# 故障排查 — 一人公司全能助手

## 常见问题

### Q1: 导入平台后提示 "连接器配置缺失"

**原因**：未配置 `wechat_official` 的 API 凭证。
**解决**：
1. 进入平台「连接器管理」页面
2. 找到 `wechat_official` 并点击「配置」
3. 填入有效的 API Key 和必要参数
4. 点击「测试连接」确认连通性

### Q2: 定时任务未按预期执行

**原因**：时区设置错误或 cron 表达式格式问题。
**解决**：
1. 检查 `scheduled_tasks.yaml` 中的 `timezone` 是否为 `Asia/Shanghai`
2. 使用在线 cron 工具验证表达式语义
3. 查看平台「任务调度」页面的执行历史

### Q3: 工作流执行超时

**原因**：输入数据量过大或下游 API 响应慢。
**解决**：
1. 减少单次处理的记录数
2. 在 `workflows/workflow.yaml` 中增加 `timeout_seconds`
3. 检查下游 API 状态和健康度

### Q4: DevKit 校验报错 "Unresolved business_skill reference"

**原因**：`employee.yaml` 中引用的 skill id 与 `skills/` 目录下的文件不匹配。
**解决**：
1. 确认 `skills/skill.yaml` 中的 `id` 与 `employee.yaml` 中的 `business_skills` 列表一致
2. 运行 `devkit validate . --strict` 查看详细错误

### Q5: 输出结果不符合预期

**原因**：输入上下文不足或参数配置不当。
**解决**：
1. 检查 `usage_examples.md` 中的输入示例格式
2. 在平台「调试模式」下逐步执行，观察中间状态
3. 调整 `options` 参数后重试

## 获取进一步帮助

- 查看平台官方文档：https://docs.digital-employee.dev
- 提交 Issue：https://github.com/your-org/digital-employees-zh/issues
- 社区讨论：https://discord.gg/digital-employee

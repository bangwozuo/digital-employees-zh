# 使用示例 — 招聘简历筛选助手

## 场景一：快速启动

1. 在数字员工平台导入本资产包
2. 配置 `boss_zhipin_api` 的 API 凭证
3. 在控制台手动触发 `resume_to_interview_flow`
4. 查看执行日志和输出结果

## 场景二：日常自动化

- 每日上午 9:00 自动执行 `screen_new_applications`
- 系统会读取配置、执行业务逻辑、发送通知
- 执行结果可在平台「任务历史」中查看

## 场景三：定时报告

- 每周一上午 9:00 自动生成 `weekly hiring funnel report`
- 报告将推送至配置的 Webhook 或邮箱
- 支持自定义报告模板和接收人

## 示例代码（Python SDK）

```python
from digital_employee_sdk import DigitalEmployeeClient

client = DigitalEmployeeClient(api_key="YOUR_API_KEY")
de = client.load_package("de_recruitment_resume_screener")

# 手动触发工作流
result = de.run_workflow("resume_to_interview_flow", inputs={
    "context": "示例上下文"
})
print(result)

# 查询任务状态
task = de.get_task("screen_new_applications")
print(task.status)
```

## 注意事项

- 首次使用前请务必阅读 `permission_notes.md`
- 建议先在沙箱环境测试再投入生产
- 定时任务时区默认为 Asia/Shanghai，可在平台调整

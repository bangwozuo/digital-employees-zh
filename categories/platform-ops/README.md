# 平台运营 (Platform Operations)

> 为平台运营团队提供技能审核、内容合规、用户反馈聚合、数据监控等数字员工能力。

## 目标用户

- 平台运营
- 内容审核
- 产品经理
- 数据运营

## 典型痛点

- 技能资产包审核标准不统一
- 内容合规检查依赖人工
- 用户反馈分散，难以聚合分析
- 平台数据监控维度不足

## 推荐数字员工资产包

- `de_platform_ops_skill_auditor` — 平台运营技能审核助手

## 推荐业务技能

- `skill_package_audit`
- `content_compliance_check`
- `feedback_aggregation`
- `platform_monitoring`

## 推荐业务连接器

- `platform_api`
- `moderation_api`
- `analytics_api`
- `ticketing_api`

## 推荐场景工作流

- `skill_submission_review_flow`
- `compliance_alert_flow`
- `feedback_to_ticket_flow`

## 高频日常任务

- `review_pending_skill_submissions`
- `scan_compliance_violations`
- `aggregate_user_feedback`

## 高频定时任务

- `daily_platform_health_report`
- `weekly_skill_quality_report`

## 开源示例

- 资产包路径：`employees/de_platform_ops_skill_auditor/`
- 使用示例：`employees/de_platform_ops_skill_auditor/docs/usage_examples.md`
- 权限说明：`employees/de_platform_ops_skill_auditor/docs/permission_notes.md`
- 故障排查：`employees/de_platform_ops_skill_auditor/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/platform-ops/employees/de_platform_ops_skill_auditor

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

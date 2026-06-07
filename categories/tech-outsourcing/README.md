# 技术外包 (Tech Outsourcing)

> 为外包需求方和服务商提供需求文档规范化、报价评估、交付物验收、风险预警等数字员工能力。

## 目标用户

- 外包需求方
- 外包项目经理
- 技术服务商
- 采购负责人

## 典型痛点

- 需求描述模糊，导致反复返工
- 报价缺乏依据，双方信任成本高
- 交付物验收标准不清晰
- 项目风险识别滞后

## 推荐数字员工资产包

- `de_outsourcing_requirement_analyst` — 外包需求分析师

## 推荐业务技能

- `requirement_clarification`
- `quote_estimation`
- `deliverable_checklist`
- `risk_assessment`

## 推荐业务连接器

- `github_api`
- `gitlab_api`
- `slack_webhook`
- `email_smtp`

## 推荐场景工作流

- `requirement_to_sow_flow`
- `milestone_acceptance_flow`
- `escalation_alert_flow`

## 高频日常任务

- `check_deliverable_submissions`
- `update_project_risk_log`
- `sync_stakeholder_status`

## 高频定时任务

- `weekly_project_health_report`
- `milestone_deadline_reminder`

## 开源示例

- 资产包路径：`employees/de_outsourcing_requirement_analyst/`
- 使用示例：`employees/de_outsourcing_requirement_analyst/docs/usage_examples.md`
- 权限说明：`employees/de_outsourcing_requirement_analyst/docs/permission_notes.md`
- 故障排查：`employees/de_outsourcing_requirement_analyst/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/tech-outsourcing/employees/de_outsourcing_requirement_analyst

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

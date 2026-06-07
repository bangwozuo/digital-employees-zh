# 销售增长 (Sales Growth)

> 为销售团队提供线索挖掘、客户画像、跟进提醒、报价生成等数字员工能力。

## 目标用户

- 销售代表
- SDR
- 销售主管
- B2B企业

## 典型痛点

- 线索来源分散，质量参差不齐
- 销售跟进节奏不一致
- 客户画像信息不完整
- 报价生成耗时，易出错

## 推荐数字员工资产包

- `de_sales_lead_digging_assistant` — 销售线索挖掘助手

## 推荐业务技能

- `lead_scoring`
- `outreach_drafting`
- `proposal_generation`
- `follow_up_reminder`

## 推荐业务连接器

- `linkedin_api`
- `salesforce_api`
- `hubspot_api`
- `email_smtp`

## 推荐场景工作流

- `lead_to_mql_flow`
- `proposal_approval_flow`
- `win_loss_analysis_flow`

## 高频日常任务

- `score_new_leads`
- `draft_personalized_outreach`
- `update_pipeline_status`

## 高频定时任务

- `weekly_pipeline_review`
- `monthly_forecast_update`

## 开源示例

- 资产包路径：`employees/de_sales_lead_digging_assistant/`
- 使用示例：`employees/de_sales_lead_digging_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_sales_lead_digging_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_sales_lead_digging_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/sales-growth/employees/de_sales_lead_digging_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

# 财税管理 (Finance and Tax)

> 为中小企业提供发票管理、费用报销、税务申报提醒、现金流预测等数字员工能力。

## 目标用户

- 财务人员
- 出纳
- 创业者
- 代理记账

## 典型痛点

- 发票验真繁琐，假票风险高
- 报销单据格式不规范
- 税务申报 deadline 易遗漏
- 现金流预测缺乏数据支撑

## 推荐数字员工资产包

- `de_finance_invoice_assistant` — 财税发票助手

## 推荐业务技能

- `invoice_verification`
- `expense_audit`
- `tax_calendar_alert`
- `cashflow_forecast`

## 推荐业务连接器

- `tax_platform_api`
- `bank_api`
- `ocr_service`
- `accounting_software_api`

## 推荐场景工作流

- `invoice_inbound_flow`
- `expense_approval_flow`
- `tax_filing_reminder_flow`

## 高频日常任务

- `scan_new_invoices`
- `verify_pending_expenses`
- `update_cash_position`

## 高频定时任务

- `weekly_cashflow_forecast`
- `monthly_tax_compliance_check`

## 开源示例

- 资产包路径：`employees/de_finance_invoice_assistant/`
- 使用示例：`employees/de_finance_invoice_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_finance_invoice_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_finance_invoice_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/finance-tax/employees/de_finance_invoice_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

# 自动化办公 (Automation Office)

> 为办公自动化场景提供表格处理、邮件批量处理、文档格式转换、流程审批等数字员工能力。

## 目标用户

- 行政人员
- 财务助理
- 运营专员
- 项目经理

## 典型痛点

- 表格数据处理重复性高
- 邮件批量发送格式易错
- 文档格式转换依赖人工
- 流程审批状态跟踪困难

## 推荐数字员工资产包

- `de_automation_office_table_assistant` — 自动化办公表格助手

## 推荐业务技能

- `spreadsheet_processing`
- `email_batch_operation`
- `document_format_conversion`
- `approval_tracking`

## 推荐业务连接器

- `excel_online_api`
- `google_sheets_api`
- `outlook_api`
- `oa_system_api`

## 推荐场景工作流

- `data_cleanup_flow`
- `mail_merge_flow`
- `format_conversion_flow`

## 高频日常任务

- `process_pending_spreadsheets`
- `send_scheduled_emails`
- `convert_document_queue`

## 高频定时任务

- `weekly_data_quality_report`
- `monthly_automation_coverage_report`

## 开源示例

- 资产包路径：`employees/de_automation_office_table_assistant/`
- 使用示例：`employees/de_automation_office_table_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_automation_office_table_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_automation_office_table_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/automation-office/employees/de_automation_office_table_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

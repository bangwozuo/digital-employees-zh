# 客户服务 (Customer Service)

> 为企业客服中心提供FAQ自动应答、工单分类、知识库维护、服务质量监控等数字员工能力。

## 目标用户

- 客服主管
- 客服代表
- 知识库管理员
- 运营负责人

## 典型痛点

- 重复性问题占用大量人工
- 工单分类不准确，流转慢
- 知识库更新滞后
- 服务质量难以量化监控

## 推荐数字员工资产包

- `de_customer_service_faq_assistant` — 客服FAQ助手

## 推荐业务技能

- `faq_auto_reply`
- `ticket_classification`
- `knowledge_base_sync`
- `quality_monitoring`

## 推荐业务连接器

- `zendesk_api`
- `freshdesk_api`
- `intercom_api`
- `feishu_webhook`

## 推荐场景工作流

- `ticket_routing_flow`
- `escalation_handoff_flow`
- `kb_update_suggestion_flow`

## 高频日常任务

- `reply_to_faq_tickets`
- `classify_new_tickets`
- `identify_kb_gaps`

## 高频定时任务

- `daily_ticket_volume_report`
- `weekly_quality_score_report`

## 开源示例

- 资产包路径：`employees/de_customer_service_faq_assistant/`
- 使用示例：`employees/de_customer_service_faq_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_customer_service_faq_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_customer_service_faq_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/customer-service/employees/de_customer_service_faq_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

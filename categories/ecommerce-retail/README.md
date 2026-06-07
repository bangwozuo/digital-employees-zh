# 电商零售 (E-commerce Retail)

> 为电商卖家提供客服应答、订单异常处理、评价管理、库存预警等数字员工能力。

## 目标用户

- 电商卖家
- 客服主管
- 店铺运营
- DTC品牌

## 典型痛点

- 客服响应慢，转化率流失
- 售后问题处理标准不统一
- 差评跟进不及时，影响店铺评分
- 大促期间客服人力不足

## 推荐数字员工资产包

- `de_ecommerce_customer_service_assistant` — 电商客服助手

## 推荐业务技能

- `pre_sales_qa`
- `order_tracking`
- `refund_processing`
- `review_management`

## 推荐业务连接器

- `taobao_api`
- `jd_api`
- `pdd_api`
- `shopify_api`

## 推荐场景工作流

- `auto_reply_workflow`
- `refund_approval_flow`
- `negative_review_escalation`

## 高频日常任务

- `reply_to_pending_inquiries`
- `process_refund_requests`
- `update_faq_knowledge_base`

## 高频定时任务

- `daily_review_reply_batch`
- `weekly_csat_report`
- `inventory_alert_check`

## 开源示例

- 资产包路径：`employees/de_ecommerce_customer_service_assistant/`
- 使用示例：`employees/de_ecommerce_customer_service_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_ecommerce_customer_service_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_ecommerce_customer_service_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/ecommerce-retail/employees/de_ecommerce_customer_service_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

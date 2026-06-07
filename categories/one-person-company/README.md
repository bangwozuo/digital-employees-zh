# 一人公司 (One-Person Company)

> 为独立创业者、自由职业者、超级个体提供全栈数字员工资产包，覆盖内容生产、客户获取、交付管理、财务记账等核心环节。

## 目标用户

- 独立创业者
- 自由职业者
- 咨询顾问
- 知识付费创作者

## 典型痛点

- 时间碎片化，无法同时处理多个业务环节
- 缺乏专业文案和设计能力
- 客户跟进容易遗漏，转化率低
- 财务记账混乱，税务合规风险高

## 推荐数字员工资产包

- `de_one_person_company_assistant` — 一人公司全能助手

## 推荐业务技能

- `content_drafting`
- `client_follow_up`
- `invoice_generation`
- `social_media_scheduling`

## 推荐业务连接器

- `wechat_official`
- `notion_api`
- `stripe_api`
- `feishu_webhook`

## 推荐场景工作流

- `daily_content_pipeline`
- `client_onboarding_flow`
- `monthly_finance_closure`

## 高频日常任务

- `check_unread_client_messages`
- `draft_social_posts`
- `update_project_status`

## 高频定时任务

- `weekly_finance_report`
- `monthly_client_retention_analysis`

## 开源示例

- 资产包路径：`employees/de_one_person_company_assistant/`
- 使用示例：`employees/de_one_person_company_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_one_person_company_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_one_person_company_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/one-person-company/employees/de_one_person_company_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

# 互联网产品研发 (Internet Product Development)

> 为产品经理和研发团队提供PRD撰写、需求评审、用户故事生成、技术方案对比等数字员工能力。

## 目标用户

- 产品经理
- 项目经理
- 业务分析师
- 研发负责人

## 典型痛点

- PRD撰写耗时过长，格式不统一
- 需求评审遗漏边界场景
- 用户故事粒度不一致
- 技术方案对比缺乏结构化框架

## 推荐数字员工资产包

- `de_product_prd_assistant` — 产品PRD助手

## 推荐业务技能

- `prd_generation`
- `user_story_splitting`
- `requirement_review`
- `tech_feasibility_check`

## 推荐业务连接器

- `jira_api`
- `confluence_api`
- `figma_api`
- `github_api`

## 推荐场景工作流

- `prd_to_ticket_flow`
- `sprint_planning_assist`
- `release_note_generation`

## 高频日常任务

- `review_pending_prd_drafts`
- `sync_jira_status`
- `check_requirement_changes`

## 高频定时任务

- `sprint_retrospective_summary`
- `weekly_product_metrics_digest`

## 开源示例

- 资产包路径：`employees/de_product_prd_assistant/`
- 使用示例：`employees/de_product_prd_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_product_prd_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_product_prd_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/internet-product-dev/employees/de_product_prd_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

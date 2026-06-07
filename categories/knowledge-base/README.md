# 知识库 (Knowledge Base)

> 为知识管理团队提供SOP生成、文档分类、知识检索、版本控制等数字员工能力。

## 目标用户

- 知识管理员
- 培训专员
- 部门负责人
- QA团队

## 典型痛点

- SOP编写耗时，更新不及时
- 文档分类混乱，检索困难
- 知识孤岛严重
- 版本变更历史不清晰

## 推荐数字员工资产包

- `de_knowledge_base_sop_generator` — 知识库SOP生成器

## 推荐业务技能

- `sop_generation`
- `document_classification`
- `semantic_search`
- `version_diff_tracking`

## 推荐业务连接器

- `confluence_api`
- `notion_api`
- `feishu_wiki_api`
- `sharepoint_api`

## 推荐场景工作流

- `doc_to_sop_flow`
- `knowledge_gap_alert_flow`
- `version_approval_flow`

## 高频日常任务

- `classify_new_documents`
- `update_search_index`
- `answer_knowledge_queries`

## 高频定时任务

- `weekly_knowledge_usage_report`
- `monthly_sop_audit`

## 开源示例

- 资产包路径：`employees/de_knowledge_base_sop_generator/`
- 使用示例：`employees/de_knowledge_base_sop_generator/docs/usage_examples.md`
- 权限说明：`employees/de_knowledge_base_sop_generator/docs/permission_notes.md`
- 故障排查：`employees/de_knowledge_base_sop_generator/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/knowledge-base/employees/de_knowledge_base_sop_generator

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

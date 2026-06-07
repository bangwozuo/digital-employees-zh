# 设计创意 (Design and Creative)

> 为设计团队提供海报文案、配色建议、素材整理、设计规范检查等数字员工能力。

## 目标用户

- 平面设计师
- 创意总监
- 品牌经理
- 电商美工

## 典型痛点

- 海报文案与视觉不匹配
- 配色方案缺乏数据支撑
- 素材库管理混乱
- 设计规范执行不一致

## 推荐数字员工资产包

- `de_design_poster_copy_assistant` — 设计海报文案助手

## 推荐业务技能

- `poster_copy_generation`
- `color_scheme_recommendation`
- `asset_tagging`
- `design_spec_check`

## 推荐业务连接器

- `figma_api`
- `canva_api`
- `adobe_api`
- `unsplash_api`

## 推荐场景工作流

- `brief_to_concept_flow`
- `design_review_flow`
- `asset_approval_flow`

## 高频日常任务

- `generate_copy_for_pending_designs`
- `tag_new_assets`
- `check_design_compliance`

## 高频定时任务

- `weekly_brand_consistency_report`
- `monthly_asset_usage_analysis`

## 开源示例

- 资产包路径：`employees/de_design_poster_copy_assistant/`
- 使用示例：`employees/de_design_poster_copy_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_design_poster_copy_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_design_poster_copy_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/design-creative/employees/de_design_poster_copy_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

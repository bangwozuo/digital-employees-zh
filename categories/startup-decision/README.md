# 创业决策 (Startup Decision)

> 为早期创业团队提供数据驱动的决策支持数字员工，覆盖竞品分析、融资材料准备、商业模式验证等场景。

## 目标用户

- 早期创业者
- 联合创始人
- 战略负责人
- 投资经理

## 典型痛点

- 缺乏系统的竞品监测机制
- 融资BP质量参差不齐，投资人反馈差
- 商业模式假设缺乏数据验证
- 市场机会窗口判断失误

## 推荐数字员工资产包

- `de_startup_decision_analyst` — 创业决策分析师

## 推荐业务技能

- `competitor_intelligence`
- `pitch_deck_review`
- `market_sizing`
- `unit_economics_modeling`

## 推荐业务连接器

- `crunchbase_api`
- `tianyancha_api`
- `pitchbook_api`
- `news_api`

## 推荐场景工作流

- `weekly_competitor_digest`
- `funding_readiness_check`
- `market_entry_scoring`

## 高频日常任务

- `scan_competitor_news`
- `update_funding_landscape`
- `track_key_metrics`

## 高频定时任务

- `weekly_investor_update`
- `monthly_strategy_review`

## 开源示例

- 资产包路径：`employees/de_startup_decision_analyst/`
- 使用示例：`employees/de_startup_decision_analyst/docs/usage_examples.md`
- 权限说明：`employees/de_startup_decision_analyst/docs/permission_notes.md`
- 故障排查：`employees/de_startup_decision_analyst/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/startup-decision/employees/de_startup_decision_analyst

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

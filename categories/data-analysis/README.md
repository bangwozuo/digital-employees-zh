# 数据分析 (Data Analysis)

> 为数据分析师和业务人员提供日报生成、异常检测、可视化建议、SQL辅助等数字员工能力。

## 目标用户

- 数据分析师
- 运营分析师
- 业务负责人
- BI工程师

## 典型痛点

- 日报制作重复性高
- 异常发现滞后
- SQL查询效率低
- 可视化规范不统一

## 推荐数字员工资产包

- `de_data_analysis_daily_report_assistant` — 数据分析日报助手

## 推荐业务技能

- `daily_report_generation`
- `anomaly_detection`
- `sql_assistant`
- `visualization_recommendation`

## 推荐业务连接器

- `mysql_connector`
- `bigquery_api`
- `clickhouse_api`
- `tableau_api`

## 推荐场景工作流

- `etl_to_report_flow`
- `alert_investigation_flow`
- `ad_hoc_query_flow`

## 高频日常任务

- `generate_morning_report`
- `check_anomaly_alerts`
- `answer_ad_hoc_queries`

## 高频定时任务

- `weekly_trend_report`
- `monthly_kpi_board_update`

## 开源示例

- 资产包路径：`employees/de_data_analysis_daily_report_assistant/`
- 使用示例：`employees/de_data_analysis_daily_report_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_data_analysis_daily_report_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_data_analysis_daily_report_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/data-analysis/employees/de_data_analysis_daily_report_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

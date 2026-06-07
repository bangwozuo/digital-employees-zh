# 财税发票助手

> 面向中小企业的财税管理数字员工，支持发票识别与验真、费用报销审核、税务日历管理和现金流预警。

## 资产包标识

- **Package ID**: `de_finance_invoice_assistant`
- **分类**: 财税管理 (`finance-tax`)
- **版本**: 1.0.0
- **作者**: digital-employee-community

## 包含组件

- `employee.yaml` — DigitalEmployee 定义
- `package.yaml` — PackageManifest 定义
- `skills/skill.yaml` — BusinessSkill 样例
- `connectors/connector.yaml` — BusinessConnector 样例
- `workflows/workflow.yaml` — ScenarioWorkflow 样例
- `tasks/daily_tasks.yaml` — DailyTask 定义
- `tasks/scheduled_tasks.yaml` — ScheduledTask 定义
- `docs/usage_examples.md` — 使用示例
- `docs/permission_notes.md` — 权限说明
- `docs/troubleshooting.md` — 故障排查
- `quality/validation_report.yaml` — QualityReport

## 快速开始

1. 阅读 `docs/usage_examples.md` 了解典型使用场景
2. 检查 `docs/permission_notes.md` 确认所需 API 权限
3. 使用 DevKit 校验：`devkit validate .`
4. 导入数字员工平台并配置连接器凭证

## 许可证

- 文档与元数据：CC-BY-4.0
- 示例代码：MIT

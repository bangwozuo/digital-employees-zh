# Contributing to Digital Employees (ZH)

感谢你对中文数字员工开源矩阵的贡献！

## 贡献类型

- **新增资产包**：在对应分类下提交新的 DigitalEmployeePackage
- **改进现有资产包**：优化 BusinessSkill、BusinessConnector、ScenarioWorkflow 定义
- **补充文档**：完善 usage_examples.md、permission_notes.md、troubleshooting.md
- **质量报告**：提交 QualityReport 改进建议

## 提交规范

### 目录与命名

- 所有目录名、ID、slug 使用小写蛇形或短横线，不使用中文路径
- 资产包目录：`categories/<category_slug>/employees/<employee_id>/`
- 文件命名：`employee.yaml`, `package.yaml`, `skill.yaml`, `connector.yaml`, `workflow.yaml`

### YAML 规范

- 使用 UTF-8 编码
- 缩进使用 2 个空格
- 所有字符串值使用双引号或字面量块（`|`）
- 必须包含 `id`, `name`, `version`, `description` 字段

### PR 流程

1. Fork 仓库并创建分支：`feature/<category>-<employee-id>`
2. 在对应分类下添加或修改文件
3. 使用 DevKit 本地校验：`devkit validate categories/<slug>/employees/<id>/`
4. 提交 PR，填写模板中的检查清单
5. 等待 CI 通过（validate-manifest、validate-links、validate-package-structure）

## 质量标准

- 每个资产包必须包含完整的 README.md、employee.yaml、package.yaml
- 至少 1 个 BusinessSkill、1 个 BusinessConnector、1 个 ScenarioWorkflow
- 必须包含 DailyTask 和 ScheduledTask 定义
- 必须包含 usage_examples.md、permission_notes.md、troubleshooting.md

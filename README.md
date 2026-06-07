# Digital Employees (ZH)

> 中文数字员工资产包集合 —— 覆盖 20 个核心商业场景，每个场景包含完整的 DigitalEmployeePackage 定义、BusinessSkill、BusinessConnector、ScenarioWorkflow、DailyTask 与 ScheduledTask。

## 30 秒快速理解

- **20 个一级分类**：从一人公司到平台运营，覆盖中小企业全链路需求。
- **每个分类 1+ 资产包**：包含 `PackageManifest`、`DigitalEmployee`、`BusinessSkill`、`BusinessConnector`、`ScenarioWorkflow` 的完整定义。
- **即插即用**：所有资产包遵循统一的 `digital-employee-spec` 标准，可直接导入数字员工平台。
- **社区共创**：欢迎提交新的数字员工资产包或改进现有定义。

## 分类速查

| 分类 | 场景 | 代表资产包 |
|------|------|-----------|
| one-person-company | 一人公司 | 全能助手 |
| startup-decision | 创业决策 | 决策分析师 |
| internet-product-dev | 互联网产品研发 | PRD 助手 |
| tech-outsourcing | 技术外包 | 需求分析师 |
| ai-app-generation | AI 应用生成 | AI 应用生成器 |
| content-marketing | 内容营销 | 内容营销助手 |
| private-domain-ops | 私域运营 | 私域运营助手 |
| ecommerce-retail | 电商零售 | 电商客服助手 |
| local-life | 本地生活 | 预约助手 |
| sales-growth | 销售增长 | 线索挖掘助手 |
| customer-service | 客户服务 | FAQ 助手 |
| finance-tax | 财税管理 | 发票助手 |
| admin-hr | 行政人事 | 会议纪要助手 |
| legal-contract | 法务合同 | 合同审查助手 |
| recruitment | 招聘面试 | 简历筛选助手 |
| data-analysis | 数据分析 | 日报助手 |
| knowledge-base | 知识库 | SOP 生成器 |
| automation-office | 自动化办公 | 表格助手 |
| design-creative | 设计创意 | 海报文案助手 |
| platform-ops | 平台运营 | 技能审核助手 |

## 快速开始

```bash
# 浏览某个分类
cd categories/one-person-company

# 查看资产包定义
cat employees/de_one_person_company_assistant/package.yaml

# 使用 DevKit 校验
devkit validate categories/one-person-company/employees/de_one_person_company_assistant/
```

## 许可证

- 文档与元数据：CC-BY-4.0
- 示例代码：MIT

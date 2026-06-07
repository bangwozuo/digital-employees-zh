# 法务合同 (Legal and Contract)

> 为法务和商务团队提供合同审查、风险条款识别、合规检查、模板管理等数字员工能力。

## 目标用户

- 法务专员
- 商务经理
- 合规负责人
- 创业者

## 典型痛点

- 合同审查周期长，影响业务进度
- 风险条款识别依赖个人经验
- 合规要求更新跟进不及时
- 合同模板版本管理混乱

## 推荐数字员工资产包

- `de_legal_contract_review_assistant` — 法务合同审查助手

## 推荐业务技能

- `contract_risk_scan`
- `compliance_check`
- `template_recommendation`
- `approval_routing`

## 推荐业务连接器

- `e_signature_api`
- `company_registry_api`
- `legal_database_api`
- `oa_system_api`

## 推荐场景工作流

- `contract_intake_flow`
- `risk_review_flow`
- `approval_signature_flow`

## 高频日常任务

- `scan_pending_contracts`
- `update_compliance_rulebase`
- `track_approval_status`

## 高频定时任务

- `weekly_contract_volume_report`
- `monthly_risk_trend_analysis`

## 开源示例

- 资产包路径：`employees/de_legal_contract_review_assistant/`
- 使用示例：`employees/de_legal_contract_review_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_legal_contract_review_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_legal_contract_review_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/legal-contract/employees/de_legal_contract_review_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

# 本地生活 (Local Life)

> 为本地生活服务商提供预约管理、排班优化、客户提醒、服务评价收集等数字员工能力。

## 目标用户

- 美容院
- 健身房
- 教培机构
- 诊所
- 家政服务

## 典型痛点

- 预约冲突频繁，客户体验差
- 到店提醒依赖人工电话，效率低
- 爽约率高，空档无法及时填补
- 服务评价收集率低

## 推荐数字员工资产包

- `de_local_life_appointment_assistant` — 本地生活预约助手

## 推荐业务技能

- `appointment_scheduling`
- `no_show_prevention`
- `satisfaction_survey`
- `slot_optimization`

## 推荐业务连接器

- `meituan_api`
- `dianping_api`
- `wechat_mini_program`
- `sms_gateway`

## 推荐场景工作流

- `appointment_confirmation_flow`
- `no_show_recovery_flow`
- `review_request_flow`

## 高频日常任务

- `confirm_next_day_appointments`
- `send_reminder_messages`
- `handle_reschedule_requests`

## 高频定时任务

- `daily_occupancy_report`
- `weekly_no_show_analysis`

## 开源示例

- 资产包路径：`employees/de_local_life_appointment_assistant/`
- 使用示例：`employees/de_local_life_appointment_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_local_life_appointment_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_local_life_appointment_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/bangwozuo/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/local-life/employees/de_local_life_appointment_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

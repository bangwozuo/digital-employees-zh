# 行政人事 (Admin and HR)

> 为行政人事部门提供会议纪要、考勤统计、入职办理、制度查询等数字员工能力。

## 目标用户

- 行政专员
- HRBP
- 部门助理
- 办公室主任

## 典型痛点

- 会议纪要整理耗时
- 待办事项跟进易遗漏
- 考勤统计手工操作多
- 制度查询响应慢

## 推荐数字员工资产包

- `de_admin_meeting_minutes_assistant` — 行政会议纪要助手

## 推荐业务技能

- `meeting_minutes_generation`
- `action_item_tracking`
- `attendance_summary`
- `policy_qa`

## 推荐业务连接器

- `feishu_api`
- `dingtalk_api`
- `zoom_api`
- `hr_system_api`

## 推荐场景工作流

- `meeting_to_minutes_flow`
- `onboarding_checklist_flow`
- `leave_approval_flow`

## 高频日常任务

- `transcribe_meeting_recordings`
- `follow_up_action_items`
- `answer_policy_questions`

## 高频定时任务

- `weekly_attendance_report`
- `monthly_meeting_analytics`

## 开源示例

- 资产包路径：`employees/de_admin_meeting_minutes_assistant/`
- 使用示例：`employees/de_admin_meeting_minutes_assistant/docs/usage_examples.md`
- 权限说明：`employees/de_admin_meeting_minutes_assistant/docs/permission_notes.md`
- 故障排查：`employees/de_admin_meeting_minutes_assistant/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/admin-hr/employees/de_admin_meeting_minutes_assistant

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

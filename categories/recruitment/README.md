# 招聘面试 (Recruitment)

> 为招聘团队提供简历筛选、面试安排、人才画像、offer生成等数字员工能力。

## 目标用户

- 招聘专员
- HRBP
- 用人经理
- 猎头顾问

## 典型痛点

- 简历量大，筛选效率低
- JD与简历匹配度判断主观
- 面试安排协调耗时
- 人才画像信息碎片化

## 推荐数字员工资产包

- `de_recruitment_resume_screener` — 招聘简历筛选助手

## 推荐业务技能

- `resume_parsing`
- `jd_matching`
- `interview_scheduling`
- `talent_profiling`

## 推荐业务连接器

- `boss_zhipin_api`
- `mokahr_api`
- `calendar_api`
- `email_smtp`

## 推荐场景工作流

- `resume_to_interview_flow`
- `offer_generation_flow`
- `onboarding_handoff_flow`

## 高频日常任务

- `screen_new_applications`
- `schedule_interviews`
- `update_pipeline_status`

## 高频定时任务

- `weekly_hiring_funnel_report`
- `monthly_talent_pool_analysis`

## 开源示例

- 资产包路径：`employees/de_recruitment_resume_screener/`
- 使用示例：`employees/de_recruitment_resume_screener/docs/usage_examples.md`
- 权限说明：`employees/de_recruitment_resume_screener/docs/permission_notes.md`
- 故障排查：`employees/de_recruitment_resume_screener/docs/troubleshooting.md`

## 平台导入说明

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/digital-employees-zh.git

# 2. 进入资产包目录
cd digital-employees-zh/categories/recruitment/employees/de_recruitment_resume_screener

# 3. 使用 DevKit 校验
devkit validate .

# 4. 导出为平台导入格式
devkit export . --output ./dist

# 5. 在数字员工平台上传 dist/ 目录下的 ZIP 和 manifest.json
```

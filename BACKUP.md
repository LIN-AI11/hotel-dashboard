# 酒店经营分析看板 · 备份索引

- 版本：V20260807-7
- 部署日期：2026-08-09
- 线上地址：https://cd4a1be4d52542e89625038a6d61d528.app.codebuddy.work/
- 本地快照：`_deploy_v22/index.html`（= `deploy/index.html`，1,644,902 字节）
- 推送方式：完整 `index.html` 与 `_deploy_v22/index.html` 经 GitHub Git Data API 推送（连接器仅有只读权限，写走 PAT 通道）。
- 备注：餐饮分析此前因云端 `fb_monthly_summary` 脏 key `'2026年年'` 污染年份下拉导致 KPI 全 0，V20260807-7 已修复（代码层 `normYrKey/normMoKey` 归一化折叠 + 云端源头清洗）。

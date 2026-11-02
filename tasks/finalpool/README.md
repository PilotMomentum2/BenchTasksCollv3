# Final task pool

This directory contains the 54 tasks marked `implemented` in the Notion Task Tracker at collection time. Each task is an exact copy of its developer-branch snapshot, preserving the complete source task tree. Existing historical Notion statuses were retained; the 29 newly reviewed tasks remain `implementing` and are not included here.

The new-task checks follow `tasks/examples`: task and agent prompts must be non-empty and English, any non-empty optional user prompt must be English, and `task_config.json` must define non-empty `needed_mcp_servers` and `needed_local_tools` containing `claim_done`. Optional scripts and workspace folders are not mandatory. No runtime/code-quality checks were added. All 29 new tasks lack the required configuration; four also violate the English-only prompt requirements.

Sources below were identified from the latest accessible developer branch snapshots. Commit-history endpoints were unavailable, so new task names were detected by comparing those snapshots with the pre-existing tracker.

| Task | Source branch | Source path |
| --- | --- | --- |
| activity-logger | `lueyang-dev` | `tasks/lueyang/activity-logger` |
| alert-system | `yuzhen-dev` | `tasks/yuzhen/alert-system` |
| asset-optimizer | `yuxuan-dev` | `tasks/yuxuan/asset-optimizer` |
| backup-utility | `xiaochen_dev` | `tasks/xiaochen/backup-utility` |
| blog-engine | `gyy` | `tasks/gyy/blog-engine` |
| booking-system | `junteng_dev` | `tasks/junteng/booking-system` |
| calendar-sync | `junteng_dev` | `tasks/junteng/calendar-sync` |
| canvas-automation | `ruige` | `tasks/ruige/canvas-automation` |
| canvas-grade-automation | `jl_dev` | `tasks/jl/canvas-grade-automation` |
| chat-bot | `lv` | `tasks/lv/chat-bot` |
| cms-builder | `gyy` | `tasks/gyy/cms-builder` |
| contact-manager | `junteng_dev` | `tasks/junteng/contact-manager` |
| content-manager | `yuxuan-dev` | `tasks/yuxuan/content-manager` |
| content-scheduler | `gyy` | `tasks/gyy/content-scheduler` |
| coupon-manager | `fan-dev` | `tasks/fan/coupon-manager` |
| crm-system | `lueyang-dev` | `tasks/lueyang/crm-system` |
| data-analytics | `ruige` | `tasks/ruige/data-analytics` |
| data-validator | `yuzhen-dev` | `tasks/yuzhen/data-validator` |
| deal-manager | `lueyang-dev` | `tasks/lueyang/deal-manager` |
| deployment-tool | `xiaochen_dev` | `tasks/xiaochen/deployment-tool` |
| email-campaign | `lueyang-dev` | `tasks/lueyang/email-campaign` |
| email-classification-system | `jl_dev` | `tasks/jl/email-classification-system` |
| error-tracker | `xiaochen_dev` | `tasks/xiaochen/error-tracker` |
| expense-tracker | `ruige` | `tasks/ruige/expense-tracker` |
| feedback-collector | `lv` | `tasks/lv/feedback-collector` |
| file-manager | `ruige` | `tasks/ruige/file-manager` |
| follow-up-reminder | `lueyang-dev` | `tasks/lueyang/follow-up-reminder` |
| form-builder | `yuzhen-dev` | `tasks/yuzhen/form-builder` |
| image-processor | `wenshuo-dev` | `tasks/wenshuo/image-processor` |
| invoice-generator | `yuzhen-dev` | `tasks/yuzhen/invoice-generator` |
| load-balancer | `zhaochen` | `tasks/zhaochen/load-balancer` |
| monitoring-agent | `xiaochen_dev` | `tasks/xiaochen/monitoring-agent` |
| network-analyzer | `yuxuan-dev` | `tasks/yuxuan/network-analyzer` |
| order-processor | `junteng_dev` | `tasks/junteng/order-processor` |
| payment-processor | `yuzhen-dev` | `tasks/yuzhen/payment-processor` |
| pdf-report-generator | `jl_dev` | `tasks/jl/pdf-report-generator` |
| permission-manager | `yuzhen-dev` | `tasks/yuzhen/permission-manager` |
| personalization-service | `lv` | `tasks/lv/personalization-service` |
| price-tracker | `fan-dev` | `tasks/fan/price-tracker` |
| product-catalog | `junteng_dev` | `tasks/junteng/product-catalog` |
| qr-generator | `junxian_dev` | `tasks/junxian/qr-generator` |
| reminder-service | `junteng_dev` | `tasks/junteng/reminder-service` |
| sales-pipeline | `lueyang-dev` | `tasks/lueyang/sales-pipeline` |
| search-engine | `wenshuo-dev` | `tasks/wenshuo/search-engine` |
| security-scanner | `xiaochen_dev` | `tasks/xiaochen/security-scanner` |
| sentiment-analyzer | `lv` | `tasks/lv/sentiment-analyzer` |
| shipment-tracker | `junteng_dev` | `tasks/junteng/shipment-tracker` |
| social-publisher | `gyy` | `tasks/gyy/social-publisher` |
| subtitle-generator | `haoze` | `tasks/haoze/subtitle-generator` |
| task-scheduler | `yuxuan-dev` | `tasks/yuxuan/task-scheduler` |
| template-engine | `zhaochen` | `tasks/zhaochen/template-engine` |
| translation-api | `junxian_dev` | `tasks/junxian/translation-api` |
| video-trimmer | `haoze` | `tasks/haoze/video-trimmer` |
| voice-processor | `lv` | `tasks/lv/voice-processor` |

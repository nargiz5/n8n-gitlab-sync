## 2026-08-26 07:00:53 (Baku, GMT+4) — Gitlab-n8n-synchronization-prod

Replaced manual trigger with schedule trigger, removed node path parameters from two Wait nodes, and updated connections accordingly.

### Added
- Added node "Schedule Trigger" (n8n-nodes-base.scheduleTrigger).
- Connection added from "Schedule Trigger" to "n8n_backup.sh".

### Removed
- Removed node "When clicking ‘Execute workflow’" (n8n-nodes-base.manualTrigger).
- Connection removed from "When clicking ‘Execute workflow’" to "n8n_backup.sh".

## 2026-08-25 14:31:04 (Baku, GMT+4) — Gitlab-n8n-synchronization-prod

New workflow file added to GitLab.


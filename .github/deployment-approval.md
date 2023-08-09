---
title: Deployment Approval Required for {{ env.ENVIRONMENT }}
labels: deployment-requested
---

Deployment Approval requested from {{ payload.sender.login }}.

Issue will be automatically closed after success deploy

=== DON'T CHANGE BELOW THIS LINE
```json target_payload
{
    "runNumber":  {{ env.RUNNUMBER }},
    "environment": "{{ env.ENVIRONMENT }}"
}
```

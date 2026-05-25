# azure-security-posture-dashboard
This project demonstrates the deployment of a cloud-native Azure Security Monitoring and Security Posture Management environment 
azure-security-posture-dashboard/
│
├── README.md
├── architecture/
│   ├── architecture-diagram.png
│   ├── sentinel-data-flow.png
│
├── docs/
│   ├── 01-resource-group-setup.md
│   ├── 02-log-analytics-workspace.md
│   ├── 03-defender-for-cloud.md
│   ├── 04-sentinel-onboarding.md
│   ├── 05-azure-monitor-agent.md
│   ├── 06-data-collection-rules.md
│   ├── 07-azure-policy.md
│   ├── 08-workbook-dashboard.md
│   ├── 09-kql-detections.md
│   ├── 10-incident-response.md
│
├── kql/
│   ├── heartbeat-query.kql
│   ├── failed-logons.kql
│   ├── successful-logons.kql
│   ├── azure-activity.kql
│   ├── nsg-events.kql
│   ├── security-alerts.kql
│
├── screenshots/
│   ├── sentinel-overview.png
│   ├── ama-installed.png
│   ├── heartbeat-results.png
│   ├── security-events.png
│   ├── workbook-dashboard.png
│
├── automation/
│   ├── logic-app-playbook.md
│   ├── automation-rules.md
│
├── policies/
│   ├── require-tags-policy.json
│   ├── audit-public-ip-policy.json
│

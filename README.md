# Oracle Fusion Cloud Applications Common Features REST API Collection

[![Release](https://img.shields.io/badge/Release-26C-0A85EA?style=flat-square)](https://github.com/saikumargudelly/oracle-fusion-rest-api-collection/releases/tag/v26C)
[![API Coverage](https://img.shields.io/badge/Coverage-100%25%20(485%20Endpoints)-brightgreen?style=flat-square)](https://docs.oracle.com/en/cloud/saas/applications-common/26c/farca/rest-endpoints.html)
[![Postman Schema](https://img.shields.io/badge/Postman-v2.1.0-FF6C37?style=flat-square&logo=postman&logoColor=white)](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
[![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)](LICENSE)

Production-aligned Postman collection providing 100% complete coverage (485 endpoints across 61 resource categories) for Oracle Fusion Cloud Applications Common Features Update **26C** (Release 26C).

---

## Downloads

[![Download Collection](https://img.shields.io/badge/Download-Postman_Collection-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://github.com/saikumargudelly/oracle-fusion-rest-api-collection/releases/latest/download/oracle_fusion_cloud_common_26c_postman_collection.json)
[![Download Environment](https://img.shields.io/badge/Download-Environment_Template-007ACC?style=for-the-badge&logo=postman&logoColor=white)](https://github.com/saikumargudelly/oracle-fusion-rest-api-collection/releases/latest/download/oracle_fusion_cloud_common.postman_environment.json)

---

## Quick Start

1. **Import:** Download and import [`oracle_fusion_cloud_common_26c_postman_collection.json`](https://github.com/saikumargudelly/oracle-fusion-rest-api-collection/releases/latest/download/oracle_fusion_cloud_common_26c_postman_collection.json) and [`oracle_fusion_cloud_common.postman_environment.json`](https://github.com/saikumargudelly/oracle-fusion-rest-api-collection/releases/latest/download/oracle_fusion_cloud_common.postman_environment.json) into Postman.
2. **Select Environment:** Choose `Oracle Fusion Cloud Common Environment`.
3. **Configure Credentials:**

| Variable | Description | Example |
| :--- | :--- | :--- |
| `baseUrl` | Fusion Cloud root host URL | `https://servername.fa.us2.oraclecloud.com` |
| `username` | API user login | `fusion_api_user` |
| `password` | API password / key | `••••••••••••` |
| `bearerToken` | OAuth 2.0 / JWT token *(optional)* | `eyJhbGciOi...` |
| `restFrameworkVersion` | ADF REST Framework version header (default: `4`) | `4` |

*Supports both HTTP Basic Authentication (configured at collection root) and OAuth 2.0 / JWT Bearer token header.*

---

## API Coverage

| Domain | Key Capabilities |
| :--- | :--- |
| **Fusion AI & Automation** | Agent triggers, Fusion AI execution, and AI Agent-to-Agent (A2A) protocol APIs. |
| **Enterprise Lookups & Values** | Common lookups, standard lookups, generic lookups, set-enabled lookups, lookups LOV, and value sets. |
| **SetID Partitioning** | Set ID reference groups, set definitions, asset book, business unit, cost organization, and project unit set assignments. |
| **Setup & Migration (FSM)** | Configuration set migration (CSM), setup offering CSV exports/imports, setup task CSV exports/imports, template exports, and setup tasks. |
| **Security, Users & Auditing** | Users, roles, persons, user account requests, sign-in/sign-out audits, and audit setup/reports. |
| **Task Management & Scheduling** | Manage tasks, enterprise scheduler service (ESS) jobs, schedules, and request executions. |
| **Localization & Reference Data** | Currencies, languages, natural languages, territories, time zones, and taxonomy nodes. |
| **UI Experience & Help Center (ATK)** | Announcements, themes, popup items, and ATK help center user assistance platform (UAP) keys. |
| **Core Platform** | Bulk operations, REST resource metadata schemas, and resource types. |

---

## License & Disclaimer

This project is licensed under the MIT License. Oracle and Oracle Fusion Cloud Applications are registered trademarks of Oracle Corporation. This repository is an independent community resource and is not affiliated with or endorsed by Oracle.

# WebGuard SOC Lab

WebGuard SOC Lab là project mô phỏng một hệ thống giám sát an ninh cho website.

## Architecture

```text
User
  ↓
Nginx Webserver
  ↓ JSON Access Log
Wazuh SIEM
  ↓ Security Alert
Shuffle SOAR
  ↓
Analyst Case


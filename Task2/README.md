\# 🚀 Task 2 - n8n with Docker



\## Objective

Run n8n using Docker, activate the license, and verify successful setup.



---



\## Steps Followed



1️⃣ Pulled n8n Docker image  

2️⃣ Ran n8n with:

```bash

docker run -it --rm -p 5678:5678 -e N8N\_BASIC\_AUTH\_ACTIVE=true -e N8N\_BASIC\_AUTH\_USER=admin -e N8N\_BASIC\_AUTH\_PASSWORD=StrongPass@123 n8nio/n8n




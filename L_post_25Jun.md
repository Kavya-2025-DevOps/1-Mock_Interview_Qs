
Q1. How would you approach migrating a monolithic application to a microservices architecture? What steps would you follow, and what key challenges might you encounter during the migration process?
Q2. After deploying an application, it becomes slow. How would you troubleshoot the issue and rectify it?
Q3. What happens if the Terraform state file stored in an Amazon S3 bucket is accidentally deleted? How would you recover it and prevent such incidents in the future?
Q4. What Jenkins strategy and pipeline type did you use?
Q5. What Kubernetes deployment strategy did you use in your project?
Q6. What is immutable infrastructure in Terraform? How does Terraform support the concept of immutability?
Q7. Do you maintain a single CI/CD pipeline for all environments (Development, SIT, UAT, and Production), or do you use separate pipelines? How do you manage environment-specific configurations and deployments?



##

If you want to ace senior-level engineering interviews, you need a systematic approach to tackle nightmares like these:
🚨 The Initial Triage: The website is down, or logs suddenly stop appearing in Grafana/Datadog altogether. What is your absolute first troubleshooting step to isolate the blast radius?
📉 Performance Degradation: Application response time balloons to 5 seconds, or CPU suddenly spikes to 100% on production servers. How do you investigate without making things worse?
🕵️‍♂️ Silent Killers: Memory usage keeps increasing every single day (classic memory leak), or a deployment completes successfully but users are hit with intermittent 500 errors.
💥 Resource Starvation: Database connections are completely exhausted in production right after a major release. How do you roll back or remediate instantly?


##

━━━━━━━━━━
🟢 ROUND 1 — Core Fundamentals
━━━━━━━━━━━━

🐳 Docker
- Define a Dockerfile & its role
- How do you secure a Docker image?
- Scenario: securely storing & distributing images

🏗️ IaC
- CloudFormation vs Terraform — when to use each?
- What is Terraform "State"?
- What happens with configuration drift?

📊 Monitoring
- Prometheus vs Grafana — purpose?
- Metric vs Trace — what's the difference?

☁️ AWS
- CloudFront use cases
- Subnets & Security Groups — why they matter
- Cost optimization strategies you've used

⚡ Serverless
- Lambda vs EC2 — when to choose which?

🌐 Networking & K8s
- SLI, SLO, SLA — definitions
- Kubernetes high-level architecture
- VPC peering & interconnectivity
- VPC ↔ On-prem connectivity (which gateways?)

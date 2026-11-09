<h1 align="center">Jorge Echeverria</h1>
<h3 align="center">Software Engineer · Fintech · Cloud · Go Backend · iOS (Swift)</h3>

<p align="center">
  <a href="https://linkedin.com/in/jorge-echeverria2710"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jfloresjef365@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Based_in-New_York-111827?style=flat" alt="New York"/>
  <img src="https://img.shields.io/badge/Languages-English_%7C_Spanish_%7C_German_(A2)-111827?style=flat" alt="English | Spanish | German (A2)"/>
</p>

---

### About me

I build the software behind money: receivables, payments, balances and the cloud infrastructure that keeps them running.
I'm a software engineer and digital business student, so I care as much about the business rule as about the code that enforces it.

- 💳 **Fintech:** accounts receivable, payment collection, settlements, promo/discount engines, money stored as integer cents
- ☁️ **Cloud:** AWS serverless and event-driven architectures, Azure, Terraform, Kubernetes, CI/CD and DevSecOps
- 🐹 **Backend in Go:** JSON APIs on PostgreSQL, multi-tenant SaaS, single-binary deploys
- 🍎 **iOS:** native apps with Swift and SwiftUI, plus cross-platform mobile with Flutter
- 📈 **Interested in:** quantitative trading and market data analysis
- 🌍 **Languages:** English, Spanish and German (A2, working toward B1)

---

### Tech stack

**Backend & data**<br/>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white"/>

**Cloud & DevOps**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white"/>

**Mobile & frontend**<br/>
<img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white"/>
<img src="https://img.shields.io/badge/SwiftUI-0D96F6?style=flat&logo=swift&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>

---

### Featured projects

#### 💳 [SaaS_CxC](https://github.com/Jechev1/SaaS_CxC) · Go · PostgreSQL · Docker
Multi-tenant **accounts-receivable + CRM SaaS** for wholesale distributors.
Payments, write-offs, adjustments with review, and **field collections**: numbered receipts signed by the customer, collector settlement, payment promises, WhatsApp reminders, PDF statements and Excel export.
- Go JSON API and a dependency-free web UI served by the **same binary**
- Tenant isolation with PostgreSQL **Row Level Security** on every tenant table
- New companies onboarded from the CLI with no code change or redeploy
- ~280 automated end-to-end checks across receivables, collections and payment promises
- Production setup with Docker, Caddy, and backup/restore scripts

#### ☁️ [CloudShop on AWS](https://github.com/Jechev1/nube1) · Terraform · Lambda · EventBridge
Serverless e-commerce backend provisioned **100% with Terraform**: S3 + CloudFront + WAF, API Gateway with Cognito JWT auth, DynamoDB, and an `OrderCreated` event fanned out through EventBridge to inventory, audit and email Lambdas.
Observability with a CloudWatch dashboard, 14 alarms and DLQs. I found and fixed a real IAM/SES permissions bug through those alarms.

#### 🔁 [Event-driven orders & saga](https://github.com/Jechev1/devsecops-lab13) · AWS · Kubernetes · DevSecOps
Order pipeline with a **saga orchestrator**, SNS fan-out, a CQRS read model, distributed tracing and alert tests. It runs on a DevSecOps pipeline with SonarQube, Terraform modules per environment and Kubernetes manifests.

#### 🏢 [CloudBox Enterprise](https://github.com/Jechev1/cloudbox-enterprise) · Terraform · Cognito · SQS
Cloud platform on AWS: Cognito, API Gateway, Lambda producers/consumers over SQS, DynamoDB, and S3 + CloudFront hosting, deployed through GitHub Actions.

#### ⚙️ [K3s on Azure](https://github.com/Jechev1/Lab5-DevOps) · Azure · Terraform · Kubernetes
API + PostgreSQL deployed to K3s on an Azure VM: Terraform networking, NSG and VM, `cloud-init` bootstrap, images published to GHCR by GitHub Actions, and Traefik ingress.

---

### Collaborations

These are team projects hosted on teammates' accounts where I contributed code.

| Project | What it is | My role |
|---|---|---|
| 💸 [Kaval](https://github.com/laujml/Kaval) | Flutter app for splitting group expenses on trips: who owes whom, group cash, voice input, QR invites; amounts stored in cents | **Top contributor** |
| 🏷️ [Promora Promo Engine](https://github.com/luciaT1212/promora-promo-engine) | NestJS + Prisma promo-code engine with chained validations and `fixed` / `percent` / `tiered` discount strategies | **Co-lead** (half of all commits) |
| 📦 [Distribuidora](https://github.com/laujml/Distribuidora) | Desktop system for a distributor built with PyQt6, pandas, matplotlib and openpyxl | Core contributor |
| 🛍️ [Naturally Stunning](https://github.com/laujml/NaturallyStunning) | Full-stack beauty e-commerce: catalog, cart and order management ([live demo](https://laujml.github.io/NaturallyStunning/)) | **Main developer** |
| 🎟️ [La Cuponera](https://github.com/laujml/la-cuponera) | Coupon marketplace built with React + Vite | **Main developer** |
| 🚚 [Fleet Management API](https://github.com/laujml/flotaAPIs) | RESTful fleet API with NestJS, Prisma and PostgreSQL | Backend contributor |
| 🤝 [Volunteer](https://github.com/MarjorieMonson/volunteer) | Next.js + TypeScript platform connecting organizations and volunteers: events, calendar, org dashboard, admin | **Top contributor** |
| 🧩 [CMS API: design patterns](https://github.com/laujml/tallerPatrones) | Express + TypeScript CMS API applying GoF design patterns | Contributor |

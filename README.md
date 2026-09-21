<img src="header.svg"></img>

<h1 align="center">Amsal Khan</h1>

<p align="center">
  <a href="https://github.com/Amsal1">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=800&color=4478E3&center=true&vCenter=true&width=700&lines=Senior+DevOps+Engineer+%40+BukuWarung;Securing+FinTech+payment+rails+on+AWS;Reliability+%E2%80%A2+Cloud+Security+%E2%80%A2+Cost+Engineering;Terraform+%E2%80%A2+Kafka+%E2%80%A2+Aurora+%E2%80%A2+ECS+%E2%80%A2+CloudHSM" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/amsal-khan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:md.amsalkhan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://rebrand.ly/AmsalResume"><img src="https://img.shields.io/badge/Résumé-2F855A?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume"/></a>
  <a href="https://stackoverflow.com/users/9513172/amsal-khan"><img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow"/></a>
  <a href="https://forum.xda-developers.com/m/amsal1.7050192/"><img src="https://img.shields.io/badge/XDA-EA7100?style=for-the-badge&logo=xdadevelopers&logoColor=white" alt="XDA"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Amsal1&label=Profile%20views&color=4478e3&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/badge/Based%20in-Jakarta,%20Indonesia-4478e3?style=flat-square&logo=googlemaps&logoColor=white" alt="Location"/>
  <img src="https://img.shields.io/badge/Open%20to-Collaboration-2F855A?style=flat-square" alt="Open to collaboration"/>
</p>

---

## 👋 About

I'm a **Senior DevOps / SRE / Platform Engineer** at **[BukuWarung](https://bukuwarung.com)**, where I build, secure, and scale high-throughput payment infrastructure serving **100K+ merchants** across Indonesia. Four-plus years of end-to-end ownership: from Terraform modules and Aurora failover automation down to HSM key ceremonies and VAPT closure.

My default lens is **security-first cloud engineering** — if it touches money, it gets threat-modelled, encrypted in transit, least-privileged, and audited before it ships.

```yaml
name:      Amsal Khan
role:      Senior DevOps Engineer @ BukuWarung (FinTech · Payments)
domain:    Payments, EDC/POS, QRIS, banking integrations
focus:     Cloud Security · Reliability Engineering · IaC · FinOps · AI Platform
cloud:     AWS (primary) · GCP
philosophy: "Automate the boring. Encrypt the rest. Alert on what matters."
ask_me_about:
  - Payment security (HSM, TMK injection, mTLS, X.509)
  - Zero-downtime Postgres/Aurora upgrades & partitioning
  - Terraform at scale, OIDC keyless CI/CD
  - Cutting cloud bills without cutting reliability
```

---

## ⚡ Impact Highlights

<table>
  <tr>
    <td width="33%" align="center">
      <h3>💸 $16K / month</h3>
      <sub>Cloud spend eliminated across AWS + GCP via Graviton migrations, resource consolidation, log retention and BigQuery partitioning</sub>
    </td>
    <td width="33%" align="center">
      <h3>⏱️ 30 min → &lt;1 min</h3>
      <sub>Aurora failover recovery on the core payments platform, fully automated with zero manual intervention</sub>
    </td>
    <td width="33%" align="center">
      <h3>🚀 sub-100ms</h3>
      <sub>Stateless Rust callback service meeting a 3s partner SLA on the QRIS payment path</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <h3>🏪 100K+ merchants</h3>
      <sub>Scale of the payment platforms I own reliability for, as on-call lead and RCA author</sub>
    </td>
    <td align="center">
      <h3>🔐 ISO 27001</h3>
      <sub>Driven from the SRE/Infra side — DR plans, runbooks and audit evidence across annual cycles</sub>
    </td>
    <td align="center">
      <h3>🤖 AI platform in prod</h3>
      <sub>Internal AI agent platform on ECS/Fargate via Terraform, with LLM observability through Langfuse</sub>
    </td>
  </tr>
</table>

---

## 🔐 Security in the Cloud

Security isn't a side quest for me — it's most of the job when the workload is regulated payments.

<details open>
<summary><b>Cryptography & Key Management</b></summary>

- **HSM-backed key management** for payment terminals — master key custody and secure key injection, with mTLS between device and platform
- **Device identity at fleet scale** — per-device **X.509** certificates over a managed PKI, replacing shared credentials
- **Message-level integrity** on partner payment flows — HMAC and RSA signature verification, plus **PGP**-encrypted file exchange with banking partners

</details>

<details open>
<summary><b>Identity, Secrets & Access</b></summary>

- **Keyless OIDC federation** for CI/CD, so pipelines hold no long-lived cloud credentials
- **Short-lived, audited database credentials** issued on demand, and least-privilege secret distribution across environments
- **SSO-enforced VPN** fronting sensitive internal apps, plus custom IdP work to put per-credential network policy behind managed file transfer

</details>

<details open>
<summary><b>Network Isolation & Assurance</b></summary>

- **Private connectivity to banking partners and payment switchers** over dedicated leased lines and IPSec tunnels in a hub-and-spoke topology
- **Edge and WAF policy** — TLS posture, origin protection and request-level access control as a self-service capability for engineers
- **Owned VAPT cycles end to end**, from finding triage through remediation to verification

</details>

<details>
<summary><b>Responsible Disclosure & Recognition</b></summary>

- 🏅 Reported a stored **XSS** vulnerability to **Microsoft (MSRC)** — 2018
- 🏅 Reported **SQL injection (MySQLi)** vulnerabilities to **CPGRAMS, Government of India** — 2018
- 🏅 Bug bounty awarded by **PayPro Global** — 2018
- 🏅 **Star Performer of the Month** among 100+ DevOps engineers at To The New — 2022
- 🔎 DevSecOps automation with **Fortify WebInspect** (DAST/SAST) for a leading insurer's compliance programme
- 🐍 Built an automated **AWS security-audit tool** in Python/boto3, cutting audit turnaround significantly

</details>

---

## 🧰 Tech Stack

<table>
<tr><td valign="top" width="50%">

**☁️ Cloud & Networking**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&labelColor=232F3E)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Route 53](https://img.shields.io/badge/Route%2053-8C4FFF?style=flat-square&labelColor=232F3E)
![VPC](https://img.shields.io/badge/VPC%20·%20TGW%20·%20Direct%20Connect-232F3E?style=flat-square)
![CloudFront](https://img.shields.io/badge/CloudFront%20·%20ALB-232F3E?style=flat-square)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white)

</td><td valign="top" width="50%">

**🏗️ Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&labelColor=232F3E)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white)

</td></tr>
<tr><td valign="top">

**🔁 CI/CD & Containers**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ECS](https://img.shields.io/badge/ECS%20·%20Fargate-FF9900?style=flat-square&labelColor=232F3E)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</td><td valign="top">

**🔐 Security**

![CloudHSM](https://img.shields.io/badge/CloudHSM%20·%20KMS-DD344C?style=flat-square&labelColor=232F3E)
![Secrets Manager](https://img.shields.io/badge/Secrets%20Manager%20·%20Parameter%20Store-DD344C?style=flat-square&labelColor=232F3E)
![TLS](https://img.shields.io/badge/TLS%20%2F%20mTLS-1E7B45?style=flat-square&logo=letsencrypt&logoColor=white)
![GnuPG](https://img.shields.io/badge/PGP%20%2F%20GnuPG-0093DD?style=flat-square&logo=gnuprivacyguard&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![OIDC](https://img.shields.io/badge/OIDC%20%2F%20SSO-EB5424?style=flat-square&logo=auth0&logoColor=white)

</td></tr>
<tr><td valign="top">

**🗄️ Data & Streaming**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Aurora](https://img.shields.io/badge/Aurora%20·%20RDS-527FFF?style=flat-square&labelColor=232F3E)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&labelColor=232F3E)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square&labelColor=232F3E)
![Kafka](https://img.shields.io/badge/Kafka%20·%20MSK-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

</td><td valign="top">

**📊 Observability**

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![ELK](https://img.shields.io/badge/ELK%20Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![PagerDuty](https://img.shields.io/badge/PagerDuty-06AC38?style=flat-square&logo=pagerduty&logoColor=white)

</td></tr>
<tr><td valign="top">

**💻 Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</td><td valign="top">

**🤖 Automation & AI Platform**

[![AxonFlow](https://img.shields.io/badge/AxonFlow-5B21B6?style=flat-square)](https://getaxonflow.com/)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

</td></tr>
</table>

---

## 🌱 Open Source

Contributor to the tooling I run in production — **[Langfuse](https://github.com/langfuse/langfuse)**,
**[n8n](https://github.com/n8n-io/n8n)** and adjacent platform projects. Running something at scale
tends to surface the rough edges worth fixing upstream.

Previously an **Android custom ROM and kernel maintainer**, shipping builds and device trees across
several AOSP-based ROMs (Project-Xtended, Corvus-OS, NamelessAOSP). That work is retired now, but
it's where I learned to read other people's systems code and debug things with no stack trace.

Selected personal projects:

| Project | Stack |
|---|---|
| [AWS EKS Terraform Module](https://rebrand.ly/ekst) | Terraform, EKS, VPC, S3, Docker — multi-AZ with autoscaling |
| [Jenkins Multibranch CI/CD on EC2](https://rebrand.ly/zulwk7i) | Jenkins, EC2, Docker, GitHub |
| [Automatic Attendance Bot](https://bit.ly/394jHRb) | Python, Selenium, Telegram API, Heroku CI/CD |

---

## 📈 GitHub Activity

> 🔒 Most of my day-to-day engineering ships from a separate **private work account**. The first
> card aggregates that output — commit and PR volume only, no repository or project detail.

<div align="center">

<img height="175" src="https://raw.githubusercontent.com/Amsal1/Amsal1/master/profile/work-stats.svg" alt="Private work activity"/>

<img height="175" src="https://raw.githubusercontent.com/Amsal1/Amsal1/master/profile/stats.svg" alt="Public GitHub stats"/>
<img height="175" src="https://raw.githubusercontent.com/Amsal1/Amsal1/master/profile/top-langs.svg" alt="Most used languages in public repos"/>

<img src="https://raw.githubusercontent.com/Amsal1/Amsal1/master/profile/snake.svg" alt="Contribution snake"/>

</div>

<p align="center">
  <sub>Cards generated by <a href="https://github.com/stats-organization/github-stats-extended">github-stats-extended</a> via GitHub Actions — no external widget hosting to break.</sub>
</p>

---

<p align="center">
  <i>⚡ Fun fact: I collect airports and timezones — travelling to new places is how I reset between incidents.</i>
</p>

<p align="center">
  <b>Let's build something reliable and secure.</b><br/>
  <a href="mailto:md.amsalkhan@gmail.com">md.amsalkhan@gmail.com</a> ·
  <a href="https://linkedin.com/in/amsal-khan">LinkedIn</a> ·
  <a href="https://rebrand.ly/AmsalResume">Résumé</a>
</p>

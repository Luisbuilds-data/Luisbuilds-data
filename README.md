<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0,0D1B2A,00D9C0&height=210&section=header&text=Luis%20Sanchez&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineer%20%7C%20Lakehouse%20Architect%20%7C%20DataOps&descAlignY=58&descSize=20" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ingénieur%20de%20données-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/Lakehouse%20Architect-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/AWS%20·%20dbt%20·%20Iceberg-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/DataOps%20Engineer-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍%20Ottawa%2C%20ON-0D1B2A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🏠%20Télétravail%20Canada-1A2744?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🌐%20FR%20%7C%20EN%20%7C%20ES-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/🚀%20Open%20to%20Opportunities-F0A500?style=for-the-badge&logoColor=0D1B2A" />
</p>

---

## 👨‍💻 À propos | About

Bilingual (FR/EN/ES) data engineer with a broadcast operations background at CBC/Radio-Canada, now building production-grade cloud data infrastructure on AWS. I design and operate end-to-end pipelines — raw ingest through validated Apache Iceberg marts — with a focus on observability, resilience, and cost-effective architecture. My current flagship project is a live trading data lakehouse processing ~500 events/day across 22 dbt models, with a 5-minute systemd cadence, Great Expectations quality gates, and Wazuh/Suricata security monitoring integrated from day one. I thrive at the intersection of DataOps, infrastructure-as-code, and financial signal intelligence.

---

## 🚀 Projet phare | Featured Project

<details>
<summary><b>🏗️ Production Data Lakehouse Platform — cliquer pour développer | click to expand</b></summary>

<br/>

> A production-grade AWS data lakehouse for financial market and meme-coin signal intelligence — built, operated, and iterated in live conditions.

| Dimension | Detail |
|:---|:---|
| **Throughput** | ~500 events/day, 5-min systemd cadence |
| **dbt models** | 22 models (staging → intermediate → marts) |
| **Storage format** | Apache Iceberg Copy-on-Write (CoW) on S3 |
| **Validation** | Great Expectations checkpoint suite per layer |
| **Orchestration** | systemd timers + Prefect hybrid deployment |
| **Security** | Wazuh SIEM + Suricata IDS, composite alert rules |
| **Signal delivery** | Tier 1/2/3 meme-coin alerts → Telegram |
| **Compute** | AWS EC2 + RDS PostgreSQL (multi-schema) |

**Architecture highlights:**
- Raw ingest → `raw.*` PostgreSQL → dbt staging → Iceberg marts on S3
- Volume spike Tier 3 precursor detection: spike ratio ≥ 3.0× AND volume ≥ $500k
- Per-session funnel counters on OANDA trading signal pipeline (8-stage instrumentation)
- Wazuh composite frequency rules: base level 3 + alert at 3 hits/300s → level 9 page

</details>

---

## 🛠️ Stack technique | Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,postgresql,docker,git,aws,linux,bash&theme=dark" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Iceberg-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/Great%20Expectations-F0A500?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/Prefect-1A2744?style=for-the-badge&logoColor=00D9C0" />
  <img src="https://img.shields.io/badge/Wazuh%20SIEM-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/systemd-0D1B2A?style=for-the-badge&logoColor=00D9C0" />
  <img src="https://img.shields.io/badge/AWS%20SSM%20%2F%20EC2-F0A500?style=for-the-badge&logo=amazonaws&logoColor=0D1B2A" />
</p>

---

## 💼 Expérience | Experience

### 🏛️ IT Technician — *Parliament of Canada, Ottawa*

- Provided bilingual (FR/EN) hardware and software support across parliamentary offices, ensuring continuity of operations in a high-security government environment
- Diagnosed and resolved endpoint, network, and peripheral issues for MPs, senators, and administrative staff under strict SLA and confidentiality requirements
- Applied government IT security policies (GC security baseline, access controls) while delivering responsive, professional service-desk support in a dual-language workplace

---

### 📡 Network Operations Centre (NOC) Technician — *CBC/Radio-Canada, Ottawa*

- Monitored and maintained national broadcast infrastructure for Canada's public broadcaster (FR + EN networks)
- Real-time incident response, escalation management, and systems diagnosis across 24/7 live broadcast operations
- Developed deep observability instincts — uptime culture, alert fatigue mitigation, runbook discipline — that now directly inform data infrastructure design

---

## 🎓 Formation & Certifications | Education & Certifications

<p align="center">

| | |
|:---|:---|
| 🏫 **La Cité collégiale** | Computer Science / Data Technology · Ottawa, ON |
| ✅ **dbt Fundamentals** | Certified · dbt Labs |
| 🔄 **AWS Cloud Practitioner** | En cours · In progress |

</p>

---

## 🌐 Langues | Languages

<p align="center">
  <img src="https://img.shields.io/badge/Français-Langue%20maternelle-00D9C0?style=for-the-badge&logoColor=0D1B2A" />
  <img src="https://img.shields.io/badge/English-Professional%20proficiency-1A2744?style=for-the-badge&logoColor=00D9C0" />
  <img src="https://img.shields.io/badge/Español-Conversationnel-F0A500?style=for-the-badge&logoColor=0D1B2A" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Luisbuilds-data&show_icons=true&theme=tokyonight&bg_color=0D1B2A&title_color=00D9C0&icon_color=F0A500&text_color=ffffff&border_color=00D9C0&hide_border=false&count_private=true" height="170"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Luisbuilds-data&layout=compact&theme=tokyonight&bg_color=0D1B2A&title_color=00D9C0&text_color=ffffff&border_color=00D9C0&langs_count=6" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Luisbuilds-data&theme=tokyonight&background=0D1B2A&ring=00D9C0&fire=F0A500&currStreakLabel=00D9C0&sideLabels=ffffff&border=00D9C0" />
</p>

---

## 🐍 Contribution Grid

<p align="center">
  <img src="https://raw.githubusercontent.com/Luisbuilds-data/Luisbuilds-data/output/github-contribution-grid-snake-dark.svg" alt="snake contribution animation" />
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0,00D9C0,0D1B2A&height=130&section=footer" width="100%"/>
</p>

<p align="center">
  <i>« Les données racontent une histoire — à nous de bien l'écouter. »</i><br/>
  <sub><i>Data tells a story — the craft is in listening carefully.</i></sub>
</p>

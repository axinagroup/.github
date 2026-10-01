<div align="center">

# Axina Group

**Enterprise software for finance, operations, and climate projects.**

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Frappe" src="https://img.shields.io/badge/Frappe-0089FF?style=for-the-badge&logo=frappe&logoColor=white" />
  <br/>
  <img alt="Hyperledger Fabric" src="https://img.shields.io/badge/Hyperledger%20Fabric-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white" />
  <img alt="Cardano" src="https://img.shields.io/badge/Cardano-0033AD?style=for-the-badge&logo=cardano&logoColor=white" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
</p>

</div>

---

## About us

Axina Group builds integrated business platforms that combine enterprise resource planning, AI, and distributed-ledger technology. Our work covers an ERP for running the business end to end, an AI-assisted post-trade platform for boutique brokerages, carbon-project tools that use satellite data and machine learning to estimate REDD+ carbon credits and tokenize them, government onboarding workflows for carbon projects, and AI assistants that automate day-to-day project management. The common goal: less manual back-office work, fewer errors, and records you can verify.

---

## Our platforms

### 🏢 AXERP: Enterprise Resource Planning

AXERP is Axina Group's ERP platform, built on the Frappe Framework. It brings accounting, inventory, manufacturing, assets, and projects into a single system, so a business doesn't need separate tools for each function. AXERP is also the foundation the rest of our platforms connect to.

**Key capabilities**
- **Accounting**: record transactions, manage cash flow, and run financial reports
- **Order management**: inventory, stock replenishment, sales orders, suppliers, and fulfilment
- **Manufacturing**: production cycles, material consumption, capacity planning, and subcontracting
- **Asset management**: track equipment and IT assets from purchase to disposal
- **Projects**: tasks, timesheets, and issues tracked against budget and profitability

**Tech stack:** Python · JavaScript · TypeScript · Frappe Framework · Frappe UI (Vue) · MariaDB · Docker

---

### 📈 AXIBROKER: AI Boutique Brokerage Platform

AXIBROKER helps boutique and independent brokerages cut back-office costs. It automates post-trade operations, including trade capture, settlement, custody reconciliation, and record-keeping, on a shared, permissioned, tamper-evident ledger. AI flags likely problems before they become costs. *AXIBROKER is in early development.*

**Key capabilities**
- **Order management**: order capture, validation, and a full trade-lifecycle state machine
- **Shared ledger**: a permissioned, tamper-evident settlement record on Hyperledger Fabric
- **Automated reconciliation**: position and cash reconciliation with break classification
- **AI insights**: volume and cash forecasting, settlement-fail prediction, and anomaly detection
- **Custodian connectivity**: industry-standard SWIFT ISO 15022 / 20022 settlement messaging

**Tech stack:** TypeScript · Node.js (Fastify) · React + Vite · Python (FastAPI) · Go · Hyperledger Fabric · Kafka-compatible messaging · PostgreSQL · Docker · AWS

---

### 🌳 Carbon AI: REDD+ Carbon Credit Estimation

Carbon AI is a Frappe app for planning and evaluating REDD+ forest carbon projects. Users define a project area on an interactive satellite map. The platform then estimates biomass, CO₂e, and forest-integrity indicators with machine-learning models trained on AWS SageMaker. It also includes experimental tools for tokenizing serialized carbon credits on the Cardano blockchain.

**Key capabilities**
- **Guided project setup**: capture project metadata and region details, then draw the project boundary on a satellite base map
- **Carbon estimation**: above-ground biomass, CO₂e, canopy height, NDVI, and deforestation indicators
- **ML pipeline**: models trained and served on AWS SageMaker
- **Project summary**: mapped area, results table, and a plain-English project explanation
- **Tokenization (experimental)**: mint serialized carbon credits as Cardano native assets, with ERP inventory tracking

**Tech stack:** Python · JavaScript · Frappe / AXERP · Leaflet · AWS SageMaker · Terraform · Cardano · Jupyter

---

### 🏛️ Carbon Onboarding: Government Onboarding Workflow

Carbon Onboarding is a Frappe app for AXERP that runs the government onboarding workflow for carbon projects on ERP sites. It handles project registration and approval from start to finish.

**Key capabilities**
- **Self-service registration**: a web portal for registering carbon projects
- **Government onboarding forms** with configurable project types
- **Approval workflows** for project registration and payment confirmation
- **Admin dashboard** and scheduled reporting

**Tech stack:** Python · JavaScript · HTML/CSS · Frappe / AXERP

---

### 🤖 Claude Assistant: AI Operations Assistant

Claude Assistant is our internal AI assistant built on Anthropic's Claude Code and the Model Context Protocol (MCP). It handles routine project-management work: scheduled briefings, task tracking, time logging, and calendar planning.

**Key capabilities**
- **Automated briefings**: morning, evening, and weekly reviews, generated by scheduled runs
- **Action items to tasks**: turns action items from email, chat, and meeting notes into project tasks, with de-duplication
- **Task housekeeping**: auto-closes completed tasks and triages the backlog
- **Time and calendar**: logs time and books focus blocks on the calendar
- **Integrations**: a library of MCP servers connecting productivity, messaging, storage, and project-management tools

**Tech stack:** Python · Shell · JavaScript · Claude Code · Model Context Protocol (FastMCP) · Docker · Terraform · AWS

---

<div align="center">

## Get in touch

🌐 **[axinagroup.com](https://axinagroup.com/)**

**Related companies:** [TGI Power](https://tgipower.com/) · [Durteq](https://www.durteq.com/) · [Aximedic](https://aximedic.com/)

<sub>© 2026 Axina Group Inc. All rights reserved.</sub>

</div>

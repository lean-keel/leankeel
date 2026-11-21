<div align="center">

# 🎮 Lean Keel

**Intelligent Building Tool for Enterprise Information Systems**

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)](https://vuejs.org/)
[![Spring AI](https://img.shields.io/badge/Spring%20AI-1.1-6DB33F?style=flat-square&logo=spring&logoColor=white)](https://spring.io/projects/spring-ai)
[![Flowable](https://img.shields.io/badge/Flowable-7.1-1B8FE0?style=flat-square&logo=flowable&logoColor=white)](https://www.flowable.com/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=flat-square)](LICENSE)

English | [简体中文](./README.md)

</div>

---

## 📖 Introduction

**Lean Keel** is an intelligent building tool for enterprise information systems, built on a front-end / back-end separated architecture. It integrates seven core capabilities: **RBAC Access Control**, **AI Conversation**, **Design Center**, **BPM Process Engine**, **Low-Code Model**, **Document Parsing**, and **Scheduled Tasks**. All back-end management capabilities are exposed to Large Language Models via the MCP tool protocol, so users can perform every management operation with natural language.

The system also provides **Business Dictionary Governance** (business categories / catalogs / models / elements / data elements + ontology lineage + business exploration) and **Master-Slave Read/Write Splitting**, supporting enterprise-grade data governance and high-performance data access.

The built-in **Design Center** offers EA five-view modeling, logical data models, detailed design diagrams, and design asset accumulation. Through landing mapping / model transformation / one-click alignment / drift detection / baseline control, it achieves **two-way integration between design-time and runtime**, supporting full-chain traceability from requirements to running systems.

### ✨ Key Features

<details open>
<summary><b>🤖 AI Capabilities</b></summary>

| Feature | Description |
|------|------|
| **AI-Native Architecture** | All back-end capabilities exposed to LLMs via MCP tools; seven Agents (Admin / Flow / Model / Reverse / Office / Schedule / Skill) work collaboratively |
| **Multimodal AI Chat** | Image understanding + file parsing + tool calling + streaming typewriter effect, compatible with any OpenAI API |
| **Expert Chat Room** | Multi-Agent multi-round sequential collaboration with automatic summary generation |
| **RAG Knowledge Base** | Document ingestion, automatic chunking, vector retrieval augmented generation; Simple / OpenAI Embedding supported |
| **AI Skill System** | Services / models / processes unified as discoverable, callable skills with Markdown description and reverse generation |
| **Playbook Persistence** | Successful call patterns saved semantically to the vector knowledge base and automatically retrieved for reuse |

</details>

<details open>
<summary><b>🔐 Security & Access Control</b></summary>

| Feature | Description |
|------|------|
| **Full RBAC** | User / role / department / employee / group / menu / button / data-level permissions with declarative annotation checks |
| **Multi-Tenancy** | Complete tenant data isolation with automatic tenant context propagation |
| **SSO** | Nine providers: Keycloak / GitHub / WeChat / WeCom / Azure AD / Okta / Google / DingTalk / Feishu |
| **Encryption** | HMAC signature + AES encryption + anti-replay + anti-tampering + XSS / SQL injection detection, 7 configurable switches |
| **Login Security** | Failure lockout + captcha + password complexity / history / expiration policies |
| **Enterprise Features** | Idempotency protection, notification center (in-app / email / Webhook), multi-timezone, AI cost control & quotas |
| **i18n** | Full Chinese / English bilingual support |

</details>

<details open>
<summary><b>🛠️ Low-Code & Data Governance</b></summary>

| Feature | Description |
|------|------|
| **Low-Code Engine** | Dynamic tables, dynamic CRUD, master-detail relations, versioning, database reverse engineering, business dictionary, field-level classification & encryption, view designer, service design, business rules |
| **Business Dictionary Governance** | Five-level system: categories / catalogs / models / elements / data elements with dual business-data traceability |
| **Ontology Lineage** | Complete lineage graph from business concepts to physical implementation: 6 node types + 5 relation edges |
| **Business Exploration** | Graph visualization + query plans (automatic multi-table JOIN SQL generation) |
| **Read/Write Splitting** | Service-layer dynamic routing, round-robin load balancing, slave cache dual mode (memory / Redis), automatic failover |

</details>

<details open>
<summary><b>🎨 Design Center</b></summary>

| Feature | Description |
|------|------|
| **EA Enterprise Architecture** | Business domain / capability / application / technology / security five-view objects and layered management, capability map + architecture alignment checks |
| **Unified Design Objects** | Domain / project tree + unified version management, 9 object relations (contains / implements / maps / depends etc.), annotation reviews, requirement traceability & change impact analysis |
| **Logical Data Modeling** | Logical models / attributes / ER diagrams / field-level lineage (FK / data element / physical column three-way traceability), one-click DDL export in 4 dialects (MySQL / PostgreSQL etc.) |
| **Design-Runtime Integration** | Design object ↔ runtime entity landing mapping (linked / landed / deviated); logical ↔ physical model two-way transformation; one-click landing of flowcharts to Flowable; business rules / interface refinement generate runtime rules & services |
| **One-Click Alignment & Drift Detection** | Five-view design objects landed as detailed design artifacts (domains / microservices / logical models / integration definitions); physical model vs. runtime table column auto-comparison generating incremental ALTER scripts with landing status write-back |
| **Baseline & Change Control** | Design baseline snapshots / version drift comparison / baseline restore / object rollback with field-level diffs; change orders integrated into Flowable multi-step approvals, baselines auto-fixed upon approval |
| **AI Design** | AI-generated logical models / interface definitions (auto-saved into design models), architecture compliance / naming / model consistency intelligent reviews |
| **Detailed Design Diagrams** | 8 diagram types: class / use case / component / deployment / state / activity / sequence / flow, auto-layout and persisted |
| **Governance & Topology** | Data asset map, end-to-end data flow lineage, integration relationship graph, deployment topology, security architecture topology |
| **Assets & Metrics** | Cross-project design asset reuse, design templates / standards, UI themes, technology roadmap, prompt templates, compliance auto-checks & design metric audits |

</details>

<details open>
<summary><b>⚙️ Process & Scheduling</b></summary>

| Feature | Description |
|------|------|
| **BPMN Process Design** | Visual process design based on Flowable 7.1 + bpmn-js, deeply integrated with low-code models |
| **Document Parsing** | Multi-format parsing: txt / md / json / csv / docx / xlsx / pptx / pdf / mpp / vsdx |
| **Scheduled Tasks** | Spring Scheduler / XXL-JOB dual frameworks, cron / fixed_rate / fixed_delay / one_shot schedule types |

</details>

<details open>
<summary><b>🚀 Engineering</b></summary>

| Feature | Description |
|------|------|
| **Fast Setup** | Out-of-the-box, runs without complex configuration |
| **Lightweight Deployment** | H2 embedded database, single JAR deployment, GraalVM Native Image / MySQL / PostgreSQL / Redis supported |

</details>

---

## 🌐 Online Trial

Try the full system online without installation:

| Item | Description |
|------|------|
| Trial URL | [https://leankeel.com](https://leankeel.com) |
| Demo Account | `admin` |
| Demo Password | `admin123` |

> 💡 Trial data is reset periodically. Do not store important business data in the trial environment.

---

## 🏗️ Architecture

| Layer | Tech Stack | Description |
|:----:|:------:|------|
| **Back End** | `Spring Boot 3` + `Java 21` | Enterprise Java application framework |
| **AI** | `Spring AI` + `MCP` | LLM integration & tool protocol |
| **Front End** | `Vue 3` + `Element Plus` | Progressive JavaScript framework |
| **Workflow** | `Flowable 7.1` | Business process engine |
| **Persistence** | `Spring Data JPA` | ORM / data access |
| **Database** | `H2` / `MySQL` / `PostgreSQL` | Relational databases |
| **Cache** | `Redis` (optional) | Distributed cache / session storage |

---

## 📁 Project Structure

```
leankeel/
├── leankeel-windows.zip.001  # Windows package (split part 1/2)
├── leankeel-windows.zip.002  # Windows package (split part 2/2)
├── leankeel-linux.zip.001    # Linux package (split part 1/2)
├── leankeel-linux.zip.002    # Linux package (split part 2/2)
├── application.yaml          # Configuration file (obtained after extraction)
├── LICENSE                   # License (Apache 2.0)
├── README.md                 # Project docs (Simplified Chinese)
├── README_EN.md              # Project docs (English)
```

---

## 🚀 Quick Start

### 1️⃣ Download and Extract the Package

> Due to upload size limits, both the Windows and Linux packages are split into 2 volumes (`.zip.001` / `.zip.002`). Download **all** volumes of the same platform into the same directory, then extract any one of them — all parts are merged automatically (you will get `leankeel.exe` or `leankeel` plus `application.yaml`).

### 2️⃣ Start the Service

- **Windows**: run the extracted `leankeel.exe`
- **Linux**: run the extracted `leankeel` (run `chmod +x leankeel` first to make it executable)

### 3️⃣ Access the System

| Item | Description |
|------|------|
| Local URL | [http://127.0.0.1:8080](http://127.0.0.1:8080) |
| Default Username | `admin` |
| Default Password | `admin123` |

---

## 🤖 AI Chat Configuration

After signing in, go to **AI Chat → Model Configuration**, select a model and set the API Key to drive all system modules via LLM conversation.

> 💡 You can also skip the LLM and operate each module manually through its menus.

### Recommended Model — DeepSeek

Great cost-performance. Register and apply for an API Key at [DeepSeek API Keys](https://platform.deepseek.com/api_keys).

---

## 📧 Support

For questions or suggestions, feel free to contact us:

- Email: [leankeel@163.com](mailto:leankeel@163.com)
- Website: [https://leankeel.com](https://leankeel.com)

---

<div align="center">

<sub>© 2025-2026 Lean Keel. All rights reserved.</sub>

</div>

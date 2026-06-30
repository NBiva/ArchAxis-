# 🏗️ ArchAxis: Smart Builds, Bold Leadership

> A comprehensive, role-based property development and construction management platform. ArchAxis enables transparent project creation, structured bidding, hierarchical team formation, live progress tracking, inventory oversight, and automated financial estimation.

---

## 📑 Table of Contents
1. [Overview](#-overview)
2. [Key Objectives](#-key-objectives)
3. [Motivation](#-motivation)
4. [Tech Stack](#-tech-stack)
5. [System Roles & Workflow](#-system-roles--workflow)
6. [Database Design Principles](#-database-design-principles)
7. [Core Features](#-core-features)
8. [Development Phases](#-development-phases)
9. [The Team](#-the-team)

---

## 🌍 Overview
ArchAxis is designed to mirror real-world construction site hierarchies. Clients, managers, engineers, subcontractors, supervisors, logistics teams, and site workers coordinate through structured, role-based workflows. The platform ensures completely transparent tracking of daily tasks, material usage, and financial expenditures from the initial sketch to the final brick.

## 🎯 Key Objectives
* **Dynamic Building Design:** Integrated estimation and automated tax calculations based on structural plans.
* **Structured Hierarchy:** Seamless workflow routing (Client → Manager → Contractor → Supervisor → Worker).
* **Comprehensive Project Lifecycle:** End-to-end support for project creation, vendor bidding, and daily progress tracking.
* **Intelligent Team Formation:** Build teams based on dynamic sorting of rank, peer ratings, and current availability.
* **Live Collaboration:** Real-time messaging and visual assignment trees to prevent miscommunication.
* **Data-Driven Insights:** Deep portfolio analytics, performance metrics, and inventory/warehouse reporting.

## 💡 Motivation
Modern construction projects frequently suffer from fragmented communication, manual tracking errors, and unclear accountability across different contracting layers. ArchAxis was built to solve this by centralizing planning, role assignment, progress tracking, material procurement, and financials into a single, unified, and highly auditable platform.

## 💻 Tech Stack

<p align="left">
  <a href="https://php.net" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="40" height="40"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="40" height="40"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/></a>&nbsp;&nbsp;
  <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40"/></a>&nbsp;&nbsp;
</p>

* **Server Environment:** XAMPP
* **Visualization & Diagrams:** Chart.js, draw.io

## 👥 System Roles & Workflow
ArchAxis features a robust access-control system tailored to specific construction responsibilities:

* 👑 **Admin:** Global control panel and system oversight.
* 🏢 **Client:** Designs the building, creates project bids, and views automated budget forecasts.
* 📊 **Project Manager:** Monitors overall progress, assigns high-level roles, and confirms material requests.
* 🏗️ **Sub-Contractor:** Authorizes on-site supervisors and updates macro-task statuses.
* 👷 **Supervisor:** Manages daily worker allocation and logs task completions.
* 🚚 **Logistics:** Enrolls suppliers, manages warehouse inventory, and processes purchase orders.
* 📋 **Site Manager:** Allocates specific daily tasks and pushes material requests up the chain.
* 📐 **Site Engineer:** Confirms structural designs and finalizes technical estimations.

## 🗄️ Database Design Principles
* **Normalization:** Optimized up to 3NF to eliminate data redundancy.
* **Referential Integrity:** Strict enforcement of foreign keys across all relational tables.
* **Audit Trails:** `created_at` and `updated_at` timestamps on all mutable entities for complete tracking.
* **Complex Queries:** Heavy utilization of Joins, aggregates, and advanced filters based on role/project scopes.
* **Automated Triggers:** Database-level automation for status updates, system logging, and inventory counters.

## ✨ Core Features
- [x] **Sketch-to-Estimate:** Building designer tool with engineer export capabilities.
- [x] **Financial Engine:** Automated cost and tax estimation with pre-execution budget forecasting.
- [x] **Resource Management:** Material and warehouse tracking (live stock, usage history, procurement).
- [x] **Communication Hub:** Role-based, real-time messaging integrated into task views.
- [x] **Approval Workflows:** Multi-tier material request and approval chains.
- [x] **HR & Operations:** Live attendance, shift tracking, and task status logging.
- [x] **Analytics:** Financial summaries per project and supplier performance insights.

## 🚀 Development Phases

| Phase | Focus Area | Key Deliverables |
| :---: | :--- | :--- |
| **1** | **Foundation** | Auth (Login/Signup), Role models, DB integration & schema setup |
| **2** | **Dashboards** | Custom role views (Client, Manager, Engineer, etc.), Task allocation |
| **3** | **Operations** | Shift tracking, Attendance, Material workflows, Incident logs |
| **4** | **Intelligence** | Financial reports, Analytics, Chart.js graphs, Supplier insights |
| **5** | **Polish** | High-contrast dashboard styling, Modern UI aesthetics, Testing, Final Deployment |

## 📝 Summary
ArchAxis unifies multi-role construction operations into a cohesive digital ecosystem. By enabling structured assignment chains, strict financial transparency, material accountability, and live collaboration, it drastically reduces site friction and improves overall delivery confidence for all stakeholders involved.

---

### 👨‍💻 Group ArchAxis
*Developed with logic and innovation by:*
* **Nusrat Alam Biva**
* **Ashfakul Ahmed Pial**
* **Rakib Rahyan**
* **Aysha Samira Sami**

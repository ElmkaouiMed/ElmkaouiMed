# Topography Office Dashboard — Case Study

> **Live Demo:** [hmtop.elmkaoui.com/dashboard](https://hmtop.elmkaoui.com/dashboard)
>
> Demo access: `admin@topography.local` / `admin1234`

---

## Overview

A complete business management dashboard built for a Moroccan topography (surveying) office. The platform centralizes daily operations — client management, project tracking, document handling, invoicing, and team coordination — replacing a fragmented workflow of Excel sheets, paper folders, and WhatsApp messages.

![Dashboard Overview — key metrics, pipeline, and invoicing summary](assets/dashboard-overview.jpg)

---

## The Problem

Topography offices typically manage their workflow using a combination of disconnected tools:

- **Excel files** for project and client tracking
- **Paper documents** and physical folders for contracts and permits
- **WhatsApp messages** for team communication and approvals
- **Email** for client exchanges and invoice sending

This leads to:
- Lost or duplicate information
- No centralized view of project status
- Delayed invoice tracking and payment follow-up
- Difficulty onboarding new team members
- No clear audit trail

The goal was to replace this chaos with a **single, private web application** that any team member can use from the office or on-site.

---

## Solution

A role-based internal dashboard where the office can:

- Track **clients** and their contact details, documents, and project history
- Manage **projects** through their lifecycle (draft → sent → approved → completed)
- Log and organize **documents/correspondence** (courriers) by type and status
- Generate and track **invoices and payments** with a clear overview of outstanding amounts
- Control **user access** with role-based permissions
- View a **dashboard** with real-time KPIs, pipeline status, and weekly summaries

### Screenshots

| Clients Management | Correspondence Tracking |
|---|---|
| ![Client management interface with search and contact list](assets/dashboard-clients.jpg) | ![Document/correspondence tracking with filters and status](assets/dashboard-courriers.jpg) |

*Left: Client management with global search and contact list. Right: Correspondence (Courriers) module with filtering by status, type, and project.*

---

## Key Features

### 📋 Client Management
- Centralized contact database with company info, emails, phone numbers, and TVA
- Quick-search across all client fields
- Associated documents and project history per client
- Add, edit, and organize client records

### 📐 Project Lifecycle
- Pipeline view: Draft → Pending → Sent → Approved → Completed
- Assign projects to clients with reference numbers
- Track project status at a glance from the dashboard
- Filter and search across all active projects

### 📨 Correspondence Tracking (Courriers)
- Log all incoming and outgoing mail/documents
- Filter by status, type, and associated project
- Search by recipient or reference number
- Complete audit trail for all correspondence

### 💰 Invoicing & Payments
- Create invoices linked to projects
- Dashboard shows total invoiced, paid, and outstanding amounts
- Weekly and monthly invoicing charts
- Track payment status per invoice

### 👥 User & Role Management
- Secure authentication with email/password
- Role-based access control (admin, manager, viewer)
- Each user sees only what they need

### 📊 Dashboard & KPIs
- Real-time operational pipeline overview
- Invoicing summary with charts (weekly/monthly)
- Weekly summary: new quotes, projects started
- Quick access to recent activity

---

## Tech Stack

| Technology | Purpose |
|---|---|
| **Next.js** | React framework for full-stack rendering |
| **React.js** | UI component architecture |
| **TypeScript** | Type safety and code quality |
| **Tailwind CSS** | Responsive, utility-first styling |
| **Database** | Relational database for business data |
| **Auth** | Secure authentication with session management |
| **VPS** | Production deployment on virtual private server |

---

## My Role

I owned the full development lifecycle:

1. **Requirements gathering** — understood the office workflow, pain points, and priorities
2. **Data modeling** — designed the database schema for clients, projects, documents, invoices, users
3. **UI/UX design** — structured the dashboard layout, navigation, and data presentation
4. **Frontend & backend** — implemented all features end-to-end
5. **Authentication** — built a secure login and role-based access system
6. **Deployment** — configured and deployed on a VPS with production-ready setup
7. **Maintenance** — ongoing improvements based on real user feedback

---

## Impact

- ✅ **Single source of truth** — all office data in one place
- ✅ **Real-time visibility** — dashboard shows pipeline and financial status instantly
- ✅ **Reduced admin overhead** — no more manual Excel updates or paper chasing
- ✅ **Professional client management** — faster responses, better organized records
- ✅ **Scalable foundation** — ready for additional modules (reporting, analytics, etc.)

---

## What This Demonstrates

This project goes beyond static websites or landing pages. It shows:

- **SaaS-style architecture** with authentication, roles, and data relationships
- **Full-stack capability** — from database design to UI to deployment
- **Business domain understanding** — building software that solves real operational problems
- **Production delivery** — deployed and used by a real business

---

## Relevant For

Clients and teams looking for:

- Admin panels & internal dashboards
- SaaS MVPs & CRM systems
- Document & project management platforms
- Invoice & payment tracking tools
- Custom business web applications

---

## Contact

- **Portfolio:** [elmkaoui.com](https://elmkaoui.com)
- **GitHub:** [github.com/ElmkaouiMed](https://github.com/ElmkaouiMed)
- **Email:** [medelmkaoui@gmail.com](mailto:medelmkaoui@gmail.com)

# 👋 Hi, I'm Thiago Oliveira

### Software Developer · Software Engineering Student

I build practical software solutions across backend systems, web and mobile applications, databases, and process automation.

I'm a Software Engineering student at **Centro Universitário Internacional UNINTER**, focused on writing maintainable code, designing reliable APIs, and applying software engineering practices to real-world problems.

🌍 **Open to:** Remote opportunities worldwide, internships, and junior software development roles.

🔗 [GitHub](https://github.com/Thiago-tods) · [LinkedIn](https://www.linkedin.com/in/thiago-oliveira-91a4851b2/)

---

## 🧰 Technology Stack

A quick overview of the tools and technologies I use in my projects.

| Area | Technologies |
|---|---|
| **Languages** | 🐍 Python · #️⃣ C# · 🟦 TypeScript · 🟨 JavaScript · 🐘 PHP · 🎯 Dart · 🗃️ SQL |
| **Frontend** | ⚛️ React · ▲ Next.js · 💚 Vue · ⚡ Vite · 🎨 Tailwind CSS |
| **Mobile** | 💙 Flutter · 🎯 Dart · 📱 Riverpod |
| **Backend** | 🟢 Node.js · 🪺 NestJS · 🚀 Express · 🔷 .NET / ASP.NET Core · 🐘 Laravel · ⚡ FastAPI |
| **Databases & ORM** | 🐘 PostgreSQL · 🗄️ SQLite · ☁️ Supabase · Prisma · Entity Framework Core · SQLAlchemy |
| **Testing** | 🧪 Jest · Vitest · Pytest · PHPUnit · xUnit · Supertest · Playwright · Testing Library |
| **Tools & DevOps** | 🐙 Git · GitHub Actions · 🐳 Docker · Docker Compose · Nginx · CI/CD |

---

## 🚀 Featured Projects

Selected projects demonstrating application development, backend architecture, database design, automation, and software quality practices.

### 📦 [StockWise](https://github.com/Thiago-tods/StockWise)
**Inventory & Business Management**

A web application for small businesses to manage products, suppliers, customers, purchases, sales, returns, and inventory operations.

- Inventory movements with transactional updates and audit history.
- Purchase workflows, partial receiving, sales, cancellations, and returns.
- Dashboard and reports with CSV, XLSX, and PDF exports.
- Session authentication, role-based access, and CSRF protection.

**Stack:** React 19 · TypeScript · Vite · Node.js · Express 5 · PostgreSQL · Prisma · Vitest · Supertest

### 🎫 [HelpDeskPro](https://github.com/Thiago-tods/HelpDeskPro)
**IT Support Ticket Management**

A full-stack support platform with dedicated workflows for requesters, agents, and administrators.

- Ticket creation, assignment, tracking, and resolution.
- Kanban board, conversations, internal notes, and activity history.
- Backend-calculated SLAs, reports, and audit logging.
- Real-time updates with SignalR and role-based permissions.

**Stack:** C# · .NET 10 · ASP.NET Core · Entity Framework Core · PostgreSQL · React · TypeScript · SignalR · xUnit · Playwright

### 🛠️ [ServiceCheck](https://github.com/Thiago-tods/ServiceCheck)
**Field Service Management**

A mobile-first application for technicians and field teams, designed for offline work and later synchronization.

- Work orders, scheduling, customers, teams, and services.
- Checklists, photos, notes, and on-screen signatures.
- Offline synchronization with idempotent operations and conflict handling.
- PDF reports, notifications, and Portuguese/English interfaces.

**Stack:** Flutter · Dart · Riverpod · Drift / SQLite · NestJS · TypeScript · PostgreSQL · Prisma · Jest

### 📅 [AgendaPro](https://github.com/Thiago-tods/agendapro)
**Appointment & Service Management**

A multi-tenant scheduling platform for clinics, barbershops, studios, and other service businesses.

- Daily, weekly, and monthly calendar views.
- Appointment, customer, professional, and service management.
- Availability rules and scheduling conflict prevention.
- Operational dashboard and tenant data isolation.

**Stack:** PHP · Laravel · PostgreSQL · Vue 3 · TypeScript · Vite · Pinia · Tailwind CSS · PHPUnit · Vitest

### 🍽️ [MenuQR](https://github.com/Thiago-tods/MenuQR)
**Digital Menu & QR Code Ordering**

A restaurant application where customers browse a digital menu, place orders, and follow order progress.

- QR-code access to menus with categories, search, and add-ons.
- Cart and checkout for takeaway or dine-in orders.
- Admin dashboard for products, orders, tables, and QR codes.
- Order status tracking and database access policies.

**Stack:** Next.js · React · TypeScript · Tailwind CSS · Supabase · PostgreSQL · Zod · Vitest · Playwright

### 💰 [FinPlan](https://github.com/Thiago-tods/FinPlan)
**Personal Finance Management**

A mobile financial management application supported by a backend API and relational database.

- JWT authentication and refresh token rotation.
- Bank account management and categorized income/expense tracking.
- Bill management and payment tracking.
- User data isolation and protection against concurrent updates.

**Stack:** Flutter · Dart · NestJS · TypeScript · PostgreSQL · Prisma · Vitest · Supertest

### 📋 [QuoteMaster](https://github.com/Thiago-tods/QuoteMaster)
**Business Quotation Management**

A web application for managing customers, products, services, quotations, and PDF documents.

- Customer and product catalog management.
- Quotations with server-side financial calculations and status workflows.
- A4 PDF generation with items, terms, and company branding.
- Local persistence, layered architecture, and database migrations.

**Stack:** C# · .NET 10 · ASP.NET Core MVC · Entity Framework Core · SQLite · QuestPDF

### 🤖 [Nexa AI](https://github.com/Thiago-tods/Nexa-AI)
**Local AI Business Agent Platform**

A web platform of AI-powered business agents that run locally using Ollama, without paid AI APIs or sending business data to the cloud. The agent answers questions from a company knowledge base, manages leads and support requests, and requires human approval for sensitive actions.

- Streaming agent chat with intent classification, tool execution, and answers grounded in cited sources.
- Local RAG pipeline for PDF, TXT, Markdown, and CSV documents, using PostgreSQL with pgvector.
- CRM with leads, Kanban pipeline, activity history, notes, and support requests.
- Human approval workflow for sensitive actions, with audit trails and idempotent execution.
- Security controls including RBAC, rotating refresh tokens, rate limits, and prompt-injection defenses.

**Stack:** Python 3.12 · FastAPI · LangGraph · Ollama · PostgreSQL 17 · pgvector · React 19 · TypeScript · Vite · Tailwind CSS · SQLAlchemy · Pytest · Vitest · Playwright

### 📡 [PulseOps](https://github.com/Thiago-tods/PulseOps)
**Website & API Monitoring / Incident Management**

A SaaS platform for monitoring website and API availability, managing incidents, and notifying teams, built as a zero-infrastructure-cost portfolio project.

- HTTP monitors (GET/HEAD) with configurable intervals, timeouts, expected status codes, and failure thresholds.
- Automatic incident creation and resolution, with a 30-day history.
- Encrypted webhook destinations and HMAC-signed notifications compatible with Slack and Discord.
- Public status pages showing 30-day availability without exposing internal URLs or data.
- Multi-tenant accounts and organizations, session management, refresh-token rotation, and audit logging.
- SSRF protections for requests to user-supplied URLs.

**Stack:** React 19 · TypeScript · Vite · NestJS 11 · PostgreSQL · Prisma 7 · Zod · Cloudflare Pages · GitHub Actions · Render · Neon

**Live demo:** [pulseops-cq4.pages.dev](https://pulseops-cq4.pages.dev/)

### 🔁 [RelayForge](https://github.com/Thiago-tods/relayforge)
**Webhook Infrastructure & Event Delivery**

A webhook infrastructure platform for receiving, persisting, processing, delivering, retrying, and monitoring webhook events, built around a modular monolith with independent worker processes.

- HMAC-SHA256 signature verification, timestamp validation, and endpoint-scoped idempotency.
- Transactional outbox pattern with PostgreSQL and durable messaging through NATS JetStream.
- Independent API, outbox publisher, and delivery worker processes.
- Multi-tenant organizations with role-based access control, secure sessions, and append-only audit events.
- Delivery retries and monitoring; delivery is at-least-once.

**Stack:** Go · PostgreSQL 17 · Redis · NATS JetStream · React · TypeScript · Vite · Docker Compose

### 🏝️ [Dynamic Island for Windows](https://github.com/Thiago-tods/DynamicIsland)
**Native Windows Desktop Utility**

A floating, Apple-inspired Dynamic Island for Windows that brings useful desktop information and quick controls into a compact interface.

- Clock and stopwatch, media controls, and system monitoring for CPU, RAM, and supported NVIDIA GPUs.
- Windows toast notifications with configurable privacy modes.
- Weather forecasts powered by Open-Meteo and download progress tracking.
- Customizable appearance, global shortcuts, system tray integration, and multi-monitor positioning.
- Native WPF application with no Electron, embedded web view, or telemetry.

**Stack:** C# 13 · .NET 10 · WPF · CommunityToolkit.Mvvm · Windows APIs · xUnit · Inno Setup

### 📊 [Sales Reports Automation](https://github.com/Thiago-tods/projeto-analise-planilhas-py)
**Business Reporting & Process Automation**

A Python system for importing, validating, and processing commercial data, querying PostgreSQL, and generating management reports.

- Excel and CSV import and validation.
- Store performance indicators, spreadsheets, and rankings.
- Personalized email generation and automated report delivery.
- Logging, error handling, simulation mode, and automated tests.

**Stack:** Python · Pandas · openpyxl · PostgreSQL · SQLAlchemy · psycopg · Pytest

---

## 🎓 Education

**Bachelor's Degree in Software Engineering**  
Centro Universitário Internacional UNINTER  
2026–2030 · In progress

## 🌎 Languages

- 🇧🇷 **Portuguese:** Native
- 🇬🇧 **English:** Advanced

## 🎯 What I'm Working Toward

I'm looking to grow as a software developer, contribute to engineering teams, and build reliable solutions that address real business needs.

My main interests are backend and full-stack development, REST API design, database architecture, web and mobile applications, software testing, and process automation.

---

## 🤝 Let's Connect

If you're interested in my work or would like to discuss a software development opportunity, feel free to reach out.

- 💻 [GitHub — Thiago-tods](https://github.com/Thiago-tods)
- 💼 [LinkedIn — Thiago Oliveira](https://www.linkedin.com/in/thiago-oliveira-91a4851b2/)

<p align="center">
  <i>Building, learning, and improving one project at a time. 🚀</i>
</p>

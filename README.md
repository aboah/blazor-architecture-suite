# Blazor Architecture Suite

> A production-ready, modular enterprise architecture blueprint built with **.NET 10+** and **Blazor Server**, featuring an advanced IT Support Ticketing Module, real-time SignalR state management, and enterprise-grade UI components.

---

## 🚀 Key Architectural Highlights

- **Server-Side Interactivity (.NET 10+):** Optimized Blazor Server architecture leveraging SignalR circuits with memory-efficient state management.
- **Enterprise Security & Architecture:** Policy-based resource authorization (`[Authorize(Policy = "TicketOwnerOrStaff")]`), strict tenant isolation, UML-driven design, and robust auditability.
- **Microservices & Cross-Platform DevOps:** Containerized services built using .NET Core and Docker, fully optimized for multi-environment deployment across Linux (Ubuntu), macOS, and Windows.
- **Resilient Data Pipelines:** High-performance database administration and optimized data access layers utilizing custom indexing, stored procedures, and triggers.

---

## 🧩 Flagship Module: Support Ticketing System

The repository features a fully specified enterprise ticketing module modeled after high-availability infrastructure:
- **Triage & Filtering:** Dynamic status buckets (Open, In Progress, On Hold, Closed) with live count badges and advanced age-filtering.
- **Threaded Communication:** Secure message rendering supporting multi-line technical logs and rich text inputs while maintaining strict XSS sanitization (`Ganss.Xss`).
- **Workflow Automation:** Automated ticket ID generation, role-based badges (Staff vs. User), and secure file attachment handling.

---

## 🛠️ Comprehensive Tech Stack & Ecosystem

### 💻 Backend, Architecture & Cloud
- **Core Frameworks:** .NET 10+, C# (OOP/Structured Design), ASP.NET Core MVC, Blazor Server & WebAssembly
- **Microservices & DevOps:** Docker Containers, Linux (Ubuntu) & macOS deployment, RESTful APIs, FastAPI
- **Embedded Systems & Mobile:** IoT with Raspberry Pi (Microcontrollers), Cross-Platform Mobile Development (.NET MAUI)

### 🗄️ Database Engineering & Administration
- **Relational & Enterprise:** Microsoft SQL Server (Advanced Stored Procedures, Triggers, UDFs), PostgreSQL, MySQL, SQLite
- **NoSQL & Embedded:** LiteDB, DuckDB, MotherDuck, Google BigQuery

### 📊 Data Analytics, BI & Statistical Modeling
- **Programming & Analysis:** Python (Pandas, Matplotlib, Seaborn, OOP), R, SPSS, Stata 11.0
- **Visualization & Reporting:** Power BI, Power Pivot, Crystal Reports, Google Looker Studio
- **Reactive Workflows:** Marimo (Reactive Python Notebooks)

### 🌐 Frontend & Enterprise Tooling
- **Web Technologies:** HTML5, CSS3, JavaScript, jQuery, Bootstrap 5
- **Legacy & Office Integration:** VBA for MS Excel & MS Access, Microsoft SharePoint, Microsoft Teams

---

## 📂 Project Structure

- `src/Core/` — Domain entities, business logic, UML-aligned models, and shared DTOs.
- `src/Infrastructure/` — Database contexts, optimized SQL stored procedures, repositories, and workers.
- `src/Web/` — Blazor Server application, interactive razor components, and DI configurations.
- `docs/` — System workflow diagrams, functional, and technical specifications.

---
*Architected and maintained as a showcase of clean code, full-stack scalability, advanced data engineering workflows, and robust enterprise system design.*
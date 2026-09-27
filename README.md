# Blazor Architecture Suite

> A production-ready, modular enterprise architecture blueprint built with **.NET 10+** and **Blazor Server**, featuring an advanced IT Support Ticketing Module, real-time SignalR state management, and enterprise-grade UI components.

---

## 🚀 Key Architectural Highlights

- **Server-Side Interactivity (.NET 10+):** Optimized Blazor Server architecture leveraging SignalR circuits with memory-efficient state management.
- **Enterprise UI Integration:** Integrated with **Syncfusion Blazor** components (including advanced Rich Text Editors and data grids) under a verified Community License.
- **Robust Security & Authorization:** Policy-based resource authorization (`[Authorize(Policy = "TicketOwnerOrStaff")]`) ensuring strict tenant and row-level data isolation.
- **Auditability & Logging:** Comprehensive system audit trails tracking state changes, reassignments, and role-based actions.
- **Resilient Data Pipelines:** High-performance EF Core data access utilizing custom indexing strategies for sub-second query execution at scale.

---

## 🧩 Flagship Module: Support Ticketing System

The repository features a fully specified enterprise ticketing module modeled after high-availability hosting infrastructure:
- **Triage & Filtering:** Dynamic status buckets (Open, In Progress, On Hold, Closed) with live count badges and advanced age-filtering.
- **Threaded Communication:** Secure message rendering supporting multi-line technical logs and rich text inputs while maintaining strict XSS sanitization (`Ganss.Xss`).
- **Workflow Automation:** Automated ticket ID generation (`{QueuePrefix}-{Dept}-{Sequence}`), role-based badges (Staff vs. User), and file attachment handling.

---

## 🛠️ Tech Stack & Ecosystem

- **Core Framework & Backend:** .NET 10+, C#, Blazor Server, Entity Framework Core (SQL / PostgreSQL / SQLite)
- **Enterprise UI & Security:** Radzen Blazor Component Suite, HTML Sanitization (`Ganss.Xss`), Role-Based Access Control (RBAC)
- **Data Engineering & Analytics:** DuckDB, MotherDuck, Databricks, Google BigQuery, Pandas, Marimo (Reactive Python Notebooks), Power BI, Power Pivot
- **Enterprise Collaboration:** Microsoft SharePoint, Microsoft Teams

---

## 📂 Project Structure

- `src/Core/` — Domain entities, business logic, and shared DTOs.
- `src/Infrastructure/` — Database context, repositories, and background notification workers.
- `src/Web/` — Blazor Server application, Razor components, pages, and DI configuration.
- `docs/` — Functional and technical specifications.

---
*Architected and maintained as a showcase of clean code, scalability, modern enterprise .NET design patterns, and advanced data engineering workflows.*
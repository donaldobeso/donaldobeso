# Hi, I'm Donald Obeso 👋

**IT Student & Full-Stack Developer** based in Cebu, Philippines. I specialize in architecting complex, role-driven web systems, database integrity models, and enterprise operations platforms using modern full-stack technologies assisted with AI agents.

---

### 🛠️ Technical Arsenal

#### Languages & Core Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

#### Backend, Cloud & Database
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Deno](https://img.shields.io/badge/Deno_Edge_Functions-000000?style=for-the-badge&logo=deno&logoColor=white)

#### Testing, CI/CD & Tooling
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

#### Also Experienced With
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

---

### 🏆 Featured Project: Capstone Project

## **KleenTech Auto Detailing — Multi-Branch Management Platform**
*A full-stack enterprise operations platform engineered for a 4-branch automotive detailing network across Cebu.

#### 🚗 Vehicle-Tier Dynamic Pricing & Quota Engine
* **5-Tier Vehicle Model:** Dynamic pricing and reservation fees tailored across 5 vehicle classes: **Sedan**, **SUV**, **Pickup**, **Van**, and **Motorcycle**.
* **Multi-Service Bundling:** Allows customers to bundle up to 4 specialized detailing services (Ceramic Coating, PPF, Detailing, Leather Reupholstery, Rustproofing, Window Tint) in a single visit with estimated inspection totals.
* **Recurring Membership Quotas:** Subscription plans with automated monthly service quota allocations and online redemption.

#### 👥 5-Role Operational Ecosystem
* **Customer Portal:** Digital vehicle garage management, 5-step booking wizard, live appointment state tracking, self-service rescheduling, and penalty pardon appeal submissions.
  
* **STAFF PORTAL**
  
* **Receptionist:** Walk-in customer and vehicle registration, physical service bay assignment, over-the-counter POS cashiering with downpayment balance settlements, and digital thermal receipts.
* **Technician:** Mobile-optimized floor queue with vehicle details, interactive package QA step checklists, customer push status triggers, and shift adjustment requests.
* **Branch Manager:** Technician roster and weekly routine scheduling, physical bay capacity monitoring, localized service price override requests, local-branch staff provisioning, and customer pardon reviews.
* **Super Admin:** Global multi-branch revenue intelligence, master service catalog governance, price request approvals, cross-branch staff provisioning, and immutable audit trails.

#### 🛡️ Database Architecture & Engineering Quality
* **PostgreSQL 17 Row-Level Security (RLS):** Multi-tenant branch isolation using cached statement-level authorization (`(SELECT auth.uid())`) and atomic `SECURITY DEFINER` RPCs.
* **Privilege Guard Triggers:** `BEFORE UPDATE` database triggers preventing unauthorized client modification of roles, branch assignments, and billing states.
* **Payment Security:** Serverless Deno Edge Functions handling PayMongo checkouts with cryptographic HMAC-SHA256 webhook signature verification and idempotency locks.
* **Automated CI/CD Quality Gate:** GitHub Actions pipeline executing static typechecking, Vite production builds, ESLint validation, and Vitest unit testing suites on every push.

> 🔒 *Repository is private under client confidentiality. System design walkthroughs and code samples are available during technical interviews.*
---

### 📂 Other Projects

* **StudySync:** Collaborative student productivity and academic task tracking mobile app built with C#.
* **Pet Adoption Management System:** Complete desktop workflow management application built with Windows Forms and Visual Basic .NET.

---

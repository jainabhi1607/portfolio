# Abhishek Jain — Project Portfolio

### Senior Full-Stack Developer | 10+ Years of Experience

I build scalable, production-ready web applications for businesses across healthcare, finance, and field services. Below are some of my recent projects built with modern tech stacks.

---

## What I Can Build For You

| Service | Description |
|---------|-------------|
| Custom Admin Dashboards & CRM Systems | Tailored business tools with role-based access and real-time data |
| SaaS Platforms with Multi-Tenant Architecture | Scalable apps serving multiple organizations with data isolation |
| Healthcare & Finance Management Systems | HIPAA-aware, secure platforms for sensitive industries |
| Mobile Apps + Web Apps | Cross-platform solutions using React Native + Next.js |
| AI-Powered Features | Chatbots, smart search, and AI integrations using Claude/OpenAI APIs |
| Legacy Modernization | Migrate PHP/WordPress apps to modern React/Next.js stacks |

---

## Projects

### 1. JJDH — Hospital Management System

> A comprehensive hospital/clinic admin dashboard for managing patients, doctors, appointments, prescriptions, invoices, and medical records.

🔗 **Live Demo:** [jjdh.vercel.app](https://jjdh.vercel.app/)

**Key Features:**
- Patient management with medical records, visit history, and medical image storage
- Doctor and staff management with role-based access (Super Admin, Admin, Doctor, Receptionist, Nurse)
- Appointment scheduling, prescription tracking, and medicine database
- Invoice generation and financial records
- Master data management (diagnoses, investigations, advice, medicines)
- Spreadsheet export for reporting

**Tech Stack:**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<details>
<summary><strong>Architecture</strong></summary>

```
Frontend:    Next.js 16 (App Router) with Server-Side Rendering
Backend:     Next.js API Routes with JWT Authentication
Database:    MongoDB Atlas with Mongoose ODM (embedded subdocuments)
Auth:        NextAuth v4 with credentials/JWT (5 user roles)
UI:          Tailwind CSS + shadcn/ui (Radix UI components)
Deployment:  Vercel with CI/CD
```
</details>

<details>
<summary><strong>Screenshots (click to expand)</strong></summary>
<br>

#### Secure Login — Role-based authentication for authorized hospital personnel
![Login](screenshots/jjdh/jjdh-Login.png)

#### Dashboard — Real-time overview of patients, appointments, and hospital activity
![Dashboard](screenshots/jjdh/jjdh-Dashboard.png)

#### Patient Management — Comprehensive list with search, filters, and quick actions
![Patients](screenshots/jjdh/Patient.png)

#### Patient Detail — Complete medical history, visit records, and documents
![Patient Detail](screenshots/jjdh/Patient-detail.png)

#### Appointments — Scheduling and calendar view for doctor-patient appointments
![Appointments](screenshots/jjdh/Appointment.png)

#### Invoice Generation — Create and manage billing with itemized details
![Invoice](screenshots/jjdh/Add-Invoice.png)

</details>

---

### 2. LoanEase — Commercial Loan Referral Platform

> A multi-tenant loan referral management platform connecting referrers with commercial loan opportunities. Includes a web dashboard and a React Native mobile app.

🔗 **Live Demo:** [loanease-app.vercel.app](https://loanease-app.vercel.app/)

**Key Features:**
- Dual-access portals: Admin dashboard and Referrer dashboard
- Loan opportunity and application workflow management
- ABN/ABR validation for Australian business verification
- 2FA authentication, audit logging, and IP tracking
- Email notifications via Postmark
- Rich text editing for notes and communications
- PDF document generation for reports
- React Native mobile app (iOS & Android) for on-the-go access

**Tech Stack:**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<details>
<summary><strong>Architecture</strong></summary>

```
Frontend:    Next.js 15 (App Router) + React Native (Expo SDK 51)
Backend:     Next.js API Routes with JWT + bcrypt Authentication
Database:    MongoDB with Mongoose ODM
Services:    Postmark (email), Mapbox (location), ABN/ABR (verification)
Auth:        2FA + JWT with audit logging and IP tracking
Validation:  React Hook Form + Zod
Documents:   jsPDF + React PDF for report generation
Deployment:  Vercel (web) + Expo (mobile)
```
</details>

<details>
<summary><strong>Screenshots (click to expand)</strong></summary>
<br>

#### Login — Secure authentication with session management
![Login](screenshots/LoanEase/Login.png)

#### Admin Dashboard — Overview of loan applications, referrers, and pipeline status
![Dashboard](screenshots/LoanEase/LoanEase-Dashboard.png)

#### Applications — Track and manage commercial loan applications
![Applications](screenshots/LoanEase/Application.png)

#### Application Detail — Full application view with status, documents, and history
![Application Detail](screenshots/LoanEase/Application-Detail.png)

#### Referrer Dashboard — Dedicated portal for referrers to manage their pipeline
![Referrer Dashboard](screenshots/LoanEase/Referrer-Dashboard.png)

</details>

---

### 3. Total Spray Care (TSC) — Field Service Management

> An admin dashboard for spray booth maintenance and pest/spray care businesses to manage clients, sites, equipment, job cards, support tickets, and technicians.

🔗 **Live Demo:** [total-spray.vercel.app](https://total-spray.vercel.app/)

**Key Features:**
- Client and site management with multi-level organization
- Job card creation with technician assignment, checklists, and time tracking
- Equipment tracking with maintenance history, QR codes, and inspection checklists
- Support ticket system with activity logging
- Role-based access control across 5 user roles (Super Admin, Admin, Manager, Client User, Client Admin)
- Interactive charts and data visualization with Recharts
- PDF export and QR code generation for equipment

**Tech Stack:**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth_5-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square&logo=chart.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<details>
<summary><strong>Architecture</strong></summary>

```
Frontend:    Next.js 16 (App Router) with Server Components
Backend:     Next.js API Routes with NextAuth 5 (JWT + credentials)
Database:    MongoDB Atlas with Mongoose 9 ODM (59 models)
Auth:        NextAuth 5 beta with 5 role-based access levels
UI:          Tailwind CSS 4 + Radix UI (shadcn) + Recharts
Utilities:   jsPDF (export), QRCode (equipment tags), crypto-js
Deployment:  Vercel with CI/CD
```
</details>

<details>
<summary><strong>Screenshots (click to expand)</strong></summary>
<br>

#### Login — Secure access for admins, managers, and client users
![Login](screenshots/TSC/Login.png)

#### Dashboard — Business overview with charts, job stats, and activity feed
![Dashboard](screenshots/TSC/Dashboard.png)

#### Client Detail — Complete client profile with sites, contacts, and history
![Clients](screenshots/TSC/Client-detail.png)

#### Job Cards — Manage work orders with status tracking and technician assignment
![Job Cards](screenshots/TSC/Job-Cards.png)

#### Job Card Detail — Full job view with checklists, time logs, and activity
![Job Card Detail](screenshots/TSC/Job-Card-detail.png)

#### Checklist Templates — Reusable inspection templates for field operations
![Checklist Templates](screenshots/TSC/Checklist-Templates.png)

#### Support Tickets — Track and resolve client issues with priority management
![Support Tickets](screenshots/TSC/Support-Tickets.png)

#### Ticket Detail — Full ticket view with conversation thread and status updates
![Support Ticket Detail](screenshots/TSC/Support-Ticket-Detail.png)

</details>

---

### 4. Clue Finance — Loan Management Platform

> A multi-tenant commercial loan referral platform with comprehensive security, workflow management, and business verification capabilities.

🔗 **Live Demo:** [cluefinance.vercel.app](https://cluefinance.vercel.app/)

**Key Features:**
- Multi-tenant architecture with row-level security (RLS) for data isolation
- Loan opportunity and application processing workflows
- ABN/ABR business validation integration
- 2FA authentication for admin users
- Audit trails with IP monitoring
- Email notifications via Postmark
- Location search integration with Mapbox
- Rich text editing and PDF document generation
- Content Security Policy headers and XSS protection

**Tech Stack:**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_(PostgreSQL)-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Postmark](https://img.shields.io/badge/Postmark-FFCC00?style=flat-square&logoColor=black)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<details>
<summary><strong>Architecture</strong></summary>

```
Frontend:    Next.js 15 (App Router) with Server-Side Rendering
Backend:     Next.js API Routes with middleware authentication
Database:    Supabase (PostgreSQL) with Row-Level Security & migrations
Auth:        2FA for admin users + JWT with audit trails
Services:    Postmark (email), Mapbox (location), ABN/ABR (verification)
Security:    CSP headers, XSS protection, IP monitoring, audit logging
Editor:      TipTap for rich text + jsPDF for document generation
Deployment:  Vercel with GitLab CI/CD pipeline
```
</details>

<details>
<summary><strong>Screenshots (click to expand)</strong></summary>
<br>

#### Dashboard — Loan pipeline overview with key metrics and activity
![Dashboard](screenshots/clue/Clue-Dashboard.png)

#### Clients — Manage organizations with multi-tenant data isolation
![Clients](screenshots/clue/Clients.png)

#### Client Detail — Full client profile with loan history and documents
![Client Detail](screenshots/clue/Client-Detail.png)

#### Opportunities — Track and manage loan opportunities through the pipeline
![Opportunities](screenshots/clue/Opportunity.png)

#### Potential Referrers — Manage and onboard new referral partners
![Potential Referrer](screenshots/clue/Potential-Referrer.png)

</details>

---

## Tech Stack Overview

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Cloud & DevOps
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

---

## About Me

I'm a Senior Full-Stack Developer with 10+ years of experience building web applications. I specialize in modern JavaScript/TypeScript ecosystems and have delivered production-ready applications across healthcare, finance, and field service industries.

### What I Bring to Every Project
- End-to-end development from architecture to deployment
- Clean, maintainable, and scalable code
- Role-based access control and security best practices
- Responsive design that works across all devices
- Production deployment and performance optimization

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jn-abhi)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://sterlinginfotech.com/portfolio)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@sterlinginfotech.com)

---

> I'm available for **freelance projects**, **contract work**, and **full-time remote roles**. If you need an experienced full-stack developer, let's talk!

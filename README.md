# Housing In Ghana Magazine – Full-Stack Case Study

> A production-grade digital publishing platform built with modern web technologies.
> This repository documents architecture decisions, system design, and engineering challenges.
> No proprietary source code is included.

---

## 🚀 Project Summary

Housing In Ghana Magazine is a scalable publishing platform supporting readers, contributors, editors, and administrators. The system demonstrates real-world full-stack engineering across content workflows, real-time systems, and performance optimization.

**Role:** Full-Stack Developer  
**Project Type:** Client Work (Production Application)

---

## 🛠 Tech Stack

- **Frontend:** Next.js (App Router), React, TypeScript
- **Backend:** Next.js API Routes & Server Actions
- **Database:** PostgreSQL (Neon) + Drizzle ORM
- **Real-Time:** WebSockets + Redis
- **Styling:** Tailwind CSS, Radix UI
- **Storage:** DigitalOcean Spaces
- **Deployment:** Vercel

---

## 🏗 Architecture

The application uses a **monolithic Next.js architecture** with a clear separation of concerns.

### Why Monolithic?
- Faster development
- Lower operational overhead
- Shared type safety
- Reduced latency between services

This approach provided the best tradeoff for speed, maintainability, and scalability at the project’s stage.

---

## ✨ Key Features

### Contributor System
- Multi-stage contributor onboarding
- Role-based permissions
- Submission and approval workflows
- Contributor recognition mechanisms

### Editorial Workflow
- Draft → Review → Revision → Publish pipeline
- Reviewer assignment and feedback tracking
- Audit trails for content decisions

### Real-Time Notifications
- WebSocket-based admin notifications
- Redis-backed connection management
- Fallback delivery mechanisms

### Admin Dashboard
- Real-time metrics
- Cached analytics
- Role-based views

---

## ⚡ Performance Optimizations

- Redis caching for hot paths
- Indexed PostgreSQL queries
- Server-side rendering for SEO
- Automatic code splitting and lazy loading

---

## 🔐 Security

- Role-based access control
- Secure authentication and sessions
- API validation and protection
- Rate limiting and monitoring

---

## 🧠 Engineering Challenges

### Complex State & Permissions
Solved with centralized permission checks and role definitions.

### Real-Time Reliability
Implemented hybrid WebSocket + HTTP fallback delivery.

### Safe Database Migrations
Designed zero-downtime migration workflows with verification and rollback.

---

## 📈 Results

- Sub-2s page loads
- <500ms average API response
- Stable real-time delivery under load

---

## 📌 Notes

This repository is a **technical case study** only.  
All proprietary code, credentials, and sensitive data have been intentionally excluded.

---

## 👨‍💻 Author

**Blaise Elolo Akpalu**  
Full-Stack / Front-End Engineer  


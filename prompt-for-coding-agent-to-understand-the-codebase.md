# MASTER PROMPT — SYSTEM UNDERSTANDING & FULL APPLICATION DOCUMENTATION

## Role & Objective

You are an **expert software architect, technical writer, and reverse‑engineering specialist**. Your task is to produce **ONE SINGLE, COMPREHENSIVE DOCUMENT** that fully explains the **current state of this application**.

This document will act as the **source of truth** for all future development, enhancements, refactors, and AI‑assisted coding.

⚠️ **Do NOT propose new features. Do NOT redesign anything. Do NOT assume future scope.**
Your job is to **observe, analyze, infer, and document what already exists**.

---

## Inputs Available to You

You may have access to:

- The full codebase (frontend, backend, config, infra, scripts)
- Environment variables and deployment configs
- API endpoints (live or referenced)
- README files or partial documentation
- CI/CD configs (if present)
- Hosting / deployment URLs (if present)

You must infer missing context **from the code itself**, not assumptions.

---

## Output Requirement (VERY IMPORTANT)

You must output **ONE SINGLE WELL‑STRUCTURED DOCUMENT** and **SAVE IT AS A PHYSICAL FILE**.

⚠️ **ACTION REQUIRED**: Do NOT just output the response in the chat. You MUST create a new markdown file named `SYSTEM_UNDERSTANDING.md` in the **root directory** of the application and write the entire content there.

No fragments. No partial answers. No multiple documents.

Use **clear headings, sub‑headings, bullet points, and diagrams in text form** where helpful.

This document must enable **any senior engineer or AI agent** to understand the app **without seeing the original code**.

---

## DOCUMENT STRUCTURE (MANDATORY)

### 1. Application Overview

- Application name (as inferred)
- Purpose of the application
- Primary problem it solves
- Target users
- Real‑world use cases

---

### 2. High‑Level System Architecture

- Overall architecture style (monolith, microservices, client‑server, etc.)
- Frontend ↔ Backend interaction flow
- External services used (payments, auth, AI models, APIs, etc.)
- Text‑based architecture diagram

---

### 3. Frontend

- Framework / library used
- Folder structure explanation
- Routing mechanism
- State management approach
- UI/UX behavior (themes, flows, conditional rendering)
- Key screens/pages and their responsibilities

---

### 4. Backend

- Runtime & framework
- Folder structure explanation
- API design pattern
- Controllers / services / middleware logic
- Authentication & authorization (if any)
- Error handling strategy

---

### 5. Database & Storage

- Database type (SQL / NoSQL / file‑based)
- Schema or table structure
- Relationships between entities
- Migrations / seed data (if any)

---

### 6. API Documentation (AS‑IS)

For **each API endpoint**, document:

- Endpoint path
- HTTP method
- Purpose
- Request payload
- Response payload
- Error responses
- Authentication requirement

---

### 7. Core Functionalities (CURRENT ONLY)

Explain **each existing feature** in detail:

- What the feature does
- How it works internally
- User flow
- Backend logic involved
- Edge cases already handled

⚠️ No feature suggestions here.

---

### 8. Configuration & Environment

- Environment variables
- Secrets handling
- Config files
- Build‑time vs run‑time configs

---

### 9. Deployment & Infrastructure

- Hosting platform(s)
- Domains / subdomains used
- Build & deployment flow
- CI/CD (if present)
- CDN, tunnels, proxies, or gateways

---

### 10. Security Considerations (CURRENT IMPLEMENTATION)

- Authentication mechanisms
- Authorization rules
- Data protection
- Known limitations visible from code

---

### 11. Logging, Monitoring & Debugging

- Logging approach
- Error reporting
- Debug tools or flags

---

### 12. Tech Stack Summary

Provide a **clear table** listing:

- Frontend technologies
- Backend technologies
- Database
- DevOps / Infra
- Third‑party libraries

---

### 13. Current Status & Maturity Assessment

- Is the app MVP / beta / production‑ready
- What is complete
- What is partially implemented
- What is stubbed or placeholder logic

⚠️ Only observations, no opinions.

---

### 14. Known Constraints & Assumptions

- Hard‑coded values
- Temporary logic
- Design constraints visible in code

---

### 15. How This App Is Meant to Be Extended (BASED ON CURRENT DESIGN)

- Extension points
- Modularity
- Where future features would logically plug in

⚠️ Describe structure, **not ideas**.

---

## Tone & Quality Bar

- Be **precise, technical, and explicit**
- Avoid vague language
- Write as if this document will be used for **AI‑driven autonomous development**
- Assume the next reader is a **coding agent, not a human beginner**

---

## Final Instruction

1. Start immediately.
2. Analyze the entire application.
3. Create the file `SYSTEM_UNDERSTANDING.md` in the root directory.
4. Populate it with the **complete single document** as specified above.
5. Do not ask clarifying questions unless something is **technically impossible** to infer.

# 🧩 SPEC-KIT PROJECT INPUT TEMPLATE

> **Instructions to the user:** Please fill in the fields below as clearly and specifically as possible. You can use bullet points where helpful. Once completed, paste this back to an LLM and updated `/speckit.*` prompts will be generated for you.

---

## 1️⃣ PROJECT OVERVIEW

**Project Name:**

**One-line description of the app:**

**Target users (who is this for?):**

**Primary problem this app solves:**

---

## 2️⃣ FRONTEND DETAILS

**Preferred framework / tool (if any):**

* [ ] Vite (recommended)
* [ ] React
* [ ] Vanilla JS only
* [ ] Other: _______

**Styling preference:**

* [ ] Plain CSS
* [ ] Tailwind
* [ ] Other: _______

**Key UI screens needed (list):**
1.
2.
3.

**Accessibility needs (if any):**

---

## 3️⃣ BACKEND & DATA

**Where should data be stored?**

* [ ] Local SQLite (recommended)
* [ ] JSON files
* [ ] Other: _______

**Will images be uploaded anywhere?**

* [ ] No (local only)
* [ ] Yes → Where? _______

**What metadata should be stored per photo?** (e.g., date, tags, location)

---

## 4️⃣ CORE FEATURES REQUIRED

Please describe what the app MUST do:

1. Album creation:
2. Album grouping by date:
3. Drag-and-drop behavior:
4. Photo preview style (tiles, grid, etc.):
5. Search or filter (yes/no + details):
6. Delete / edit functionality:

---

## 5️⃣ TOOLS & TECH STACK

Preferred tools (tick or add):

* Build tool: Vite / Other: _______
* Database: SQLite / Other: _______
* Testing: Jest / Vitest / None / Other: _______
* Linting: ESLint / None / Other: _______

---

## 6️⃣ AGENT SKILLS REQUIRED

What should the AI agent be capable of?

* [ ] Writing clean JavaScript
* [ ] Designing UI layouts
* [ ] Working with SQLite
* [ ] Implementing drag-and-drop
* [ ] Writing tests
* [ ] Creating documentation

Add any additional skills:

---

## 7️⃣ CONSTRAINTS & PRINCIPLES

(Your expectations for quality)

**Code quality standards:**

**Testing expectations:**

**Performance expectations:**

**User experience principles:**

---

## 8️⃣ DELIVERY FORMAT

How do you want outputs structured?

* [ ] Full repository structure
* [ ] Step-by-step plan
* [ ] Ready-to-run code
* [ ] All of the above

---

> ✅ After filling this, give the above information with the below prompt to your favorite LLM. LLM will then generate customized prompts:
> `/speckit.constitution`
> `/speckit.specify`
> `/speckit.plan`
> `/speckit.tasks`
> `/speckit.implement`
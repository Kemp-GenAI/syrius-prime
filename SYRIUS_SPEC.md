# SYRIUS PRIME — SYSTEM SPEC

## 1. Purpose
SYRIUS PRIME is a lightweight web-based system for:
- Landing page presentation
- User data capture (surveys/forms)
- Future expansion into structured intelligence systems

---

## 2. Current State
- Static HTML site deployed via Netlify
- Connected to GitHub repository: syrius-prime
- Auto-deployment enabled from main branch

---

## 3. Data Strategy (Phase 1)
Initial focus:
- Simple form inputs
- Lightweight data collection
- No backend complexity yet

Preferred initial tool:
- Netlify Forms (or equivalent zero-backend capture layer)

---

## 4. Source of Truth Hierarchy
1. GitHub repository (primary truth)
2. Deployed Netlify site (live reflection)
3. Chat threads (contextual guidance only)

---

## 5. Evolution Rule
All system changes must:
- Update codebase
- Maintain alignment with this specification file
- Avoid uncontrolled divergence between UI and data model

---

## 6. Design Principle
Start simple → validate → scale structure incrementally

# Chris Mendoza — Software Developer

I'm a software developer in the Pacific Northwest with a hands-on background in marine machining, manufacturing, and IT. That combination shapes how I build software: I think in tolerances, failure modes, repeatable workflows, and tools that have to make sense outside of a demo.

I build Android apps, web applications, developer tooling, and automation systems — often around real-world problems I've encountered myself.

**BAS, Mobile & Web App Development — North Seattle College**

---

## 🚀 Featured Work

### 🛠️ ShaftSchematic — Android · Kotlin · Jetpack Compose
An Android application for rapidly modeling marine propeller-shaft assemblies and producing clean, dimensioned technical documents. It grew directly out of my work as a marine machinist and is designed around real inspection, repair, and machining workflows.

**Highlights:**
- Parametric shaft modeling with bodies, tapers, threads, liners, keyways, undercuts, and coupler features
- Live dimensioned Compose drawing with canonical millimeter geometry and inch/mm UI conversion
- Technical PDF generation for shaft schematics, runout, wear inspection, undercuts, and consolidated reports
- Versioned `.shaft` document format with migrations, autosave, backup, restore, and import/export
- Validation and geometry rules modeled around real machining constraints rather than generic drawing primitives

👉 [github.com/chrisjmendoza/ShaftSchematic](https://github.com/chrisjmendoza/ShaftSchematic)

---

### 🚲 Rideprint — Next.js · TypeScript · Supabase *(live at [rideprint.com](https://rideprint.com))*
A mobile-first bike maintenance platform for building a durable service history across the life of a bicycle. Riders can track maintenance and rides, while verified shops can add service records directly to customer bikes.

**Highlights:**
- Next.js App Router with Supabase Postgres, Auth, Storage, RLS, and SSR sessions
- AI-assisted bike specification lookup and receipt OCR using Claude
- Service intervals, reminders, component tracking, and public QR bike profiles
- Verified-shop workflows with mechanic access controls and customer lookup
- Strava ride import, Stripe freemium payments, Resend email reminders, and installable PWA support
- 184 automated tests across 25 files

👉 [rideprint.com](https://rideprint.com)

---

### 📘 Reading the Machine — Programming Textbook / Instructional Project
A programming textbook built around real production-style code from ShaftSchematic and MemoBoard. Instead of teaching isolated syntax exercises, it focuses on learning how to read an unfamiliar codebase, trace behavior, reason about architecture, debug problems, understand tests, and turn requirements into implementation.

The project is currently being prepared for publication and instructor feedback as supplemental programming material.

---

### 📌 MemoBoard — React Native · Expo · TypeScript
A tactile corkboard-style note app built around a large pannable and zoomable canvas. Notes behave like physical objects rather than rows in a conventional notes list.

**Highlights:**
- Reanimated + Gesture Handler canvas with pan, pinch-to-zoom, drag, resize, rotation, and z-order controls
- Sticky notes, index cards, text bubbles, photos, checklists, and link cards
- Multiple named boards with persistent local storage
- Per-note typography, formatting, color customization, and automatic text contrast
- TypeScript-first architecture with a substantial Jest test suite

👉 [github.com/chrisjmendoza/hanna-notes](https://github.com/chrisjmendoza/hanna-notes)

---

### 🤖 Hephaestus — Python · AI Developer Tooling
A local AI software-engineering assistant that accepts a natural-language development task, reasons over an actual repository, generates a structured plan, and executes work through a controlled tool layer.

**Highlights:**
- `task → plan → execute → report` lifecycle with structured logging
- Semantic repository search across multiple programming languages
- LLM-guided planning and patch generation
- Dry-run previews, file patching, test execution, and Git-aware workflows
- Per-repository memory for continuity across sessions
- GitHub issue-to-PR workflow support

👉 [github.com/chrisjmendoza/Hephaestus](https://github.com/chrisjmendoza/Hephaestus)

---

## 🔧 Other Projects

### 🔌 PortFlow — C# · .NET 8 · Windows
A Windows backup utility that detects a specific USB drive by identity rather than drive letter and automatically runs controlled Robocopy backup jobs in the background.

👉 [github.com/chrisjmendoza/portflow](https://github.com/chrisjmendoza/portflow)

### 📁 DocArchivist — Python · FastAPI · React
A local-first document management system for extracting text from PDFs and images, applying structured metadata, and making scanned documents searchable with OCR and SQLite FTS5. Currently in development.

---

## 🧰 Tech I Work With

**Languages**  
Kotlin · TypeScript · Python · C# · SQL

**Application Development**  
Jetpack Compose · Android SDK · Next.js · React · React Native · Expo · FastAPI · .NET

**Data & Infrastructure**  
Supabase · PostgreSQL · SQLite / FTS5 · REST APIs · Vercel · GitHub

**Automation & Applied AI**  
LLM APIs · OCR workflows · document processing · repository tooling · developer automation

---

## 🧭 How I Build

- Start with the actual workflow and constraints, not just the UI
- Keep domain logic explicit, testable, and separate from presentation code
- Treat edge cases and failure modes as part of the design
- Prefer maintainable systems over clever one-off solutions
- Use AI tooling to accelerate iteration while still verifying behavior through tests, documentation, and real-world constraints
- Write documentation so someone other than the original author can understand the system later

---

## 📫 Contact & Links

- **Portfolio:** [chrismendoza-dev.vercel.app](https://chrismendoza-dev.vercel.app)
- **LinkedIn:** [linkedin.com/in/chrisjmendoza](https://www.linkedin.com/in/chrisjmendoza/)
- **Email:** [chrisjmendoza@gmail.com](mailto:chrisjmendoza@gmail.com)

# Chris Mendoza — Developer

Hi, I'm Chris — a developer based in the Pacific Northwest with a background that runs through IT, manufacturing, and the trades. That mix shapes how I build: I care about precision, real-world practicality, and software that actually holds up.

I build web apps, Android apps, and custom tools. Most of what I work on sits at the intersection of structured engineering problems and clean, maintainable code.

---

## 🚀 Featured Projects

### 🚲 Shiftlog — Web App · Next.js · Supabase *(live at [shiftlog.bike](https://shiftlog.bike))*
A mobile-first bike maintenance tracking web app. Cyclists log every service, track component wear, get maintenance reminders, and carry a complete history through ownership transfers — like a Carfax for bikes.

**Key features:**
- Google OAuth + email/password auth with SSR cookie sessions
- AI-assisted bike registration — enter year/brand/model, specs auto-populate via Claude API
- Receipt OCR — snap or upload a shop invoice, AI extracts and pre-fills the service record
- Service interval tracking with progress bars, component library, and auto-seeded intervals on bike creation
- Daily reminder emails via Resend + Vercel Cron
- Public QR bike profiles with three privacy tiers
- Photo upload with client-side compression
- Ride logging with aggregate stats
- Full test suite — 41 tests across 11 files, all green

👉 [shiftlog.bike](https://shiftlog.bike)

---

### 📌 TackBoard — React Native · Expo
A corkboard-style note canvas app for Android. Pin 6 note types to a large pannable and zoomable canvas across multiple named boards.

**Key features:**
- Pan/pinch-zoom canvas at 120fps (UI thread, Reanimated 4)
- Sticky notes, index cards, checklists, photos, text bubbles, links
- Note resize, rotation, color themes, snap-to-grid
- Rubber-band multi-select, tack grouping, board templates
- Persistent local storage with schema versioning and migration
- 426 passing tests across 19 suites

👉 [github.com/chrisjmendoza/hanna-notes](https://github.com/chrisjmendoza/hanna-notes)

---

### 🤖 Hephaestus — AI Agent · Python
A local AI software engineering agent that accepts a natural-language task, scans a repository using semantic search, generates a structured plan via LLM, and executes each step through a controlled tool layer.

**Key features:**
- Multi-LLM support: Anthropic Claude, OpenAI, Ollama, Groq, LM Studio
- File patching, test running, git commits, GitHub PR creation
- Issue watcher daemon — polls GitHub and auto-resolves labeled issues
- Per-repo memory for continuity across sessions
- Dry-run mode, structured task reports, 20+ test files

👉 [github.com/chrisjmendoza/Hephaestus](https://github.com/chrisjmendoza/Hephaestus)

---

### 🛠️ ShaftSchematic — Android · Kotlin
Android app for modeling marine propeller-shaft assemblies with parametric components and real-world machining rules.

**Key features:**
- Jetpack Compose UI with live dimensioned canvas preview
- Parametric bodies, tapers, liners, threads
- Snap engine, taper calculations, OAL logic
- PDF export and drawing layout engine
- Clean, modular architecture with full unit test coverage

👉 [github.com/chrisjmendoza/ShaftSchematic](https://github.com/chrisjmendoza/ShaftSchematic)

---

### 🔌 PortFlow — C# · .NET 8 · Windows
A Windows backup utility that automatically backs up folders to a USB drive the moment it's plugged in.

**Key features:**
- Drive identification via sentinel marker file — not fragile drive letters
- WMI USB detection with event storm protection and debounce
- Robocopy-based backup engine with job object process control
- Silent system tray operation with async buffered logging
- Full install/uninstall scripts, scheduled task integration

👉 [github.com/chrisjmendoza/portflow](https://github.com/chrisjmendoza/portflow)

---

### 📁 DocArchivist — Python · FastAPI · React *(in development — available on request)*
A local-first, AI-powered document management system. Drop in a scanned PDF or image — DocArchivist extracts text via OCR, applies AI-driven metadata, and files everything into a searchable archive.

**Key features:**
- PDF text extraction with OCR fallback (PyMuPDF + Tesseract)
- AI metadata: title, vendor, date, category, summary
- Multi-provider AI: OpenAI and Anthropic, switchable at runtime
- SQLite FTS5 full-text search across all documents
- React + TypeScript frontend with TanStack Query

---

## 🔧 Tech Stack

### Web
- Next.js / React / TypeScript
- Tailwind CSS
- Supabase (Postgres, Auth, Storage)
- REST APIs / Server Actions
- Vercel

### Mobile
- Kotlin / Jetpack Compose / Android SDK
- React Native / Expo
- MVVM architecture · Coroutines · Material 3

### Backend & Automation
- Python / FastAPI
- SQLite / FTS5
- OCR workflows (Tesseract / PyMuPDF)
- PDF processing and automation utilities

### Other
- C# / .NET 8 / WinForms
- Git / GitHub

---

## 💼 What I Work On

- Production web apps with auth, databases, and AI integration
- Android features, UI builds, and bug fixes (Kotlin + Compose)
- Python tooling, OCR pipelines, and data extraction
- FastAPI backends and automation workflows
- Custom desktop utilities and system tools
- Refactoring legacy codebases into maintainable systems

---

## 🎯 How I Work

- Clear communication and honest expectations
- Thoughtful, predictable engineering
- Strong debugging and systems thinking
- High-quality code built to last
- Fast iteration without cutting corners

---

## 📫 Contact & Links

- **Portfolio:** [chrismendoza-dev.vercel.app](https://chrismendoza-dev.vercel.app)
- **LinkedIn:** [linkedin.com/in/chrisjmendoza](https://www.linkedin.com/in/chrisjmendoza/)
- **Email:** [chrisjmendoza@gmail.com](mailto:chrisjmendoza@gmail.com)

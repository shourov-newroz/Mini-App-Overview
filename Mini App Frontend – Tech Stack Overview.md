## 📦 Mini App Frontend – Tech Stack Overview

### Purpose

This mini web app is designed to run **inside the Super App as WebView** and follows an **enterprise-grade frontend architecture** focused on scalability, performance, and long-term maintainability.

---

### 🧱 Core Framework & Tooling

- **React.js** – UI composition and component model
- **Vite** – Fast development server and optimized production builds
- **TypeScript (strict)** – Strong typing and compile-time safety

---

### 🧩 Architecture Approach

- **Feature-based, domain-driven structure**
- Each feature owns its **UI, state, services, and tests**
- No hidden cross-feature coupling
- Ready for future micro-frontend evolution

---

### 🧠 State & Data Management

- **Zustand** – Lightweight, feature-scoped client state management
- **SWR** – Server-state management with caching and revalidation
- **Axios** – Centralized HTTP client with interceptors and error handling

---

### 🎨 UI & Styling

- **Tailwind CSS** – Token-based, utility-first styling
- **shadcn/ui** – Accessible, composable UI components

---

### 🧪 Testing & Quality

- **Vitest** – Fast unit and integration testing
- **React Testing Library** – User-focused component testing
- **MSW** – API mocking for reliable tests

---

### 🧼 Code Quality & Governance

- ESLint (strict rules)
- Prettier (consistent formatting)
- Husky + lint-staged (pre-commit checks)
- Conventional Commits

> Linting, formatting, and tests must pass before code can be committed.

---

### 📡 Observability & Stability

- Centralized logging utilities
- Error boundaries for runtime safety

---

### ⚡ Performance Principles

- Feature-level code splitting
- Lazy loading where applicable
- Optimized state subscriptions
- WebView-friendly bundle sizes

---

### ✅ Outcome

This stack ensures the mini app is:

- **Production-ready**
- **Highly maintainable**
- **Scalable with team growth**
- **Optimized for Super App WebView environments**

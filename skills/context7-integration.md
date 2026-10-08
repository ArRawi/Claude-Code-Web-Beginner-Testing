---
name: context7-integration
description: Guidelines and reference patterns for fetching real-time, version-specific framework and library documentation via Context7 to eliminate AI hallucinations.
---

# Context7 Real-Time Documentation Integration

**Context7** ensures that AI agents write code using current, version-accurate documentation for libraries, frameworks, and SDKs.

## Agent Specific Usage Guidelines

### 1. Aisha (UI/UX & Frontend Lead)
* **Triggers:** React, Next.js, Vue, Tailwind CSS, Framer Motion, Shadcn UI, Vite.
* **Usage Pattern:** Query Context7 with the specific major/minor framework version:
  - `/vercel/next.js@15`
  - `/tailwindlabs/tailwindcss@v4`
  - `/facebook/react@19`
* **Rule:** Never guess new class names, component APIs, or server component directives without checking Context7 docs first.

### 2. Jane (Lead Architect & Security Engineer)
* **Triggers:** FastAPI, Spring Boot, Prisma, Drizzle, PyTorch, Docker, Kubernetes, AWS SDKs.
* **Usage Pattern:** Fetch latest API schemas and security advisories:
  - `/fastapi/fastapi@0.115`
  - `/prisma/prisma@6`
* **Rule:** Verify breaking API changes before writing code migrations or backend handlers.

### 3. Nasuha (Research & Fact Verification)
* **Triggers:** Framework comparisons, new library releases, API deprecation checks.
* **Usage Pattern:** Retrieve authoritative library docs to compare implementations or cite primary specs.

## Command Syntax
Agents include `use context7` or target documentation using the pattern:
```
use context7 /org/repo@version
```

Create a concise `.github/copilot-instructions.md` (and copy it to `AGENTS.md`) with our engineering rules:
1. Tech Stack: TypeScript (strict mode), Node.js / NestJS (if backend is needed), React + Vite + Tailwind (if frontend is needed), Vitest/Jest for testing.
2. Architecture: Clean Architecture principles. Keep domain entities, business validations, and formatters in pure TypeScript (`src/domain`), completely decoupled from UI or frameworks.
3. Quality & TDD: Every domain rule and service must have unit tests.
4. AI Behavior: Escalate instead of guessing. Do not invent requirements not present in the specification. Keep functions small and readable.

# blueprint-playwright-ts

A modern Playwright + TypeScript starter kit. Kickstart your next journey with this template.

## 📦 Project structure

- `tests/` – E2E tests organized by topic
- `pages/` – Page Object Models (POM)
- `components/` – reusable components
- `fixtures/` – test data and fixtures
- `utils/` – utility functions
- `config/` – environment configurations

## 🧱 Naming conventions

- **Class naming**: PascalCase (e.g., `LoginPage`)
- **Test file names**: snake_case with the extension `.spec.ts` (e.g., `login.spec.ts`)
- **Method names**: camelCase (e.g. `submitLoginForm`)
- **Test names**: descriptive, e.g. `should display error for invalid credentials`
- **Test tagging**: use `@smoke`, `@regression`, `@critical` in test annotations

## 💡 Design principles

# SOLID

**Single Responsibility Principle (SRP)**
Description:
Each class or module should have only one task. This means that changing one aspect of the application should require changing only one class.
Example in testing:
Do not combine page logic with test assertions in the same class.

## Environment management

dotenv
cross-env

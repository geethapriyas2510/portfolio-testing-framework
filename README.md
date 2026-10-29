# Playwright E-Commerce Automation Framework

A high-performance, scalable automated testing framework designed with **Playwright** and **TypeScript** to validate core end-to-end user workflows on e-commerce platforms.

## 🚀 Key Features Built
- **Robust End-to-End Workflows:** Completely automates login validations, cart item additions, and full data-driven checkout processes.
- **Resilient Locators:** Utilizes clean `data-test` explicit attribute selectors to prevent test brittleness and ensure stability.
- **Comprehensive Test Isolation:** Implements test hooks (`beforeEach`) ensuring clean execution states across cycles.
- **Rich HTML Reporting:** Generates diagnostic test results and execution tracking automatically.

## 🛠️ Tech Stack & Tooling
- **Test Runner:** Playwright (v1.49+)
- **Language:** TypeScript
- **Runtime:** Node.js

## 📦 Local Installation & Setup

1. Clone the project locally:
   ```bash
   git clone https://github.com
   ```
2. Install all core framework dependencies:
   ```bash
   npm install
   ```
3. Install the required isolated browser binaries:
   ```bash
   npx playwright install
   ```

## 🎭 Running the Test Suite

Execute the entire test battery in headless mode:
```bash
npx playwright test
```

To watch the live browser automation execution window:
```bash
npx playwright test --headed
```

To view the interactive graphical test reporting engine dashboard:
```bash
npx playwright show-report
```

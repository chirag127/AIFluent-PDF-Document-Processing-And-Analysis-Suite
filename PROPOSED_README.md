# AIFluent-PDF-Document-Processing-And-Analysis-Suite

<!-- Hero Banner / Logo Placeholder -->
<p align="center">
  <img src="https://via.placeholder.com/1200x300.png?text=AIFluent-PDF-Document-Processing-And-Analysis-Suite" alt="AIFluent Banner" style="width:100%;">
</p>

<!-- Live Badges -->
<p align="center">
  <!-- Build Status (Python Backend) -->
  <a href="https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/actions/workflows/python-ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/python-ci.yml?branch=main&label=Python%20CI&style=flat-square" alt="Python CI Status">
  </a>
  <!-- Build Status (TypeScript Frontend) -->
  <a href="https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/actions/workflows/typescript-ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/typescript-ci.yml?branch=main&label=TypeScript%20CI&style=flat-square" alt="TypeScript CI Status">
  </a>
  <!-- Code Coverage (Python) -->
  <a href="https://codecov.io/gh/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite">
    <img src="https://img.shields.io/codecov/c/github/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/main?label=Python%20Coverage&style=flat-square&token=YOUR_CODECOV_TOKEN" alt="Python Code Coverage">
  </a>
  <!-- Code Coverage (TypeScript) -->
  <a href="https://codecov.io/gh/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite">
    <img src="https://img.shields.io/codecov/c/github/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/main?label=TS%20Coverage&style=flat-square&token=YOUR_CODECOV_TOKEN" alt="TypeScript Code Coverage">
  </a>
  <!-- Python Version -->
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python&logoColor=white" alt="Python Version">
  <!-- TypeScript Version -->
  <img src="https://img.shields.io/badge/TypeScript-6.x-blue?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript Version">
  <!-- Ruff Linter -->
  <img src="https://img.shields.io/badge/Linter-Ruff-black?style=flat-square&logo=ruff" alt="Ruff Linter">
  <!-- Biome Formatter -->
  <img src="https://img.shields.io/badge/Formatter-Biome-blueviolet?style=flat-square&logo=biome" alt="Biome Formatter">
  <!-- Pytest -->
  <img src="https://img.shields.io/badge/Tests-Pytest-green?style=flat-square&logo=pytest&logoColor=white" alt="Pytest">
  <!-- Vitest -->
  <img src="https://img.shields.io/badge/Tests-Vitest-yellowgreen?style=flat-square&logo=vitest" alt="Vitest">
  <!-- License -->
  <a href="https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square" alt="License: CC BY-NC 4.0">
  </a>
  <!-- GitHub Stars -->
  <a href="https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/stargazers">
    <img src="https://img.shields.io/github/stars/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite?style=flat-square&colorA=white&colorB=white&logo=github" alt="GitHub stars">
  </a>
</p>

<!-- Social Proof -->
<p align="center">
  <a href="https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/stargazers">
    <img width="170" height="30" src="https://img.shields.io/badge/Star%20⭐%20this%20Repo-white?style=for-the-badge&logo=github&labelColor=black">
  </a>
</p>

## Bluf: Elevate Your Document Intelligence 🚀

AIFluent-PDF-Document-Processing-And-Analysis-Suite is an advanced, AI-powered platform designed to revolutionize how organizations interact with unstructured PDF content. It leverages cutting-edge natural language processing and machine learning to enable intelligent data extraction, comprehensive summarization, and deep analytical insights from complex documents, significantly boosting productivity and knowledge accessibility.

## 🏛️ Architecture: Modular Monolith with Distributed AI Processing

AIFluent is architected as a robust modular monolith for its backend services, allowing for clear separation of concerns in document processing, AI inference, and data management. The frontend is a modern TypeScript-based web application, communicating with the backend via a RESTful API. AI processing itself is designed for distributed execution, leveraging cloud-based services and APIs (like Google Gemini) for scalable and efficient document analysis.

mermaid
graph TD
    A[User/Client] -->|HTTP/S| B(Frontend Web App - TypeScript, Vite, React)
    B -->|REST API| C(Backend API - Python, FastAPI)
    C --> D{PDF Document Processing Module}
    C --> E{AI Analysis & Summarization Module}
    C --> F{Data Extraction & Storage Module}
    D --> G(PDF Parsing & Text Extraction)
    E --> H(Google Gemini API / LLM Integration)
    F --> I(Database/Vector Store)
    H --> J(AI-Powered Insights & Summaries)
    G --> E
    E --> F
    F --> B


## 📋 Table of Contents

*   [Bluf: Elevate Your Document Intelligence 🚀](#bluf-elevate-your-document-intelligence-🚀)
*   [🏛️ Architecture: Modular Monolith with Distributed AI Processing](#️-architecture-modular-monolith-with-distributed-ai-processing)
*   [📋 Table of Contents](#-table-of-contents)
*   [🤖 AI Agent Directives (CRITICAL)](#-ai-agent-directives-critical)
    *   [1. IDENTITY & PRIME DIRECTIVE](#1-identity--prime-directive)
    *   [2. INPUT PROCESSING & COGNITION](#2-input-processing--cognition)
    *   [3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)](#3-context-aware-apex-tech-stacks-late-2025-standards)
        *   [PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python Backend)](#primary-scenario-data--scripts--ai-python-backend)
        *   [SECONDARY SCENARIO: WEB / APP (TypeScript Frontend)](#secondary-scenario-web--app-typescript-frontend)
    *   [4. ARCHITECTURAL PATTERNS & PRINCIPLES](#4-architectural-patterns--principles)
    *   [5. VERIFICATION & QUALITY ASSURANCE](#5-verification--quality-assurance)
*   [🚀 Getting Started](#-getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Backend Setup (Python)](#backend-setup-python)
    *   [Frontend Setup (TypeScript)](#frontend-setup-typescript)
*   [🛠️ Development Scripts](#️-development-scripts)
    *   [Backend (Python)](#backend-python)
    *   [Frontend (TypeScript)](#frontend-typescript)
*   [💡 Core Principles](#-core-principles)
*   [🤝 Contributing](#-contributing)
*   [📄 License](#-license)
*   [🛡️ Security](#️-security)
*   [🐛 Bug Report](#-bug-report)
*   [✨ Pull Request](#-pull-request)
*   [💖 Support](#-support)

## 🤖 AI Agent Directives (CRITICAL)

<details>
<summary><b>Expand for AI Agent Directives</b></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This project, `AIFluent-PDF-Document-Processing-And-Analysis-Suite`, is a dual-stack application comprising a Python-based AI/backend service and a TypeScript-based frontend web application.

*   **PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python Backend)**
    *   **Stack:** Leverages **Python 3.10+**. Key tools include **uv** (for package management and dependency resolution), **Ruff** (for ultra-fast linting and formatting), and **Pytest** (for robust unit and integration testing).
    *   **Backend Framework:** Utilizes **FastAPI** for building high-performance APIs for document upload, processing, and AI inference.
    *   **Architecture:** Adheres to a **Modular Monolith** pattern for the backend, ensuring clear separation of concerns for features like PDF parsing, AI processing, data storage, and API endpoints, while maintaining a unified deployment.
    *   **AI Integration:** Deeply integrated with **Google Gemini API** (`gemini-3-pro` by default) for intelligent batch-processing, summarization, extraction, and decision-making on PDF content. Prioritize modular design, clear API contracts, and robust error handling for all AI model interactions.
    *   **Data Storage:** Employs appropriate databases/vector stores (e.g., PostgreSQL, ChromaDB, Pinecone) for document metadata and extracted insights.

*   **SECONDARY SCENARIO: WEB / APP (TypeScript Frontend)**
    *   **Stack:** Built with **TypeScript 6.x** (Strict Mode enforced), **Vite 7** (using Rolldown for optimized bundling), and **React 19** (or latest stable, leveraging hooks and concurrent features). Styling is managed with **TailwindCSS v4**.
    *   **Architecture:** Follows the **Feature-Sliced Design (FSD)** methodology for scalable and maintainable frontend structure, ensuring clear boundaries between layers (App, Pages, Widgets, Features, Entities, Shared).
    *   **State Management:** Utilizes modern **Signals-based** state management (e.g., `@preact/signals-react` or similar standardized approach) for efficient and reactive UI updates.
    *   **Lint/Test:** Employs **Biome** (for speed and integrated linting/formatting) and **Vitest** (for lightning-fast unit/component testing). **Playwright** is used for robust end-to-end (E2E) testing across various browsers.

---

## 4. ARCHITECTURAL PATTERNS & PRINCIPLES
*   **General Principles:** Adhere to **SOLID** principles, **DRY** (Don't Repeat Yourself), and **YAGNI** (You Ain't Gonna Need It). Prioritize readability, maintainability, and testability.
*   **Frontend (TypeScript):** Implement **Feature-Sliced Design (FSD)** for organized and scalable component architecture.
*   **Backend (Python):** Maintain a **Modular Monolith** structure, ensuring domain-driven design principles for clear separation of concerns within services.
*   **Security by Design:** Implement robust authentication (e.g., OAuth 2.0, JWT), authorization, input validation, and secure API practices.
*   **Observability:** Integrate logging, tracing, and metrics for comprehensive system monitoring.

---

## 5. VERIFICATION & QUALITY ASSURANCE
*   **Unit Tests:**
    *   **Python:** Run `pytest` for comprehensive backend unit and integration tests.
    *   **TypeScript:** Run `vitest` for frontend unit and component tests.
*   **Linting & Formatting:**
    *   **Python:** Execute `ruff check --fix` and `ruff format` for code quality and consistency.
    *   **TypeScript:** Execute `biome check --apply` and `biome format --write` for frontend code quality and consistency.
*   **End-to-End Tests:** Execute `playwright test` for critical user flows in the frontend.
*   **Security Scans:** Integrate SAST/DAST tools into the CI/CD pipeline for continuous vulnerability detection.

</details>

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have the following installed:

*   **Python 3.10+**
*   **Node.js 18+** & **npm/yarn/pnpm** (recommended: `pnpm`)
*   **uv** (Python package manager, install via `pip install uv`)
*   **Git**

### Backend Setup (Python)

bash
# 1. Clone the repository
git clone https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite.git
cd AIFluent-PDF-Document-Processing-And-Analysis-Suite/backend # Assuming a 'backend' directory

# 2. Create and activate a virtual environment using uv
uv venv
source .venv/bin/activate # On Windows: .venv\Scripts\activate

# 3. Install Python dependencies
uv pip install -r requirements.txt # Or uv pip install -e . if using pyproject.toml

# 4. Set up environment variables (e.g., Google Gemini API Key)
cp .env.example .env
# Open .env and add your GEMINI_API_KEY and other necessary configurations

# 5. Run database migrations (if applicable)
# python -m alembic upgrade head # Example for SQLAlchemy/Alembic

# 6. Start the backend server
uv run python -m uvicorn main:app --host 0.0.0.0 --port 8000


### Frontend Setup (TypeScript)

bash
# 1. Navigate to the frontend directory
cd AIFluent-PDF-Document-Processing-And-Analysis-Suite/frontend # Assuming a 'frontend' directory

# 2. Install Node.js dependencies (using pnpm recommended)
pnpm install

# 3. Start the development server
pnpm dev
# The frontend typically runs on http://localhost:5173


## 🛠️ Development Scripts

### Backend (Python)

| Command                           | Description                                     |
| :-------------------------------- | :---------------------------------------------- |
| `uv run python main.py`           | Starts the backend API server.                  |
| `uv run pytest`                   | Runs all unit and integration tests.            |
| `uv run ruff check .`             | Checks for linting errors.                      |
| `uv run ruff check . --fix`       | Checks and automatically fixes linting errors.  |
| `uv run ruff format .`            | Formats Python code.                            |
| `uv run bandit -r .`              | Runs security linter (Bandit).                  |

### Frontend (TypeScript)

| Command                   | Description                                         |
| :------------------------ | :-------------------------------------------------- |
| `pnpm dev`                | Starts the development server.                      |
| `pnpm build`              | Builds the application for production.              |
| `pnpm test`               | Runs unit and component tests with Vitest.          |
| `pnpm test:e2e`           | Runs end-to-end tests with Playwright.              |
| `pnpm lint`               | Runs Biome linter.                                  |
| `pnpm format`             | Runs Biome formatter.                               |
| `pnpm lint:fix`           | Runs Biome to fix linting errors.                   |
| `pnpm format:write`       | Runs Biome to format and write changes.             |

## 💡 Core Principles

This project is built upon a foundation of robust software engineering principles:

*   **SOLID Principles:** Ensuring maintainable, scalable, and understandable code through Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.
*   **DRY (Don't Repeat Yourself):** Promoting code reuse and reducing redundancy to enhance consistency and ease of maintenance.
*   **YAGNI (You Ain't Gonna Need It):** Focusing on immediate needs and avoiding premature optimization or feature implementation, leading to lean and efficient solutions.
*   **Security by Design:** Integrating security considerations from the outset of the development lifecycle.
*   **Modularity:** Breaking down the system into independent, interchangeable components for easier development and testing.

## 🤝 Contributing

We welcome contributions! Please refer to our [CONTRIBUTING.md](https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/.github/CONTRIBUTING.md) for guidelines on how to get started.

## 📄 License

This project is licensed under the [CC BY-NC 4.0 License](https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/LICENSE).

## 🛡️ Security

For information on security practices and how to report vulnerabilities, please see our [SECURITY.md](https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/.github/SECURITY.md).

## 🐛 Bug Report

Found a bug? Help us improve by opening an issue using our [bug report template](https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/.github/ISSUE_TEMPLATE/bug_report.md).

## ✨ Pull Request

Want to contribute code? Please use our [pull request template](https://github.com/chirag127/AIFluent-PDF-Document-Processing-And-Analysis-Suite/blob/main/.github/PULL_REQUEST_TEMPLATE.md) for submitting changes.

## 💖 Support

If you find this project helpful, please consider giving it a star ⭐! Your support encourages continued development.

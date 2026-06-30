# High-Level Design (HLD)

## System Architecture

CodeSage AI follows a modular architecture where each service has a single responsibility.

---

## Components

### Frontend

- Flutter Web/Desktop
- Dashboard
- Repository Upload
- Report Viewer

---

### Backend

- FastAPI
- REST APIs
- Authentication
- Business Logic

---

### AI Engine

- OpenAI API
- Prompt Manager
- Response Validator

---

### Repository Intelligence

- Repository Parser
- AST Analyzer
- Dependency Analyzer
- Feature Discovery

---

### Testing Engine

- Test Generator
- Pytest Executor
- Coverage Analyzer

---

### Security Engine

- Bandit
- Semgrep

---

### Report Engine

- Repository Summary
- Engineering Report
- PDF Generator

---

### Database

- PostgreSQL
- Repository Metadata
- Analysis Results
- Reports

---

## Data Flow

Repository Upload

↓

Repository Analysis

↓

Repository Intelligence

↓

AI Analysis

↓

Test Generation

↓

Test Execution

↓

Security Scan

↓

Engineering Report

↓

Dashboard

---

## Design Principles

- Modular Architecture
- Loose Coupling
- High Cohesion
- API First Design
- Scalable Services
- Reusable Components
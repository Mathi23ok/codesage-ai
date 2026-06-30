# Low-Level Design (LLD)

## Backend Modules

### Authentication Module
- User Login
- JWT Authentication

### Repository Module
- Upload Repository
- Validate Repository
- Extract Files

### Analysis Module
- AST Parsing
- Dependency Analysis
- Feature Detection

### AI Module
- Prompt Management
- OpenAI Integration
- Response Validation

### Testing Module
- Test Strategy
- Test Generation
- Test Execution

### Security Module
- Bandit Scan
- Semgrep Scan

### Report Module
- Report Generation
- PDF Export

---

## Database Tables

- Users
- Repositories
- Files
- Features
- TestCases
- Reports
- AnalysisHistory

---

## API Endpoints

- /auth
- /repository
- /analysis
- /ai
- /testing
- /security
- /report

---

## Folder Structure

backend/
- app/
- api/
- core/
- db/
- models/
- schemas/
- services/
- repositories/
- prompts/
- validators/
- utils/
- tests/

---

## Design Principles

- Single Responsibility Principle
- Dependency Injection
- Repository Pattern
- Service Layer Pattern
- Clean Architecture
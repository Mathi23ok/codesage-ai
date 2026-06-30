# Database Design

## Database

PostgreSQL

---

## Tables

### Users
- id
- name
- email
- password_hash
- created_at

### Repositories
- id
- user_id
- name
- description
- language
- uploaded_at

### Files
- id
- repository_id
- file_name
- file_path
- file_type

### Features
- id
- repository_id
- feature_name
- confidence_score

### TestCases
- id
- repository_id
- feature_id
- test_name
- test_type
- status

### SecurityReports
- id
- repository_id
- tool
- severity
- description

### AnalysisReports
- id
- repository_id
- overall_score
- coverage
- maintainability
- generated_at

---

## Relationships

- One User → Many Repositories
- One Repository → Many Files
- One Repository → Many Features
- One Repository → Many TestCases
- One Repository → Many SecurityReports
- One Repository → One AnalysisReport

---

## Indexes

- user_id
- repository_id
- feature_name
- file_path

---

## Future Enhancements

- Repository Knowledge Base
- Analysis History
- Version Comparison
- AI Conversation History
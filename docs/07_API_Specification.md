# API Specification

## Base URL

/api/v1

---

# Authentication

## POST /auth/login

Description:
Authenticate user.

Response:
- JWT Token
- User Details

---

# Repository

## POST /repository/upload

Description:
Upload Python repository.

## GET /repository/{id}

Description:
Get repository details.

## DELETE /repository/{id}

Description:
Delete repository.

---

# Analysis

## POST /analysis/start/{repository_id}

Description:
Start repository analysis.

## GET /analysis/{repository_id}

Description:
Get analysis status and results.

---

# AI

## POST /ai/analyze/{repository_id}

Description:
Generate AI insights.

## POST /ai/chat/{repository_id}

Description:
Ask questions about the repository.

---

# Testing

## POST /testing/generate/{repository_id}

Description:
Generate test cases.

## POST /testing/run/{repository_id}

Description:
Execute generated tests.

## GET /testing/results/{repository_id}

Description:
View test results.

---

# Security

## POST /security/scan/{repository_id}

Description:
Run security analysis.

## GET /security/report/{repository_id}

Description:
View security report.

---

# Reports

## GET /report/{repository_id}

Description:
Generate engineering report.

## GET /report/pdf/{repository_id}

Description:
Download PDF report.

---

# Health Check

## GET /health

Description:
Check backend status.
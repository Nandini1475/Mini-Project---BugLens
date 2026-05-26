BugLens – GitHub Bug Pattern Analyzer

BugLens is a Flask-based web application that fetches GitHub repository issues, classifies bug types, predicts risk levels, and visualizes bug analytics using interactive charts and graphs.

---

Features

- Fetch GitHub issues dynamically using GitHub REST API
- Analyze large repositories with pagination
- Bug classification:
  - UI Bug
  - Functional Bug
  - Security Bug
  - API Bug
  - Database Bug
  - Performance Bug
  - Network Bug
  - Logic Bug
  - Memory Bug
  - Compatibility Bug
- Risk prediction:
  - High
  - Medium
  - Low
- Interactive charts and graphs using Chart.js
- SQLite database integration
- Duplicate issue filtering
- Retry and timeout handling

---

Technologies Used

# Frontend
- HTML
- CSS
- JavaScript
- Chart.js

# Backend
- Python
- Flask

# Database
- SQLite

# API
- GitHub REST API

---

## Project Architecture

Frontend → Flask Backend → GitHub API → SQLite Database → Visualization Dashboard

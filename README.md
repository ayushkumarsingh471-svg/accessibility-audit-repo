# Accessibility Baseline & Repository Architecture Audit

## 📌 Project Overview
This repository contains the foundational architecture and an accessibility audit report for a public service website (Target: `bihar.gov.in`). The goal of this project is to reverse-engineer the findings into a maintainable, fully accessible full-stack project skeleton.

## 🏗️ Architecture Boundaries
This project follows a strict Monorepo structure to separate concerns effectively:
*   **`/client`**: Contains the frontend application code (e.g., React/Vite). Responsible for accessible UI components, state management, and client-side routing.
*   **`/server`**: Contains the backend API code (e.g., Node.js/Express). Handles business logic, database connections, and secure data processing.
*   **`/docs`**: Stores project documentation, accessibility audit CSVs, architecture diagrams, and Lighthouse evidence screenshots.
*   **`/test`**: Houses end-to-end (E2E) and integration tests to ensure accessibility and functionality are not broken in future updates.

## 🚀 Local Setup Instructions
To set up this project locally, run the following commands:

```bash
# Clone the repository
git clone <YOUR_GITHUB_REPO_URL>
cd accessibility-audit-repo

# (Future implementation) Install Client Dependencies
cd client
npm install

# (Future implementation) Install Server Dependencies
cd ../server
npm install
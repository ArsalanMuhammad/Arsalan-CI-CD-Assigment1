# Arsalan-CI-CD-Assigment1

# Multi-Branch CI/CD Demo

## Branch Workflow

- **main (push)** → Production deploy
- **dev (push)** → QA deploy
- **pull_request** → CI only (lint + test)

## Scripts

- `npm run lint` → Lint code
- `npm run test` → Run tests
- `npm run build` → Create build artifact

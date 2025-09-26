# 🙌 Contributing to Pet Care Management System

Thank you for your interest in contributing! This document outlines how to set up the project, propose changes, and submit contributions effectively.

## 📦 Project Setup

1. Fork the repository
2. Clone your fork
```bash
git clone https://github.com/<your-username>/pet-care-management-system.git
cd pet-care-management-system
```
3. Create a feature branch
```bash
git checkout -b feature/short-descriptor
```
4. Install dependencies (root + apps)
```bash
npm install
cd backend && npm install && cd ..
cd frontend && npm install && cd ..
cd docterInterface && npm install && cd ..
```
5. Run locally
```bash
# terminal 1
cd backend && npm run dev
# terminal 2
cd frontend && npm run dev
# terminal 3
cd docterInterface && npm run dev
```

## 📝 Commit Convention

- Use conventional commits
  - feat: add new feature
  - fix: bug fix
  - docs: documentation only changes
  - refactor: code change that neither fixes a bug nor adds a feature
  - perf: performance improvement
  - test: add or fix tests
  - chore: tooling/config updates

Example:
```
feat(adoption): add home visit scheduler to coordinator dashboard
```

## 🔀 Branching Strategy

- main: production-ready
- feature/*: new features
- fix/*: bug fixes
- docs/*: documentation updates

## ✅ Pull Request Checklist

- Code builds and runs locally
- Lint passes (if configured)
- Adds/updates tests where appropriate
- Updates docs/README if behavior changes
- Includes screenshots/GIFs for UI changes
- Links related issues (e.g., Closes #123)

## 🧪 Testing Guidance

- Prefer small, focused changes
- Cover critical flows: authentication, appointments, adoption, checkout

## 🛡️ Security & Data

- Never commit secrets (.env, API keys)
- Validate and sanitize all inputs
- Follow least-privilege principle for roles

## 📂 Monorepo Notes

- Backend (Express/MongoDB): `backend/`
- Pet Owner Portal (React): `frontend/`
- Professional Portal (React): `docterInterface/`

## 💬 Communication

- Use GitHub Issues and Discussions
- For significant changes, open an issue first to discuss

## 🤝 Code of Conduct

Please follow our CODE_OF_CONDUCT.md when participating in this project.

Thanks again for contributing! 🐾

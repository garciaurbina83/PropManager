# PropManager Development Guide

## Project Overview
Property management application focused on simplicity and correctness, with potential for future scalability.

## Technology Stack

### Backend
- Python
- FastAPI
- PostgreSQL (Docker)
- SQLAlchemy
- Alembic (Migrations)

### Frontend
- React + TypeScript
- Chakra UI
- React Query (Recommended for state management)
- React Router (Navigation)
- i18next (Internationalization)

## Project Structure

### Frontend Structure
```
frontend/
├── src/
│   ├── pages/
│   │   ├── landing.tsx
│   │   └── dashboard/
│   │       └── page.tsx
│   ├── components/
│   │   ├── layout/
│   │   │   ├── Sidebar
│   │   │   ├── Header
│   │   │   └── Layout
│   │   └── shared/
│   │       ├── Charts
│   │       ├── StatsCards
│   │       ├── Lists
│   │       └── DataTables
│   └── i18n/
```

### Backend Structure
```
backend/
├── app/
│   ├── api/
│   ├── core/
│   ├── models/
│   └── schemas/
├── alembic/
└── tests/
```

## Development Guidelines

### General Requirements
- [ ] Language: English (UI/Code)
- [ ] Spanish translation support
- [ ] Date format: MM-DD-YYYY
- [ ] Code comments in Spanish
- [ ] Consistent design across components
- [ ] No authentication required initially

### Frontend Pages (Priority Order)
- [ ] Landing Page
- [ ] Dashboard
- [ ] Properties
- [ ] Tenants
- [ ] Expenses
- [ ] Payments
- [ ] Loans

### Components to Implement
- [ ] Layout Components
  - [ ] Sidebar
  - [ ] Header
  - [ ] Main Layout
- [ ] Shared Components
  - [ ] Charts
  - [ ] Stats Cards
  - [ ] Lists
  - [ ] Data Tables

### Backend Tasks
- [ ] Database Setup (Docker)
- [ ] Initial Migration Implementation
- [ ] API Endpoints Structure
- [ ] Models Definition
- [ ] CRUD Operations

### Database
- [ ] PostgreSQL in Docker
- [ ] Migration Management
- [ ] Data Models Implementation

### Version Control (GitHub)
- [ ] Repository Setup
- [ ] Branch Strategy
  - `main`: Production-ready code
  - `develop`: Development branch
  - Feature branches: `feature/feature-name`
  - Hotfix branches: `hotfix/fix-description`
- [ ] Pull Request Template
- [ ] Commit Message Convention

### Development Workflow
1. [ ] Setup Development Environment
2. [ ] Initialize Project Structure
3. [ ] Implement Basic Frontend Layout
4. [ ] Setup Backend Base Structure
5. [ ] Database Integration
6. [ ] Feature Implementation
7. [ ] Testing
8. [ ] Documentation

### Notes
- Backend will be manually executed
- Frontend will be manually executed
- Database runs in Docker
- Focus on maintainable and clean code
- Consistent styling across components
- Scalable architecture for future enhancements

## Progress Tracking
- See `frontend/PROGRESS.md` for frontend development progress
- See `backend/PROGRESS.md` for backend development progress

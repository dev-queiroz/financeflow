# FinanceFlow

Personal Finance Manager with AI-powered insights, smart budgeting, and beautiful visualizations.

Built as a fullstack portfolio project to demonstrate modern development practices, clean architecture, scalability, and excellent code quality.

## Features

- Complete authentication and authorization with Clerk (RBAC support)
- Transaction management with categories, tags, recurrence, and attachments
- Smart monthly budgets with real-time alerts
- Rich dashboard with interactive charts and financial evolution
- AI insights and savings suggestions (Gemini integration)
- Goals and financial planning
- Export reports to PDF and CSV
- Fully responsive with WCAG AA accessibility

## Tech Stack

**Backend**  
NestJS 10 + TypeScript + Prisma ORM + PostgreSQL (Neon) + Redis + BullMQ + Sentry + Rate Limiting

**Frontend**  
React 19 + Vite + TypeScript + shadcn/ui + Tailwind CSS + TanStack Query + Zustand

**DevOps & Testing**  
Docker + GitHub Actions (CI/CD) + Vitest + Testing Library + Playwright + Sentry

## Quick Start (Local Development)

```bash
# Clone the repository
git clone https://github.com/yourusername/financeflow.git
cd financeflow

# Backend
cd backend
cp .env.example .env
npm install
npm run prisma:generate
npm run dev

# Frontend (new terminal)
cd ../frontend
cp .env.example .env.local
npm install
npm run dev
```

## Project Status
This is the first project of a strong portfolio series.
**Current Phase:** Repository setup and architecture definition.

---

## Roadmap
- [ ] Repository structure and professional README
- [ ] Backend foundation (Auth + Core modules)
- [ ] Frontend with Design System
- [ ] Complete test coverage and E2E
- [ ] Docker + CI/CD pipelines
- [ ] Production deployment

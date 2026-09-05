# Capacity Connect — IMD React/Tailwind Demo

Frontend-only Ideathon prototype for a specialized Learning Management & Competency Intelligence Portal for the India Meteorological Department (IMD).

## Stack
- React + Vite
- Tailwind CSS
- Recharts
- Lucide React
- Node.js (development/build tooling)
- Planned production backend: Python/FastAPI + PostgreSQL + Scikit-learn
- Planned security/infra: JWT/RBAC + Nginx

## Demo routes
- `/` Landing page
- `/login` Login / SSO placeholder
- `/dashboard` Trainee dashboard
- `/learning` My Learning
- `/recommended` Personalized recommendations
- `/assessment` Assessment
- `/certificate` Certificates
- `/profile` Profile
- `/feedback` Feedback
- `/trainer` Trainer Studio / AI MCQ generator
- `/admin` Admin analytics
- `/heatmap` Competency heatmap
- `/optimization` Load optimization & platform health
- `/users` User management / RBAC demo

## Run
```bash
npm install
npm run dev
```

This is intentionally a frontend dummy/demo. API, database, ML recommendation service, authentication, and Nginx are represented in the UI as planned architecture rather than connected services.


V3 updates: trainer-specific My Courses workspace, per-course management pages, trainer assessment management, typeable global search bar, and improved interactive controls.

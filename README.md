# A-Plan AI Tutor

A production-ready SaaS for O-Level, A-Level, and SAT students.

## Features
- **AI Tutor**: Voice and text-based AI tutoring (OpenAI powered).
- **Study Planner**: Track courses, topics, and progress.
- **Authentication**: Secure email/password login.
- **Interactive UI**: React-based dashboard, responsive design.

## Setup

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Database Setup**:
   Ensure PostgreSQL is available.
   ```bash
   npm run db:push
   ```

3. **Environment Variables**:
   - `DATABASE_URL`: PostgreSQL connection string.
   - `SESSION_SECRET`: Secret for session cookies.
   - `AI_INTEGRATIONS_OPENAI_API_KEY`: Managed by Replit AI Integrations.

4. **Run Development**:
   ```bash
   npm run dev
   ```

5. **Run Production**:
   ```bash
   npm run build
   npm start
   ```

## Deployment
Includes `render.yaml` for deployment on Render.

## Tech Stack
- Frontend: React, Vite, TailwindCSS, Shadcn UI
- Backend: Node.js, Express, Drizzle ORM
- Database: PostgreSQL
- AI: OpenAI (GPT-4o, GPT-Audio)

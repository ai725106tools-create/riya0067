# Focus Flow — MVP

Personalized AI study planner — minimal MVP.

Quick start
1. Clone the repo (or copy files into a folder).
2. Install:
   npm install
3. Prisma (dev SQLite):
   npx prisma generate
   npx prisma migrate dev --name init
4. Seed demo data:
   npm run seed
5. Add ambient audio:
   put a rain-loop.mp3 in public/sounds/
6. Run:
   npm run dev
7. Open:
   http://localhost:3000

Notes
- This is an MVP scaffold. Scheduler and API routes are simple but functional.
- Replace public/sounds/rain-loop.mp3 with a Creative Commons ambient MP3.
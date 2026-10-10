# Obscura — Build Log 🌑

> Privacy-first analytics. Watch everything. Remember no one.

## Day 1-2: Foundation ✅

**Stack:** Next.js 15 · TypeScript · Tailwind · Prisma 6 · PostgreSQL (Neon) · Auth.js (coming)

- [x] Set up dev environment: Node, Git, VS Code
- [x] Scaffolded Next.js + TypeScript + Tailwind project
- [x] Deployed to GitHub, connected Neon Postgres (Singapore)
- [x] Designed User + Site schema in Prisma
- [x] Verified tables live via Prisma Studio 🎉

**Debugged along the way:**

- `.env` variable naming (the missing `DATABASE_URL=` prefix)
- Prisma v8 (RC) → v6 (stable) downgrade decision
- Missing models in schema — caught by reading the actual file 🕵️

**Next up:** ⚔️ Authentication (Auth.js) — Week 1 final boss

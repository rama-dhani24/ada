# Ada projects

This workspace contains the Ada backend API, Flutter parent app, school dashboard, and admin operations console. Start services and connect clients with the [local connection guide](CONNECTING.md).

- **Backend API (Fastify + Prisma):** [backend](backend/README.md)
- **School dashboard (Next.js + TypeScript):** [dashboard](dashboard/README.md)
- **Admin console (Vite + React + TypeScript):** [admin](admin/README.md)
- **Parent app (Flutter):** [mobile](mobile/README.md)

Local ports: API `3001`, dashboard `3000`, admin `3002`, PostgreSQL `5433`, Redis `6379`. Both browser apps proxy API requests through their own dev server. The Android emulator uses `10.0.2.2` to reach the host API.

On Windows PowerShell, use `npm.cmd` / `npx.cmd` to avoid execution policy errors.

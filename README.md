# CAMX Frontend

Next.js 16 / React 19 / TypeScript frontend for the CAMX e-commerce application.

## Technology

Next.js, Tailwind CSS, Axios, Next Themes, Recharts, document preview utilities and related UI packages.

## Local development

```bash
npm install
npm run dev
```

Open http://localhost:3000. Available checks: `npm run build`, `npm run lint`.

## Related code

- [CAMX backend](https://github.com/Kelumsameera/camx-backend)
- [CAMX web experience](https://github.com/Kelumsameera/camx-lk)
- [Other CAMX frontend](https://github.com/Kelumsameera/camx_frontend)

Two CAMX frontend repositories currently exist with similar architecture and different dependency sets. Do not delete, redirect or archive either repository until you confirm which version is connected to active deployment.

## Before production

Verify API connection, admin access, authentication, orders, responsive pages and document previews. Keep private tokens in server-side configuration. Run lint and build and review permission enforcement in the backend.

This README documents the codebase, not a verified production deployment.

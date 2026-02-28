# Setup

## Prerequisites

- Node.js 18+
- npm 9+

## Environment variables

Copy `.env.example` to `.env.local`.

| Variable | Required | Purpose |
|---|---|---|
| `NEXT_PUBLIC_SITE_URL` | Yes | Canonical URL for metadata/social tags |
| `NEXT_PUBLIC_GA_ID` | Optional | Google Analytics tracking |
| `NEXT_PUBLIC_FB_PIXEL_ID` | Optional | Facebook Pixel tracking |

## Install and run

```bash
npm install
npm run dev
```

## Build and validate

```bash
npm run build
npm run typecheck
npm run lint
```

## Deploy

```bash
vercel --prod
```

Ensure production env vars are configured before deployment.

# Architecture

## Overview

This is a Next.js App Router site with route-based content pages and reusable presentation components tailored for a local service business.

## Main areas

- `app/`: route pages (`/`, `/services`, `/faq`, `/gallery`, contact flows) and metadata.
- `components/`: reusable conversion, trust, and content blocks.
- `data/`: structured page content and messaging inputs.
- `public/`: optimized service imagery and static assets.

## Request/content flow

1. Route loads page-level content and metadata.
2. Shared components render reusable conversion blocks.
3. CTA paths direct users toward call/contact actions.
4. SEO metadata and structured route hierarchy support discoverability.

## Deployment topology

- Frontend deploys on Vercel.
- Static media is served from `public/` with optimized formats.
- Analytics IDs are injected through environment variables.

## Design priorities

- Mobile readability and quick scanning
- Fast first load and stable layout
- Clear conversion paths (call, message, booking intent)

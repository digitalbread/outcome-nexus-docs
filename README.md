<p align="center">
  <img src="assets/Outcome_Nexus_Logo_Facebook.png" alt="Outcome Nexus" width="600" />
</p>

# Outcome Nexus - Documentation

Documentation repository for the **Outcome Nexus** platform — a SaaS application for non-profits and organizations to manage events, volunteers, and measure impact.

## About Outcome Nexus

Everything a non-profit does is an "outreach opportunity" that can be organized as an event with pre/during/post phases, tasks, and measurable outcomes. Outcome Nexus transforms how organizations track their outreach efforts from inception to impact, providing tools for event management, volunteer coordination, fundraising, and comprehensive reporting for grants.

?? **Website:** [outcomenexus.com](https://outcomenexus.com)
?? **App:** [app.outcomenexus.com](https://app.outcomenexus.com)

## Platform Architecture

| Application | Purpose | URL |
|---|---|---|
| Marketing Site | Public-facing website | outcomenexus.com |
| Admin Dashboard | Organization management | app.outcomenexus.com |
| Mobile App | Event participation & content capture | iOS & Android |

## Tech Stack

- **Frontend:** Next.js 16, React 19, Tailwind CSS
- **Mobile:** React Native with Expo
- **Backend:** Supabase (PostgreSQL, Auth, Realtime)
- **Storage:** AWS S3 + CloudFront
- **SMS:** Twilio (mobile OTP authentication)
- **Monorepo:** Turborepo with pnpm
- **Deployment:** Vercel
- **Repository:** (PRIVATE) [github.com/digitalbread/outcome-nexus](https://github.com/digitalbread/outcome-nexus)

## Documentation Index

> ?? *Detailed documentation coming soon. This repo will be expanded with guides covering setup, architecture, API reference, and contributor docs.*

- **Project Overview** — Platform vision, user types, and core concepts
- **Architecture** — Monorepo structure, database schema, authentication strategy
- **Setup Guide** — Local development environment setup
- **Database** — Schema documentation (43 tables), migrations, RLS policies
- **Authentication** — Web (Supabase Auth) and Mobile (Twilio SMS OTP) flows
- **Deployment** — Vercel configuration for marketing site and admin dashboard
- **Fundraising** — Calendar fundraisers and campaign contact system
- **API Reference** — Shared types, API client, and service documentation

## Core Concepts

- **Outreach Opportunity** — Any activity an organization undertakes (meetings, competitions, workshops, fundraisers)
- **Event** — The core unit of the platform with title, description, venue, date/time, assigned teams, and task lists
- **Event Phases** — Pre-event (preparation), During-event (content capture), Post-event (debrief & reporting)
- **Impact Tracking** — Metrics, media, attendance, and outcomes captured during events for grant reporting and fundraising

## User Types

1. **Founder/Superadmin** — Platform-wide administration
2. **Organization Admin** — Manages org settings, billing, teams, and events
3. **Team Admin/Lead** — Manages specific teams and creates team events
4. **Team Member/Volunteer** — Participates in events, completes tasks, uploads content

## License

Proprietary — All rights reserved.
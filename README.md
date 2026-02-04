# VOLTRIX – Esports Production Platform

VOLTRIX is a multi-tenant esports production and tournament management platform inspired by professional PUBG MOBILE tournaments.

The platform focuses on real-world esports workflows including tournament setup, live match control, results processing, and broadcast-ready production tools.

## Key Features
- Multi-tenant architecture (organizations, tournaments, matches)
- Role-based access control (Super Admin, Admin, Organizer)
- Real-time match control using WebSockets
- Automated and manual result pipelines
- Live dashboards for match control and results
- OBS-ready overlays for live broadcasts
- Multi-game ready architecture (PUBG Mobile, Free Fire – planned)

## Tech Stack
**Backend**
- Node.js
- NestJS
- PostgreSQL
- Prisma ORM
- WebSockets (Socket.IO)

**Frontend**
- Next.js
- React
- Tailwind CSS

## Architecture Overview
VOLTRIX is designed with a modular architecture:
- Authentication & RBAC
- Tournament and match domain
- Live match control layer
- Result processing pipeline
- Export and overlay layer

The system is built to support both automatic data ingestion and manual fallback workflows.

## Project Status
This project is under active development and is used as a real-world learning and production platform.

## Author
Md Mohoshin Sheikh  
Full-Stack Developer | Esports Platform Engineer

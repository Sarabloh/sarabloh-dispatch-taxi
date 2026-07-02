# Sarabloh Dispatch Taxi

Real-time taxi dispatch and delivery platform.

## Overview
Full-stack web application enabling customers to request rides/deliveries and drivers to accept and complete jobs in real-time. Built with React, TypeScript, Node.js, Express, and PostgreSQL.

## Features
- Real-time dispatch and driver location tracking (Socket.io)
- Customer booking interface
- Driver app for job acceptance
- Admin panel for management
- SMS integration (Twilio)
- Payment processing
- Geolocation (Google Maps)

## Tech Stack
**Frontend:** React 18+, TypeScript, Tailwind CSS, Socket.io Client
**Backend:** Node.js, Express, PostgreSQL with Drizzle ORM, Socket.io, Twilio SDK
**Infrastructure:** Docker containerization, Canadian cloud hosting

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Twilio account
- Google Maps API key

### Installation
```bash
git clone https://github.com/Sarabloh/sarabloh-dispatch-taxi.git
cd sarabloh-dispatch-taxi
npm install
cd backend && npm install && cd ../frontend && npm install
cp .env.example .env
```

### Running Locally
```bash
# Terminal 1: Backend
cd backend && npm run dev

# Terminal 2: Frontend
cd frontend && npm run dev
```

## Database
```bash
npm run migrate
npm run seed
```

## Deployment
See [DEPLOYMENT.md](./docs/DEPLOYMENT.md)

## API Documentation
See [API.md](./docs/API.md)

## Architecture
See [ARCHITECTURE.md](./docs/ARCHITECTURE.md)

## License
MIT - See [LICENSE](./LICENSE)

---

**Sarabloh Technologies Ltd.**  

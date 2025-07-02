# Orchestra Rehearsal Webapp

A web app to automate scheduling, attendance, reminders, and calendar integration for orchestras and ensembles. Responsive for mobile and desktop.

## Features
- Create/manage rehearsal events
- RSVP/attendance tracking
- Automated reminders (email/SMS)
- Calendar sync (Google, iCal, Outlook)
- User roles (admin, conductor, musician)
- Materials upload/share

## Stack
- Frontend: React + Tailwind CSS
- Backend: Node.js (Express)
- Database: PostgreSQL

## Setup
- Clone repository and install dependencies (npm install)
- Set up a .env with DB and calendar/twilio credentials
- Run database migrations (see /migrations)
- Start backend (npm run server)
- Start frontend (npm run client)

## Deployment
- Use Vercel for frontend, Render/Heroku for backend

## Security
- Data encrypted in transit and at rest
- JWT auth for all endpoints

## Integration
- Google Calendar, iCal, Outlook support

----

This project is part of the music industry web app automation series. Project plan in Google Docs.

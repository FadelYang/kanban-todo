# Simple Kanban Todo
This repository contain submodule of frontend and backend repository a project called "Simple Kanban Todo"
## Backend
The backend service build with NodeJS + ExpressJS + Prisma ORM + PostgreSQL Database
### How to Install
- Go to "be" submodule
- clone the repository
- run `npm install` for installing package and dependencies
- run `npm run dev` for running it locally
### Database Setup
- create .env file
- add DATABASE_URL variable and fill it with postgresql database
- run `npx prisma generate`
- run `npx prisma migrate dev` for run migration
## Frontend
The fronted app build with ReactJS + Vite + TailwindCSS
### How to Install
- Go to "fe" submodule
- clone the repository
- run `npm install` for installing package and dependencies
- run `npm run dev` for running it locally
### Backend Service Setup
- create .env file
- add VITE_BACKEND_URL variable and fill it with backend service url (eg: localhost:3000)


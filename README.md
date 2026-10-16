# Student Project Tracker

A web application to manage and track electronics project ideas and their progress.

## Live Demo
https://student-project-tracker-live-swart.vercel.app

## GitHub Repository
https://github.com/shalinikonanki2k07-crypto/student-project-tracker-live

## Features
- Add new projects
- View the project list
- Edit project details
- Delete projects
- Store project data in a Supabase PostgreSQL database
- Deploy the application using Vercel

## Technologies Used
- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- Supabase PostgreSQL
- Vercel
- Git and GitHub

## Database Setup
The database schema is provided in `schema.sql`. Configure the `DATABASE_URL` environment variable using your Supabase Transaction Pooler connection string.

**Security:** Never commit `.env` or expose database credentials in source code.

## Deployment
The application is deployed on Vercel and connected to Supabase for persistent data storage.

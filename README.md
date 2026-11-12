# SkyBook – Flight Booking Management System

A flight-booking application project with two frontend implementations and a Java/Spring Boot backend configuration starter.

## Repository structure

- `frontend-demo/` – feature-rich frontend with flight search, authentication screens, seat selection, passenger workflow, dashboards and a local demo data layer.
- `frontend-modular/` – modular React frontend foundation with authentication/API integration structure.
- `backend-config/` – Maven project configuration (`pom.xml`). Backend source code and database integration are not included in this upload.

## Important implementation notes

- The demo frontend uses browser `localStorage` and simulated flows; it is not a production booking or payment system.
- The modular frontend contains integration foundations and placeholder modules.
- No live airline API, payment gateway, or verified persistent MySQL backend is included in this repository.
- Any sample login credentials in the demo are for local demonstration only. Do not reuse them in a real system.

## Frontend setup

Open the relevant frontend folder and install its dependencies with `npm install`. Start the development server using `npm run dev` if the package scripts provide it.

## Backend configuration

The Maven `pom.xml` is included as a configuration starter. Add the actual Spring Boot source code, application configuration, and database schema before treating the backend as complete.

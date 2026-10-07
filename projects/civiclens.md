# CivicLens

[Source repository](https://github.com/anvirekap/CivicLens)

Community issue reporting dashboard built for WarriorHacks 2.0.

## Implemented features

- Guided report creation with map-based coordinates.
- Keyword and rule-based category and priority classification.
- Leaflet map using OpenStreetMap tiles.
- Community confirmations, limited to once per browser session.
- Urgency ranking using priority and confirmation counts.
- Dashboard counts for active, high-priority, confirmed, and resolved reports.
- REST endpoints for reports, confirmations, classification, and status updates.

## Stack

Python, FastAPI, SQLAlchemy, Pydantic, SQLite for local storage; React, TypeScript, Vite, and Leaflet. The source also includes Render deployment configuration and support for a production PostgreSQL connection.

## Run it

Use the setup and deployment instructions in the [source README](https://github.com/anvirekap/CivicLens#readme).

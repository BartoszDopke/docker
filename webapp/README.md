# Full-Stack Web App with Docker Compose

Build a simple "To-Do" application comprising a React frontend, a Node.js/Express backend, and a PostgreSQL database, all orchestrated via Docker Compose.

## Key Deliverables

- `Dockerfile` for frontend and backend
- `compose.yaml` defining three services plus a network
- Environment variable management with a .env file
- Volume mounting for persistent database storage

Learning Outcomes: Service isolation, multi-container networking, data persistence, environment configuration.

## Run

`docker compose up`

## Tear down

`docker compose down --volumes mysql-data`
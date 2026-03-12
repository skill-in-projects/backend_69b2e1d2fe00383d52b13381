# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2e1d2fe00383d52b13381_user:3toK9kxy5gbRF8HmZQ%5Ec%23M4FLDKW9%2ADc@ep-long-wind-adhd6yzp.c-2.us-east-1.aws.neon.tech:5432/AppDB_69b2e1d2fe00383d52b13381?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.

# LibreCrawl

Flask-based SEO spider (Python 3.11, Waitress, Playwright, SQLite in `data/users.db`).

## Railway

- Project name: LibreCrawl
- Project ID: `b61b2d96-e72c-409d-a26a-47fceeba1d4f`
- Config: `railway.json` (Dockerfile builder, healthcheck `/login`)
- Required service variables: `PORT=5000`, `SECRET_KEY`, `RAILWAY_RUN_UID=0`
- Volume mount: `/app/data`

Language: Python 3.12.10 .

Web framework: FastAPI (lightweight, async, great for APIs).

Server: Uvicorn for local dev.

Memory: SQLite (file) for prototype or Redis for scale .

Storage for logs / telemetry: plain file logs (later switch to structured logging).

Packaging / env: venv + pip .

Testing: pytest.

Optional later: Docker for deployment, or a small Node/React wrapper for a UI.

Start with API-key authentication (static key in dev); rotate for prod.

Only store user data you need; provide TTL for memory items.

Never log raw user-provided sensitive fields.

If you store locally, keep the DB in project folder and ignore it in Git.

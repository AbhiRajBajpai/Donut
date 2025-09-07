Language: Python 3.12.10 .

Web framework: FastAPI (lightweight, async, great for APIs).

Server: Uvicorn for local dev.

Memory: SQLite (file) for prototype or Redis for scale .

Storage for logs / telemetry: plain file logs (later switch to structured logging).

Packaging / env: venv + pip .

Testing: pytest.

Optional later: Docker for deployment, or a small Node/React wrapper for a UI.

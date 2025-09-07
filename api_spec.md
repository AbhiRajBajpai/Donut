POST /v1/message

Request JSON: { "session_id": "string", "message": "string", "user_meta": { ... } }

Response JSON: { "reply": "string", "session_id": "string", "meta": { "source": "persona_v1" } }

GET /v1/health → { "status": "ok" }

GET /v1/memory?session_id=... → returns memory keys for session

POST /v1/memory → { "session_id": "...", "key": "...", "value": "...", "ttl_seconds": 3600 }

POST /v1/plugin/<name> → call registered plugin (for future plugin system)

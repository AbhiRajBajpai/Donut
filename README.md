# Donut
My Dream Project
Donut — a small, reusable text-first assistant microservice (female persona) designed to be embedded into other projects (e.g., AGI Prototype Village). Start text-only. Provide a stable API for sending user messages and receiving persona-styled replies, with an extensible plugin/memory system.

-Provide a POST /v1/message API that returns persona-styled replies.

-Keep light-weight session memory (per-session key/value store).

-Persona layer (template-driven prompt) so voice is consistent.

-Simple plugin interface to call custom functions (e.g., query AGI simulation state).

-Basic auth (API key) and logging.

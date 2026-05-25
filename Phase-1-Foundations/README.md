## Phase 1: Local Orchestration & The Atomic Node Protocol
**Project:** "Hello World" Connectivity Protocol

**Objective:** Establish a self-hosted infrastructure and validate external service authentication.

**Technical Execution:**
* **Infrastructure:** Deployed a containerized n8n instance via Docker on WSL (Ubuntu), establishing persistent volumes and mapping port 5678 for local orchestration and data sovereignty.
* **Node Architecture:** Internalized the tripartite architecture of n8n nodes (Input payload, Configuration logic, Output JSON).
* **Authentication & Execution:** Configured Google OAuth2 credentials to establish a secure handshake. Executed a deterministic workflow utilizing a Manual Trigger and a Gmail node to dispatch a predetermined payload, validating environment integrity.

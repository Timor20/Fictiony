# Fictiony

Fictiony is an interactive story-generation application that lets users enter a theme and receive an AI‑generated branching narrative — similar to a multiple‑choice adventure novel. Each story includes several decision points and concludes with one winning ending.

---

## 🚀 Features

* Generate fully AI‑driven interactive stories based on a custom theme
* Multiple branching choices at each step
* One definitive winning ending per story
* Session-based experience (no authentication required)
* Modern, fast, and lightweight full‑stack architecture

---

## 🧠 Tech Stack

### **Backend**

* **Python** — core backend language
* **FastAPI** — high‑performance API framework
* **PostgreSQL** — primary database
* **SQLite** — optional local development database
* **Pydantic** — data validation & serialization
* **SQLAlchemy** — ORM for database models & queries
* **psycopg2** — PostgreSQL driver
* **OpenAI API** — AI story generation
* **Uvicorn** — ASGI server
* **UV & npm** — build and dependency tooling

### **Frontend**

* **Vite** — ultra‑fast tooling & build system
* **React** — component‑based UI
* **TypeScript** — type safety
* **Axios** — API requests
* **react-router-dom** — routing & navigation

---

## 🧩 How It Works

1. User enters a **theme** (e.g., "space pirates," "enchanted forest," "detective noir").
2. Backend sends theme to the **OpenAI API**.
3. AI generates:

   * A story introduction
   * Multiple decision points
   * Several branching paths
   * One winning ending
4. The frontend renders choices using React, allowing the user to navigate the narrative.
5. Session handling is used instead of authentication, keeping the experience lightweight.

---

## 📜 License

MIT — free to use and modify.
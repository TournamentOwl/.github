# Debate Tournament Webapp
Organize debate tournaments with realtime scoring.




# Tournament App Architecture
## Services Breakdown

| Service                | Technology                               | Purpose                                                                 |
|------------------------|------------------------------------------|-------------------------------------------------------------------------|
| **Frontend**            | React / Vite                          | UI for tournament registration, real-time updates, and user interaction. |
| **Backend (Django API)**| Django, Django REST Framework (DRF)      | User authentication, tournament management, data persistence.           |
| **Authentication Database**       | PostgreSQL / SQLite                      | Secure user authentication and role management.                        |
| **Tournament Database**       | PostgreSQL / SQLite                      | Store tournament-related data (brackets, rounds, scores).               |

---

# Candidate-Dashboard-Portal
I built a candidate review dashboard designed to solve a common problem in talent acquisition: the gap between static data and actual hiring decisions. Rather than just displaying a list of names, I engineered a decision-driven interface that simulates the high-pressure workflow of a real-world recruiter
---

Key Features

Candidate Management

- Search candidates by name
- Filter by assignment, video, and ATS scores
- Sort dynamically by priority and performance

Evaluation System

- Assignment evaluation (UI quality, state handling, accessibility)
- Video evaluation (clarity, confidence, communication)
- Editable candidate scores with real-time updates

Priority Engine

Candidates are ranked using a weighted scoring system:

- Assignment: 30%
- Video: 25%
- ATS: 20%
- GitHub: 15%
- Communication: 10%

Priority levels:

- P0 → Interview immediately
- P1 → Strong shortlist
- P2 → Review later
- P3 → Reject

Explainable Decisions

Each candidate includes reasoning behind their priority:

- Example: “Strong assignment, clear communication”

Comparison Mode

- Compare up to 3 candidates side-by-side
- Helps in faster decision-making

Analytics Dashboard

- Visual breakdown of candidate distribution by priority
- Highlights hiring trends

Persistence

- Data is stored in localStorage
- Changes persist across sessions

---

Tech Stack

- React (Vite)
- Zustand (state management)
- Tailwind CSS
- Recharts

---

Architecture Decisions

- Centralized state using Zustand for scalability
- Separate utility for priority logic (clean abstraction)
- Modular components for maintainability
- Real-time updates to simulate production systems

---

Setup Instructions

npm install
npm run dev

---

Future Improvements

- Backend integration (Node + DB)
- Authentication system
- Multi-user collaboration
- Advanced analytics (ML-based ranking)

---

Demo

(Attach your demo video link here)

---

Notes

This project focuses on usability, clarity, and real-world product thinking rather than just UI implementation.

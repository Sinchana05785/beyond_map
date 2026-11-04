# Beyond Maps

An AI‑powered local discovery and tourist‑local connection platform.

## Overview
Beyond Maps helps travelers find hidden gems, get personalized itineraries, and connect with verified local guides. It combines:
- Preference‑based AI recommendation engine
- Hidden‑Gem scoring
- Real‑time travel intelligence (weather, traffic, crowd)
- Secure matching marketplace with SOS & trust features

## Quick Start
1. **Clone the repo**
   ```bash
   git clone <repo‑url>
   cd beyond-maps
   ```
2. **Frontend** – built with React + Vite
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
3. **Backend** – FastAPI (Python)
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate   # on Windows: venv\Scripts\activate
   pip install -r requirements.txt
   uvicorn app:app --reload
   ```
4. **Databases** – MySQL & Redis (Docker‑compose provided)
   ```bash
   docker-compose up -d mysql redis
   ```

## License
MIT

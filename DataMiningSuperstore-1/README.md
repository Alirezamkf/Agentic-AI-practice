# DataMiningSuperstore

A learning project for a Superstore Business Intelligence dashboard.

## Current status

The project currently contains a minimal React + TypeScript + Vite frontend and a minimal FastAPI backend. Dashboard components, analytics, and data processing will be added incrementally later.

## Structure

- `frontend/` — React, TypeScript, and Vite application.
- `backend/` — FastAPI application and Python dependencies.
- `data/` — Original Superstore CSV dataset. It is intentionally not modified.
- `outputs/` — Reserved for generated outputs.

## Run the applications

Frontend:

```powershell
cd frontend
npm install
npm run dev
```

Backend:

```powershell
cd backend
.venv\Scripts\activate
uvicorn app.main:app --reload
```

The frontend runs at `http://localhost:5173` and the backend health endpoint is available at `http://localhost:8000/api/health`.

Docker is not required for development.

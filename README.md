# AI News Verification System

A full-stack project for checking news claims against multiple evidence sources and showing an explainable verification result. The frontend is built with React and Vite, and the backend uses FastAPI with NLP-based analysis signals.

## Project Features

- News claim input and category-based analysis.
- Evidence collection from public news and discussion sources.
- Verdict, confidence score, accuracy estimate, and supporting references.
- Interactive frontend with a 3D news-themed interface.
- FastAPI backend for text analysis and result generation.

## Folder Structure

```text
.
+-- backend/          # FastAPI backend and analysis modules
+-- docs/             # Project notes and attributions
+-- src/              # React frontend source code
+-- index.html        # Vite entry file
+-- package.json      # Frontend scripts and dependencies
`-- vite.config.ts    # Vite configuration
```

## Frontend Setup

```powershell
npm install
npm run dev
```

## Backend Setup

```powershell
cd backend
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8001
```

Keep both the frontend and backend running while testing the complete application.

## Build

```powershell
npm run build
```

## Notes

- The backend endpoint used by the frontend is `/api/analyze`.
- The local SQLite data file is kept inside `backend/data`.
- Additional project notes are available in the `docs` folder.

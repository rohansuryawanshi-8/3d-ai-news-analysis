
  # 3D AI News Analysis Frontend

  This is a code bundle for 3D AI News Analysis Frontend. The original project is available at https://www.figma.com/design/cAZPB61EW9NKqVNiss65Ts/3D-AI-News-Analysis-Frontend.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.

  ## Python analysis backend

  The Analyze News panel calls a FastAPI backend at `/api/analyze`.

  ```powershell
  cd backend
  python -m venv .venv
  .\.venv\Scripts\Activate.ps1
  pip install -r requirements.txt
  uvicorn app.main:app --reload --port 8001
  ```

  Keep the backend running alongside `npm run dev`.
  

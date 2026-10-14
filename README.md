# Hospital Appointment System — Frontend

React + Vite frontend for a full-stack hospital appointment CRUD application.

## Local setup

1. Install Node.js 20+.
2. Open a terminal in this frontend folder.
3. Run `npm install`.
4. Copy `.env.example` to `.env` (default API: `http://localhost:8080`).
5. Start the Spring Boot backend separately.
6. Run `npm run dev` and open the local URL shown.

## Deploy to Vercel

Import this frontend repository. Framework: **Vite**. Build: `npm run build`. Output: `dist`. Add environment variable `VITE_API_URL=https://YOUR-BACKEND.onrender.com` (no trailing slash). Redeploy after changing variables.

**Important:** A frontend deployment needs a reachable backend API to save/view appointments. Do not upload `node_modules`, `.env`, or `dist` to GitHub. For GitHub browser upload, extract the ZIP first and upload the project files/folders.

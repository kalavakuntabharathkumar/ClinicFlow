# ClinicFlow
MERN appointment and billing starter: React, Redux Toolkit, Express, MongoDB/Mongoose.

## Start
1. Install Node.js 18+ and run MongoDB locally.
2. In the project root: `npm install`
3. Run API: `npm run dev` (default `mongodb://127.0.0.1:27017/clinicflow`, port 5000).
4. In another terminal: `cd client && npm install && npm run dev`.
5. Open the Vite URL shown in the terminal.

Endpoints: `GET/POST /api/patients`, `GET/POST /api/appointments`, `PATCH /api/appointments/:id/status`, `GET/POST /api/invoices`, `PATCH /api/invoices/:id/pay`.

This is a functional starter, not a deployed production system. Resume metrics (records, speedups, PRs, bug counts) must be measured independently before claiming them.

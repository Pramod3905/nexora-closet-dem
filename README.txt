NEXORA CLOSET BACKEND
Requires Node.js 18+.
Local test:
  npm install
  npm start
Health check: GET /health
Listings: GET/POST /api/listings
Chat: GET/POST /api/chat
Environment:
  PORT (hosting platform normally sets this)
  ALLOWED_ORIGIN (optional frontend URL; set this for production)
  DATA_FILE (optional data file path)
Deploy as a Node web service on Render/Railway/Fly.io or another Node host.
WARNING: JSON file storage is for demo only. Many cloud hosts use ephemeral filesystems; use a persistent disk or managed database before launch. No real user authentication or payment processing is included.

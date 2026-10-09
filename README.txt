Vastu Vihar - Information & AI Assistant  (static HTML / CSS / JS version)

HOW TO RUN
  Double-click index.html. No Node, npm, database or server needed.
  (Also works on any static host: Netlify, GitHub Pages, Vercel, plain Apache/Nginx.)

FILES
  index.html          page shell
  css/style.css       all styles
  js/app.js           the application UI (compiled from the React source)
  js/api-server.js    the former Node/Express backend, now running inside the browser.
                      It answers every /api/... request locally (login, AI assistant,
                      projects, properties, GST, knowledge base, users, audit log).
  vastu_logo.png

DEMO LOGINS (same as before)
  admin@vastuvihar.org    Admin@123#Vastu
  sales@vastuvihar.org    Sales@123#Vastu
  manager@vastuvihar.org  Manager@123#Vastu

NOTES
  * Data you add (users, knowledge entries, documents, chats) is saved in this
    browser's localStorage - it is per browser/device, not shared between people.
    Clear site data to reset to the original seed data.
  * Because everything runs client-side, logins are a demo-level convenience, not real
    security. For a real multi-user deployment keep the Node backend.
  * Fonts load from Google Fonts when online; the app falls back to system fonts offline.

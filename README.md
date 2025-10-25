# encrypted-messaging-app

A small example project that serves a static frontend from a minimal Node.js server. Intended as a starter/demo repository for a messaging-style client served from a local server.

## Features
- Minimal Node.js server to serve static assets
- Simple single-page frontend in `public/`
- Lightweight, easy to extend for experimenting with messaging/encryption features

## Requirements
- Node.js (LTS recommended)
- npm (comes with Node.js)

## Installation
Open PowerShell or Command Prompt in the repository root and run:

```powershell
npm install
```

## Running the app
Start the server:

```powershell
npm start
# or
node server.js
```

By default the server serves files from the `public/` directory. Open a browser to:
http://localhost:3000
(if your server uses a different port, follow the value printed by the server on startup)

## Development
- Edit server behavior in `server.js`.
- Update frontend UI/logic in `public/index.html` and any assets under `public/`.
- Restart the server after changing server-side code (or use a watcher like nodemon).

## Project structure
- server.js — minimal Node.js server that serves static files
- public/ — static frontend assets (index.html, scripts, styles)
- package.json — project metadata and npm scripts
- .gitignore — files to exclude from version control

## Contributing
Contributions are welcome. Open an issue to discuss changes or submit a pull request with a clear description of the change and why it's needed.

## License
Add a LICENSE file to the repository to clearly state the project license.

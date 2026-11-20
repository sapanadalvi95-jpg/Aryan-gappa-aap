# Aryan App — Real AI starter

This is a mobile-friendly AI chat web app starter with a Node.js backend. It keeps the Gemini API key on the server, not in the browser.

## Run locally
1. Install Node.js 22+.
2. Extract this project.
3. In the project folder, run `npm install`.
4. Set the server secret `GEMINI_API_KEY` (do not put it in `public/` or share it).
5. Run `npm start`.
6. Open `http://localhost:3000`.

## Deploy
Deploy the project to a Node.js hosting provider that supports server-side environment variables. Add `GEMINI_API_KEY` in the host's Secrets/Environment Variables settings, then deploy. Never share your API key in chats or screenshots. Ask a parent/guardian to help with account or billing settings.

The app currently supports text chat. Image upload, speech, accounts, and persistent chat history are not implemented in this starter.

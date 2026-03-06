# Project Rules

## Client-Side Only

All tools must run entirely in the browser. No server-side code execution or data exchange is allowed. Before every git commit, verify that any new or modified HTML/JS files:

- Do not make API calls to external servers for processing data
- Do not require a backend or server to function
- Only use CDN-hosted libraries that run client-side (e.g. Chart.js, SheetJS)
- Process all data locally in the browser

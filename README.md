# gcdRadar: the newest sweep

This branch holds one commit: the files the home page and the live board redraw from between site rebuilds.
The collector replaces it after every sweep (`collector/live.ts` on `main`), so it has no history and is never merged.
The Cloudflare Worker serves the files at `/v1/live/<name>`. `vercel.json` keeps Vercel from deploying this branch.

# Contributing / Branch Rules

- `main` is **live production** — it's what's deployed to poolrescue911.vercel.app.
- `dev` is the working branch for in-progress changes.
- **Never commit directly to `main`.**
- Workflow: create a feature branch off `dev` → make changes → test → merge into `dev` → when ready, merge `dev` into `main`.
- Never commit API keys, passwords, or other secrets to the repo. Use environment variables or Apps Script Script Properties instead.

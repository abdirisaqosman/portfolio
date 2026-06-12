# Portfolio

Landing page for **Abdirisaq Osman** — fullstack & DevOps engineer.

A single static page (no build step) listing selected work and stack.
Live via GitHub Pages.

## Selected work

| Project | What it is | Repo |
|---------|------------|------|
| **Pulse** | Self-hosted uptime monitor — Fastify API + worker + React dashboard on Kubernetes (kind), fronted by Cloudflare. | [abdirisaqosman/pulse](https://github.com/abdirisaqosman/pulse) |
| **LeadScout** | Local-business lead finder — pluggable scrapers → background jobs → Postgres → FastAPI → React. | [abdirisaqosman/leadscout](https://github.com/abdirisaqosman/leadscout) |

## Run locally

It's plain HTML/CSS — open `index.html`, or serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Served from the `main` branch root via GitHub Pages.

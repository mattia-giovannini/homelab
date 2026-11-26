# homelab

Static page describing Mattia Giovannini's self-hosted homelab — the stack it runs (GitOps-managed k3s, runtime security, observability) and how agentic AI tools (Claude Code) get scoped access to it.

No build step: plain HTML/CSS, served as-is.

## Local dev

```bash
python3 -m http.server 8000
```

## Deploy

GitHub Pages, served from the root of `main`.

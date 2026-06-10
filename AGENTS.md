# AGENTS.md

Guidance for AI agents working in this repository.

## Repository overview

This repository (`ideas`) is currently a minimal placeholder. It contains only `README.md` with the title `# ideas`. There is no application code, dependency manifests, build tooling, tests, or service definitions.

**Canonical remote:** https://github.com/olucasbernardino/ideas.git

## Persistence and workflow constraints

- **Use this GitHub repo only.** All code, config, and documentation must live in `olucasbernardino/ideas` and be pushed to `origin`.
- **Do not rely on the user's local machine.** The developer's personal machine cannot be used for storage or as a source of truth. Do not instruct them to keep uncommitted work, local-only env files, or machine-specific artifacts outside this repository.
- **Cloud agents:** Work in the cloud VM workspace (`/workspace`), commit changes, and push to GitHub so nothing important exists only on ephemeral VM disk or the user's computer.
- **Secrets:** Never commit secrets. Use Cursor Cloud secrets or GitHub Actions secrets when credentials are needed later.

## Cursor Cloud specific instructions

### Services

| Service | Required | Notes |
|---------|----------|-------|
| *(none)* | — | No runnable application or backend exists in this repo yet |

### Development workflow

- **Clone / Git**: Clone from `https://github.com/olucasbernardino/ideas.git`. Default branch is `main`. Push all completed work to `origin` before ending a session.
- **Dependencies**: None. No `package.json`, `requirements.txt`, `Cargo.toml`, `go.mod`, `docker-compose.yml`, or similar files are present.
- **Lint / test / build / run**: Not applicable until application code is added. Re-scan the repo for manifests and README instructions when new code lands.

### When code is added

Future agents should look for:

- `README.md` — run and setup instructions
- `package.json`, `pyproject.toml`, `go.mod`, etc. — dependency installation
- `docker-compose.yml` / `Dockerfile` — containerized services
- `Makefile` — common dev targets
- `.devcontainer/` — dev container configuration

Update this section with concrete commands once those files exist.

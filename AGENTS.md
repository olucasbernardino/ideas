# AGENTS.md

Guidance for AI agents working in this repository.

## Repository overview

This repository (`ideas`) is currently a minimal placeholder. It contains only `README.md` with the title `# ideas`. There is no application code, dependency manifests, build tooling, tests, or service definitions.

## Cursor Cloud specific instructions

### Services

| Service | Required | Notes |
|---------|----------|-------|
| *(none)* | — | No runnable application or backend exists in this repo yet |

### Development workflow

- **Clone / Git**: Standard Git workflow applies. The default branch is `main`.
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

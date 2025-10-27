# GitHub Actions Lab - GitHubActionsLab-NabiaMahmood

## Workflows included
1. `.github/workflows/dependent-jobs.yml` — demonstrates job dependencies (build → test → deploy).
2. `.github/workflows/env-and-secrets.yml` — demonstrates env at workflow/job/step levels and using secrets.
3. `.github/workflows/multi-platform.yml` — demonstrates parallel jobs across Ubuntu, Windows, macOS.

## How to test
- Dependent jobs: push to `main`.
- Env & secrets: run manually from Actions → Environment and Secrets Workflow → Run workflow.
- Multi-platform: create a branch, push, open a PR to `main`.

## Notes
- Secrets are masked automatically by GitHub Actions.
- Use `needs` for dependencies. Without `needs`, jobs run in parallel.

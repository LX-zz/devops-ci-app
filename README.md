# devops-ci-app

Учебное Flask-приложение для практической работы №10.

## CI/CD

Pylint → pytest → Docker build → smoke-test → GHCR.

Публикация образа выполняется только из main.
В Pull Request выполняются проверки без публикации.

## HTTP

- GET /health
- GET /

## Docker

Образ: ghcr.io/lx-zz/devops-ci-app

## GitHub Actions

Workflow: .github/workflows/ci.yml

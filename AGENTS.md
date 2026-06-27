# Resources

- https://docs.daft.ai for the user-facing API docs for Daft
- https://docs.daft.ai/en/stable/extensions/authoring/ for writing Daft extensions

# Dev Workflow

1. Set up Python environment, install dependencies, and build dev package: `uv sync`
2. Activate .venv: `source .venv/bin/activate`
3. If Rust code is modified, rebuild: `make build`

# PR Conventions

- Titles: Conventional Commits format; enforced by `.github/workflows/pr-labeller.yml`.
- Descriptions: follow `.github/pull_request_template.md`.

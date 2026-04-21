# test67

> Scaffolded with [forge](https://github.com/your-org/forge) — node project.

## Getting started

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

## Project structure

```
test67/
├── src/          # Application source code
├── tests/        # Test suite
├── terraform/    # Infrastructure as code
├── Dockerfile
└── .gitignore
```

## Infrastructure

Terraform module located in `terraform/`. Initialise with:

```bash
cd terraform
terraform init
terraform plan
```

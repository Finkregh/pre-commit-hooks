# Renovate pre-commit hooks

A [pre-commit](https://pre-commit.com/) hook to run `renovate-config-validator` when you [reconfigure Renovate via PR](https://docs.renovatebot.com/getting-started/installing-onboarding/#reconfigure-via-pr).

Even though it is a Node-based hook, it works [without any system-level dependencies](https://pre-commit.com/#node).

## Usage

```yaml
repos:
  - repo: github.com/maxbrunet/renovate-pre-commit-hooks
    rev: 31.57.0
    hooks:
      - id: renovate-config-validator
```

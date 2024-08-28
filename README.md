# Prettier pre-commit (pre-commit.com) hook

Fork of archived https://github.com/pre-commit/pre-commit

---

# prettier

For prettier repo: see https://github.com/prettier/prettier

### Using prettier with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/posthello-code/pre-commit-prettier
  rev: "" # Use the sha / tag you want to point at
  hooks:
    - id: prettier
```

# mypy-dev mirror

Mirror of `mypy-dev` for pre-commit.

> [!CAUTION]
> Use at your own risk!  
> Old releases might be deleted!

For `pre-commit`: see https://github.com/pre-commit/pre-commit  
For `mypy-dev`: see https://github.com/cdce8p/mypy-dev

### Using mypy-dev with pre-commit:

Add this to your `.pre-commit-config.yaml`

```yaml
- repo: https://github.com/cdce8p/mypy-dev-pre-commit
  rev: ''  # Use the sha / tag you want to point at
  hooks:
    - id: mypy
```

### Credit

Based on https://github.com/pre-commit/mirrors-mypy/

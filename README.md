# prettier pre-commit hook

pre-commit hook of prettier with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For prettier: see [here](https://github.com/prettier/prettier)

## Using prettier with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-prettier
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: prettier-conda
```

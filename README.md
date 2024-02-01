# checkov pre-commit hook

pre-commit hook of checkov with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For checkov: see [here](https://github.com/bridgecrewio/checkov)

## Using checkov with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-checkov
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: checkov-conda
```

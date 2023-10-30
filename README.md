checkov(-conda) mirror
===================

Mirror of checkov for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For checkov: see https://github.com/bridgecrewio/checkov

### Using checkov with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-checkov
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: checkov-conda
```

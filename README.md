# setup-guardai-action

A GitHub Action for installing GuardAI in GitHub Workflows across multiple operating systems. Cached by default.

<!-- action-docs-inputs source="action.yml" -->

## Inputs

| name      | description                          | required | default  |
| --------- | ------------------------------------ | -------- | -------- |
| `version` | <p>Version of GuardAI to install</p> | `false`  | `latest` |

<!-- action-docs-inputs source="action.yml" -->

<!-- action-docs-outputs source="action.yml" -->

<!-- action-docs-outputs source="action.yml" -->

<!-- action-docs-runs action="action.yml" -->

## Runs

This action is a `composite` action.

<!-- action-docs-runs action="action.yml" -->

<!-- action-docs-usage action="action.yml" project="codeguardai/setup-guardai-action" version="0.1.0" -->

## Usage

```yaml
- uses: codeguardai/setup-guardai-action@0.1.0
  with:
    version:
    # Version of GuardAI to install
    #
    # Required: false
    # Default: latest
```

<!-- action-docs-usage action="action.yml" project="codeguardai/setup-guardai-action" version="0.1.0" -->

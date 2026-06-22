# DriftHeal Action

Autonomous cross-repository API contract guardian and self-healing engine.

## Usage

Add the following step to your GitHub Actions workflow:

```yaml
steps:
  - name: Run DriftHeal
    uses: rohitdas-ai/driftheal-action@v1.0.0
```

## Description

DriftHeal actively monitors API changes across your distributed repositories, automatically identifying contract drift, and proposing immediate code-fixes to downstream consumers before pipelines break.

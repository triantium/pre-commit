# Pre Commit Hooks

## Kustomize 

Usage:

```
  - repo: https://github.com/triantium/pre-commit.git
    rev: v0.0.2 # Version from Tags or Release
    hooks:
      - id: kustomize
        name: 
        args: [ '.k8s/overlays/test' ]
```

# [prek](https://github.com/j178/prek) hook for csharpier

please note you cannot use this hook with pre-commit as it does not support dotnet additional-deps


example config:
```yaml
  - repo: https://github.com/snus-kin/mirrors-csharpier
    hooks:
      - id: csharpier
        name: CSharpier
```

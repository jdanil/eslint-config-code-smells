# eslint-config-code-smells

A collection of ESLint rules to enforce [clean coding](https://moderatemisbehaviour.github.io/clean-code-smells-and-heuristics/) conventions.

This configuration is a demonstration of how ESLint can be used to automate enforcement of some rules.
The configuration represents a subset of rules from some eslint plugins;
it is still suggested to use the plugins directly and their recommended rules.

## Usage

install

```bash
yarn install --save-dev eslint-config-code-smells
```

eslint config

```yaml
extends:
  - code-smells
parserOptions:
  project: ./tsconfig.json # if using typescript
```

# eslint-config-clean-code

A collection of eslint rules to enforce [clean coding](https://moderatemisbehaviour.github.io/clean-code-smells-and-heuristics/) conventions.

This configuration is a demonstration of how eslint can be used to automate enforcement of some rules.
The configuration represents a subset of rules from some eslint plugins;
it is still suggested to use the plugins directly and their recommended rules.

## Usage

install

```bash
yarn add https://github.com/jdanil/eslint-config-clean-code.git#master
```

eslint config

```yaml
extends:
  - eslint-config-clean-code
parserOptions:
  project: ./tsconfig.json # if using typescript
```

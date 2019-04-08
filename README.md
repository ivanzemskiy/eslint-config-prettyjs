# eslint-config-prettyjs

Eslint Config based on JS Standard

### Purpose

Combination of: Eslint + Prettier + JavaScript + TypeScript

### Inspiration

Non-resolved problems like this: https://github.com/prettier/prettier-vscode/issues/352

## Links

#### TypeScript ESLint
- https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin
- https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/src/configs/recommended.json

#### Prettier ESLint
- https://github.com/prettier/eslint-plugin-prettier
- https://github.com/prettier/eslint-config-prettier#special-rules
- https://github.com/prettier/eslint-config-prettier/blob/master/index.js

#### Eslint Guide
- https://eslint.org/docs/developer-guide/shareable-configs

#### Eslint Config Examples
- https://github.com/standard/eslint-config-standard
> - https://github.com/standard/eslint-plugin-standard
> - https://github.com/xjamundx/eslint-plugin-promise
> - https://github.com/benmosher/eslint-plugin-import
> - https://github.com/mysticatea/eslint-plugin-node
- https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base
- https://github.com/airbnb/javascript/blob/master/packages/eslint-config-airbnb-base/rules/imports.js - airbnb uses _‘eslint-plugin-import’_
>  - https://github.com/benmosher/eslint-plugin-import

https://eslint.org/docs/user-guide/migrating-from-jscs#converting-presets - ESLint Shareable Config

| Preset | ESLint Shareable Config |
| --- | --- |
| `airbnb` | [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) |
| `crockford` | (not available) |
| `google` | [eslint-config-google](https://github.com/google/eslint-config-google) |
| `grunt` | [eslint-config-grunt](https://github.com/markelog/eslint-config-grunt) |
| `idiomatic` | [eslint-config-idiomatic](https://github.com/jamespamplin/eslint-config-idiomatic) |
| `jquery` | [eslint-config-jquery](https://github.com/jquery/eslint-config-jquery) |
| `mdcs` | [eslint-config-mdcs](https://github.com/zz85/mrdoobapproves) |
| `node-style-guide` | [eslint-config-node-style-guide](https://github.com/pdehaan/eslint-config-node-style-guide) |
| `wikimedia` | [eslint-config-wikimedia](https://github.com/wikimedia/eslint-config-wikimedia) |
| `wordpress` | [eslint-config-wordpress](https://github.com/WordPress-Coding-Standards/eslint-config-wordpress) |

> - https://github.com/google/eslint-config-google
> - https://github.com/github/eslint-plugin-github
> - https://github.com/Netflix/eslint-config-netflix
> - https://github.com/htmlacademy/eslint-config-htmlacademy
> > - https://github.com/marcelmokos/eslint-config-with-prettier
> > - https://github.com/keithamus/eslint-config-strict
> > - https://github.com/npetruzzelli/eslint-config-prettier-standard

#### Eslint "overrides":"extends" Workaround
- https://eslint.org/docs/user-guide/configuring#how-it-works - Eslint `“overrides”`
- https://github.com/eslint/eslint/issues/8813#issuecomment-456034732 - Glob override configs do not support "extends"

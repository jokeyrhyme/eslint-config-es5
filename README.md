# @jokeyrhyme/eslint-config-es5

an opinionated ESLint configuration

[![npm module](https://img.shields.io/npm/v/@jokeyrhyme/eslint-config-es5.svg)](https://www.npmjs.com/package/@jokeyrhyme/eslint-config-es5)
[![travis-ci](https://img.shields.io/travis/jokeyrhyme/eslint-config-es5.svg)](https://travis-ci.org/jokeyrhyme/eslint-config-es5)

## What does it do?

- extends "eslint:recommended"

- extends [eslint-config-semistandard](https://github.com/Flet/eslint-config-semistandard)

    - which extends [eslint-config-standard](https://github.com/feross/eslint-config-standard)

- explicitly disables the "env" and "ecmaFeatures" settings from standard

- enables all rules from [Best Practices](http://eslint.org/docs/rules/#best-practices)

    - "complexity" higher than 10 is a warning

    - not "no-eq-null", as "eqeqeq" covers it

    - not "no-implicit-coercion", as I like the shorter notation

    - "no-warning-comments" is a warning

- enables other rules

    - "valid-jsdoc", but don't require `@returns` for every Function

    - "no-shadow"

    - "no-undefined"

    - "no-use-before-define"

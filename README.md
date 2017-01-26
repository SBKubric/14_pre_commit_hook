# Quadratic Equations Solver

## Description

This unique script provides 5th grades with ultimate power of solving square equations! Due to rather big developers team
it is provided with module tests and pre-commit check.

## Usage

```
<<< from quadratic_equation import get_roots

<<< print(get_roots(1, -2, 1))

>>> 1, 1
```

## Auto-testing

### Description

This module supports autotesting during commit. If enabled it will run tests during every commit and would abort if some of test failed.

### Installation

Just run the script file `./init_hooks` to use pre-commit hook in your project!

### Configuration

If you want to add extra hooks, just place them into
`./hooks/` directory and run the `./init_hooks`.

If you want to know more about git-hook technique you could use this [link](http://githooks.com/).

Also you can define extra scripts in the `makefile` and `./hooks/*`.

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)

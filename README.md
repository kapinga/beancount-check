# Beancount-check
A [pre-commit](https://pre-commit.com) hook mirror for linting [beancount](http://furius.ca/beancount) files with `bean-check`.

## To Install
Add the following to your `.pre-commit-config.yaml`:
```
-   repo: https://github.com/kapinga/beancount-check.git
    rev: 'v0.1.0'
    hooks:
    -   id: beancount-check 
```

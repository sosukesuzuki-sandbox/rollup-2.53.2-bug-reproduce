# Rollup 2.53.2 bug reproduce

To reproduce the memory bug of Rollup 2.53.2.

ref: https://github.com/rollup/rollup/issues/4181

In this repository, I tried to build same code with defferent Rollup versions(`2.53.1` and `2.53.2`).

See results of building in GitHub Actions:

- [Build with Rollup 2.53.1 has succeed](https://github.com/sosukesuzuki-sandbox/rollup-2.53.2-bug-reproduce/runs/3101870864?check_suite_focus=true)
- [Build with Rollup 2.53.2 has failed](https://github.com/sosukesuzuki-sandbox/rollup-2.53.2-bug-reproduce/actions/runs/1044442869)

## Context

- https://github.com/prettier/prettier/pull/11217

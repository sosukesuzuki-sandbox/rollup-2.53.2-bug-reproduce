# Rollup 2.53.2 bug reproduce

To reproduce the memory bug of Rollup 2.53.2.

ref: https://github.com/rollup/rollup/issues/4181

This repository includes two projects:

## 1. bundle `flow-parser` with Rollup **2.53.1**.

This command will success

```
npm run run:2.53.1

```

## 2. bundle `flow-parser` with Rollup **2.53.2**.

But, this command will fail because of memory problems:

```
npm run run:2.53.2

```


- [components](#components)
  - [Getting Started](#getting-started)
    - [关于贡献代码](#关于贡献代码)
    - [关于发版](#关于发版)

# components

## Getting Started

Install dependencies,

```bash
$ tnpm i
```

Start the dev server,

```bash
$ tnpm start
```

Build documentation,

```bash
$ tnpm run docs:build
```

Run test,

```bash
$ tnpm test
```

Build library via `father-build`,

```bash
$ tnpm run build
```

### 关于贡献代码

1. `fork toCfe/components`
2. update files
3. pr to toCfe/components
4. other review and merged
5. lerna publish

### 关于发版

1. 如果 lerna publish 失败了，因为其需要文件改动才能重新发版，但是没关系，可以去子包内直接 npm publish 即可

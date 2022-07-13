安装依赖后运行 max setup 就报错了，执行 max dev 也会报错

```
$ max setup
│ fatal - Error: Register plugin /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+plugins@4.0.6_ifk47trdx4k2nmkpfwvit
│ Require stack:
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+plugins@4.0.6_ifk47trdx4k2nmkpfwvitjhdqq/node_modules/@umijs/plu
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+plugins@4.0.6_ifk47trdx4k2nmkpfwvitjhdqq/node_modules/@umijs/plu
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dist/service/plugin.js
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dist/service/pluginAPI.js
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dist/index.js
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/umi@4.0.6_n6ei2enrkwsxqmhl5cihb3nvii/node_modules/umi/dist/service/serv
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/umi@4.0.6_n6ei2enrkwsxqmhl5cihb3nvii/node_modules/umi/dist/cli/cli.js
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/umi@4.0.6_n6ei2enrkwsxqmhl5cihb3nvii/node_modules/umi/dist/index.js
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+max@4.0.6_nc4dtyqdheuhii572r4yb6hf5i/node_modules/@umijs/max/dis
│ - /Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+max@4.0.6_nc4dtyqdheuhii572r4yb6hf5i/node_modules/@umijs/max/bin
│     at Plugin.apply (/Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dist/serv
│     at Service.initPlugin (/Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dis
│     at Service.run (/Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/@umijs+core@4.0.6/node_modules/@umijs/core/dist/servi
│     at processTicksAndRejections (node:internal/process/task_queues:96:5)
│     at async Service.run2 (/Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/umi@4.0.6_n6ei2enrkwsxqmhl5cihb3nvii/node_modu
│     at async run (/Users/cuiliang/FE/React/umi3-and-umi4/node_modules/.pnpm/umi@4.0.6_n6ei2enrkwsxqmhl5cihb3nvii/node_modules/umi/d
│ fatal - A complete log of this run can be found in:
│ fatal - /Users/cuiliang/FE/React/umi3-and-umi4/apps/umi4/node_modules/.cache/logger/umi.log
│ fatal - Consider reporting a GitHub issue on https://github.com/umijs/umi/issues
```

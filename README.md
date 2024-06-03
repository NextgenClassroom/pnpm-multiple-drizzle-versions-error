## Steps to reproduce

1. `pnpm i`
2. `cd apps/app2`
3. `pnpm run drizzle:up` - Notice **drizzle-orm: v0.29.3**
4. `cat node_modules/drizzle-orm/package.json | grep version` The version here is **0.31.0**
5. `cat ../app1/node_modules/drizzle-orm/package.json | grep version` here's the **0.29.3** version
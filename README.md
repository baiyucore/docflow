# DocFlow Foundation

DocFlow 同层的空白 monorepo 基座：Next.js（React）前端、NestJS（Fastify）后端。尚无业务页面、接口、数据库、协同编辑或 Agent 功能。

## 结构

- `apps/frontend`：空白 React 页面，开发端口 3000。
- `apps/backend`：空 Nest 应用，开发端口 3001，没有业务路由。
- `packages`：预留共享包目录。

## 开始

使用 Node.js 24 和 pnpm 10。运行 `pnpm install` 安装依赖，`pnpm dev` 启动两个应用。

`pnpm lint` 检查代码，`pnpm format:check` 检查格式，`pnpm typecheck` 检查类型，`pnpm build` 构建。`pnpm check` 依次执行这些检查。

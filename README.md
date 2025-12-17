# My Domain Monitor

这是一个域名监控工具。

## 如何使用 (How to use)

1. **Fork 本项目**：点击右上角的 Fork 按钮。
2. **安装依赖**：
   ```bash
   npm install
3.配置数据库： 运行 SQL 命令初始化你的 D1 数据库：
<BASH>
npx wrangler d1 execute 你的数据库名 --file=./schema.sql
4.部署：
<BASH>
npm run deploy

# 💬 概述

一个简单而优雅的 AI 聊天程序

支持 ChatGPT **函数调用：**

- Google 搜索 (使用`Programmable Search Engine`)

## ⚙️ 设置

#### 环境变量

- `OPENAI_API_KEY`：懂得都懂
- `GOOGLE_API_KEY`：用于 Google 搜索插件（可选）
- `GOOGLE_ENGINE_ID`：用于 Google 搜索插件（可选）

## 🚀 本地运行

1. 克隆仓库：

```sh
git clone 
```

2. 安装依赖项：

```bash
pnpm install
```

3. 本地运行：

```bash
# 设置环境变量 OPENAI_API_KEY=sk-xxx
touch .env.local
# 本地运行
pnpm run dev
```

# FlowUs MCP 配置指南

## 1. 获取 FlowUs MCP Token

1. 打开 FlowUs → 空间设置 → 开发者中心
2. 创建集成应用（机器人），命名如 "DeepSeek助手"
3. 把需要 AI 访问的页面勾选权限
4. 复制生成的 Token

## 2. MCP 地址

```
Streamable HTTP:
https://mcp.flowus.cn/message?token=你的Token

SSE:
https://mcp.flowus.cn/sse?token=你的Token
```

## 3. 在 AI 客户端中配置

DeepSeek API 配置示例：
```
mcpServers:
  flowus:
    url: https://mcp.flowus.cn/message?token=你的Token
```

## 4. 验证

配置完成后，AI 可以：
- 读取 FlowUs 页面内容
- 写入笔记到指定页面
- 搜索知识库内容
- 配合 DeepSeek 的读图能力识别图片

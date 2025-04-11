本项目是复现 https://github.com/jasonsum/gmail-mcp-server/tree/main 的gmail邮箱管理服务。
# Gmail MCP 服务器

基于Model Context Protocol的Gmail邮件管理服务，支持邮件发送、读取、草稿编辑等功能。

## 主要功能
- 📩 发送邮件
- 📥 读取未读邮件
- 📝 编辑邮件草稿
- 🗑️ 删除邮件到垃圾箱
- ✅ 标记邮件为已读


使用mcp inspector测试： npx @modelcontextprotocol/inspector uv run src/gmail/server.py --creds-file-path D:/DevlopProjects/test6/gmail-mcp-server-main/credential.json --token-path D:/DevlopProjects/test6/gmail-mcp-server-main/token.json

本地终端运行：uv run src/gmail/server.py --creds-file-path D:/DevlopProjects/test6/gmail-mcp-server-main/credential.json --token-path D:/DevlopProjects/test6/gmail-mcp-server-main/token.json
注意: credential.json文件是Google API的凭证文件，token.json文件是用于存储访问令牌的文件(自动生成)
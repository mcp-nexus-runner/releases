# Nexus Runner

**官网 / Website: [mcp-nexus.online](https://mcp-nexus.online)**

Nexus Runner 是 [MCP Nexus](https://mcp-nexus.online) 的本机客户端 —— AI 技能的应用市场与执行引擎。用自然语言对话，即可调用 330+ 个经过测试的实用技能（财务对账、合同审查、Excel 批处理、SEO、数据洞察等），并把多个技能自动编排成可复用的业务工作流。

Nexus Runner is the desktop client for [MCP Nexus](https://mcp-nexus.online) — an app marketplace and execution engine for AI skills. Talk to it in plain language to run 330+ tested skills (reconciliation, contract review, batch Excel, SEO, data insight, and more), and chain them into reusable business workflows.

---

## 下载 / Download

| Platform | File | |
|---|---|---|
| Windows 10/11 (x64) | [NexusRunner-1.0.7-win-Setup.exe](https://github.com/mcp-nexus-runner/releases/releases/latest) | [Latest Release](https://github.com/mcp-nexus-runner/releases/releases/latest) |

下载后校验 SHA256，与 Release 页 `SHA256SUMS.txt` 一致即为完整未篡改。
After downloading, verify the SHA256 against `SHA256SUMS.txt` on the Release page.

```powershell
Get-FileHash .\NexusRunner-1.0.7-win-Setup.exe -Algorithm SHA256
```

---

## 核心能力 / What it does

1. **技能市场 Skill Marketplace** — 330+ 技能，BYOK 自带大模型 Key，一键安装到 Runner。
2. **工作流引擎 Workflow Engine** — scan -> decide -> execute -> deliver，多技能自动编排成业务流水线。
3. **技能图谱 Skill Graph** — 技能间内建 8 类关联关系，覆盖财务/法务/制造/营销/办公 5 大行业包，自动推荐下一步。
4. **智能体对话 Agent Chat** — Agent 自主多轮工具循环，把"提一个需求"变成"交付一份结果"。
5. **MCP 互操作 MCP Interop** — 兼容 Claude Desktop / Cursor / Cline 等任意 MCP 客户端，技能即插即用。

---

## 说明 / Notes

- 仅支持 Windows 10/11 (x64)。Windows 10/11 (x64) only.
- 本仓库仅用于发布官方安装包，**不包含源代码**（闭源商业软件）。This repository hosts official binaries only and contains **no source code** (closed-source commercial software).
- 问题反馈 / Support: [Issues](https://github.com/mcp-nexus-runner/releases/issues) 或 [mcp-nexus.online](https://mcp-nexus.online)

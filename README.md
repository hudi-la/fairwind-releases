# Fairwind · 发布 / Releases

这里只放**发布物**，不放源码：每个 Release 里是安装包（zip）、`latest.json` 和装机脚本。
This repository holds **release artifacts only** — no source. Each release has the app bundle (zip), `latest.json` and the install script.

## 装机 / Install (mac)

打开「终端」，粘这一行，回车：
Open Terminal, paste this line and press Enter:

```
curl -fsSL https://github.com/hudi-la/fairwind-releases/releases/latest/download/install.sh | sh
```

装好之后双击你用户目录下「应用程序」里的 **Fairwind**。以后有新版本，程序里会自己提示。
Then double-click **Fairwind** in the Applications folder inside your home folder. The app tells you when a new version is available.

**从装机到用 AI 工具填档案，一步一步：[SETUP.md](SETUP.md)** · **Step by step, from install to filling your profile with your AI tool: [SETUP.md](SETUP.md)**

## 许可 / License

随包附带的 `LICENSE.txt`：可自用，不可转售、不可用它开班或做成别的产品。
See `LICENSE.txt` in the bundle: personal use only; no resale, no teaching with it, no derivative products.

## 让你自己的 AI 工具读写 Fairwind / Use your own AI tool with Fairwind

Fairwind 开了一扇门（MCP）：Claude 桌面版、Claude Code、Codex、Gemini CLI 或任何认 MCP 的工具，连上就能替你从作品集网站填档案、把 open call 做成机会卡、按你的口味改判据。设置里一键接入；怎么接、能做什么、试试哪几句：[MCP-guide.md](MCP-guide.md)。
Fairwind exposes an MCP server: the Claude desktop app, Claude Code, Codex, Gemini CLI or any MCP-capable tool can fill your profile from your website, turn open calls into pursuit cards and rewrite your judgment rules. One-click connect in Settings; how to connect and what to say: [MCP-guide.md](MCP-guide.md).

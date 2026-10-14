# mobile-geo-ops

> 🔄 持续更新 / Continuously updated

## 中文

**是什么**：一个 Agent Skill，指导 AI 通过 [iphone-use](https://github.com/search?q=iphone-use) 在真机 iPhone 上做 GEO（生成式引擎优化）与社媒运营：AI App 回答周测（DeepSeek/千问/豆包/元宝）、小红书养号、单条私信测试。适用于网页端被登录墙或验证码挡住的场景。

**依赖**：iphone-use（MCP 或桥接脚本）；macOS + 通过 USB/无线连接的 iPhone。

**用法**：把本仓库目录（含 `SKILL.md`）放进 Cursor 或 Claude 的 skills 目录（例如 `~/.cursor/skills/` 或 `~/.claude/skills/`），之后让 Agent 做相关任务时会自动加载。将文中的 `<brand>`、`<site>` 换成你的品牌与官网。

**安全原则**：
- 遵守各平台用户协议与社区规则；
- 私信等外联动作必须先得到账号所有者授权，频率保持极低，出现风控立即停止；
- 不登出、不改资料、不装/删 App、不删记录，系统权限弹窗一律拒绝并记录；
- 不抢占其他会话或自动化任务。

## English

**What**: An agent skill that drives a real iPhone via iphone-use for GEO (Generative Engine Optimization) and social-media ops: weekly answer tests in AI apps, Xiaohongshu account warm-up, and single-DM tests — useful when the web is blocked by login walls or captchas.

**Requirements**: iphone-use (MCP or bridge script); macOS + a connected iPhone.

**Usage**: Drop this folder (with `SKILL.md`) into your Cursor or Claude skills directory (e.g. `~/.cursor/skills/` or `~/.claude/skills/`). Replace `<brand>` / `<site>` placeholders with your own.

**Safety principles**:
- Follow each platform's terms and community rules.
- Outreach/DMs only with the account owner's explicit authorization, at very low frequency; stop at any risk-control signal.
- Never log out, edit profiles, install/remove apps, or delete history; deny system permission prompts and log them.
- Never hijack other sessions or automations.

## License
MIT

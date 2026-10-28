# 608tt · Legal research × AI tools

我从法律研究中的材料整理与文本审校出发，做可追溯、可检查、能实际使用的小工具。  
I build tools for traceable research, usable AI workflows and explicit text checks.

## Selected projects / 精选项目

| Project | What it does / 一句话定位 | Explore |
|---|---|---|
| **01 · [Source Ledger](https://github.com/608tt/source-ledger)** | 把本地研究材料变成可检索、可追溯摘录、可记录人工复核的资料库。<br>Search local sources, trace excerpts and track human review; optional read-only MCP access for AI assistants. | [Report preview](https://github.com/608tt/source-ledger/blob/main/docs/overview.jpg) · [MCP setup](https://github.com/608tt/source-ledger/blob/main/docs/mcp.md) · [Validation](https://github.com/608tt/source-ledger/blob/main/docs/validation.md) |
| **02 · [Audio to Text](https://github.com/608tt/audio-to-text)** | 在浏览器本地将中英文录音转为文字，并导出 TXT、Word 或 Markdown。<br>Transcribe recordings on your device and export editable text; no account or API key. | **[Open web app](https://608tt.github.io/audio-to-text/)** · [Validation & deployment record](https://github.com/608tt/audio-to-text/blob/main/docs/validation.md) |
| **03 · [Rubric Gate](https://github.com/608tt/rubric-gate)** | 把文本中的必留字串、禁用表达与脚注要求变成可重复检查的规则，硬性失败不能被高分掩盖。<br>Check explicit text requirements with deterministic rules and hard-failure vetoes. | [Report preview](https://github.com/608tt/rubric-gate/blob/main/docs/overview.jpg) · [Rule reference](https://github.com/608tt/rubric-gate/blob/main/docs/rules.md) · [Validation](https://github.com/608tt/rubric-gate/blob/main/docs/validation.md) |

These projects cover source organization, audio transcription and text checks.
Source Ledger and Rubric Gate run locally; their report previews are screenshots.
Audio to Text has a hosted app; its first run downloads models.
Review marks record human declarations, transcripts need checking, and rule checks do not establish factual or legal correctness.

## New experiments / 新项目

| Project | What it does | Try |
|---|---|---|
| **[Scroll Words · 刷着记](https://github.com/608tt/scroll-words)** | 自选词库，在抖音、小红书电脑网页浏览间隙展示英文与中文释义。桌面扩展预览版；不支持 iPhone 原生 App 内插卡。 | [互动演示](https://608tt.github.io/scroll-words/) · [下载扩展](https://608tt.github.io/scroll-words/scroll-words-extension.zip) |
| **[Task Relay · 任务接力](https://github.com/608tt/task-relay)** | 本地排队、预约开始、限额等待与顺序执行。Codex CLI 已实测；Claude Code 待真实账号验证；聊天网页为手动接力。 | [互动演示（不调用 AI）](https://608tt.github.io/task-relay/) · [安装说明](https://github.com/608tt/task-relay#quick-start) |

<details>
<summary>More projects / 更多项目：数据标注与轻量交互</summary>

- **[Label Loop](https://github.com/608tt/label-loop)** — 小团队文本标注与复核：导入 → 标注 → 退回或通过 → 仅导出已通过结果。FastAPI · SQLite. [Review history](https://github.com/608tt/label-loop/blob/main/docs/review.jpg) · [Validation](https://github.com/608tt/label-loop/blob/main/docs/validation.md).
- **[Weather Pet](https://github.com/608tt/weather-pet)** — 宠物场景、小任务与专注计时器，展示轻量交互和本地状态管理。HTML · CSS · JavaScript. [Mobile preview](https://github.com/608tt/weather-pet/blob/main/docs/mobile.jpg) · [Validation](https://github.com/608tt/weather-pet/blob/main/docs/validation.md). Weather values are simulated.

</details>

Project READMEs include Chinese introductions, synthetic examples, local quick starts and documented limits.
Contributions are welcome: reproduce a problem, suggest a small improvement or make the first run clearer.

**Work inquiries / 工作联系:** [2032087242@qq.com](mailto:2032087242@qq.com)

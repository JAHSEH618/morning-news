# 🌅 morning-news

一个 Claude Code Skill —— 每日 10 分钟极客科技晨报生成器。

从 **多个高质量信息源** 自动抓取当日最核心动态，整合为一份结构化中文简报。直接在 Claude Code 中触发，无需离开终端。

## 信息源

| 板块 | 来源 |
|------|------|
| 🧠 AI 前沿与大厂动态 | Andrej Karpathy / X (Twitter) AI 热点 |
| 🤖 AI 应用与 Agent 工具 | Claude Code / OpenAI Codex / AI Apps 生态 |
| 💻 科技与开源 | Readhub / Hacker News / GitHub Trending |
| 🏘️ 社区与财富 | V2EX / Web3 空投 |
| 🎬 精神补给 | 豆瓣热门高分影音 |

## 安装

```bash
# 克隆仓库
git clone https://github.com/你的用户名/morning-news.git /tmp/morning-news

# 复制 skill 到个人目录（全局生效，所有项目可用）
cp -r /tmp/morning-news/.claude/skills/morning-news ~/.claude/skills/

# 清理
rm -rf /tmp/morning-news
```

或者一行搞定：

```bash
git clone https://github.com/你的用户名/morning-news.git /tmp/morning-news && cp -r /tmp/morning-news/.claude/skills/morning-news ~/.claude/skills/ && rm -rf /tmp/morning-news
```

## 使用

安装后在 Claude Code 中用以下任意方式触发：

```
生成今日极客晨报
10分钟早报
Daily Tech Briefing
开机早报
/morning-news
```

## 输出示例

```markdown
## 🌅 10分钟高能晨报 | 2026-03-03（星期二）

### 🧠 AI 前沿与大厂动态
* **[X热门] OpenAI 完成 $1,100 亿融资：** Amazon、SoftBank、Nvidia 领投...
* **[Karpathy] MicroGPT：** 200 行纯 Python 实现完整 GPT 训练与推理...

### 🤖 AI 应用与 Agent 工具
* **[Claude] WebMCP 早期预览版发布：** Chrome 原生 MCP 支持...
* **[Codex] Codex CLI 新增多仓库支持：** 可同时操作多个项目...

### 💻 科技与开源
* **[HN] Ghostty 终端模拟器：** 新一代高性能终端...(🔥 817 pts)
* **[GitHub] wifi-densepose：** WiFi 信号实现人体姿态估计...(⭐ +5,080 today)

### 🏘️ 社区与财富
* **[V2EX] "买车感觉像买了一个爷回来"：** ...(💬 206 replies)
* **[Web3] 3 月代币解锁潮：** 总价值超 $60 亿...

### 🎬 精神补给
* **[豆瓣] 《夜王》：** 黄子华、郑秀文主演...(⭐ 7.8)

---

## 🔗 深度阅读链接
1. OpenAI 融资 — [blog.mean.ceo/...](https://...)
2. MicroGPT — [karpathy.github.io/...](https://...)
...
```

## 要求

- [Claude Code](https://claude.com/claude-code) CLI
- 需要 `WebSearch` 和 `WebFetch` 工具权限

## License

MIT

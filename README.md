# Arvin Xiang

**AI Product Engineer.** 15 年工程经验，现在做 AI Native 产品——把 Agent 的能力落成用户真的会用、也愿意付费的东西。

**白天** 在 Quantum Temple 做 AI 语音旅行助手 **[Dunia](https://dunia.co)**（已上架 App Store）：主导移动端与 Agent 交互层，把 Tool Call 编排成界面，让「语音说了什么」和「屏幕显示什么」实时对齐；
同时做 agent 驱动的提案流水线：21 工具的 MCP server，以及一套能在任一决策点停下来转人工的状态机。

**晚上** 一个人做产品，从想法到收款全链路自己跑。就是下面这些。

[arvinxiang.com](https://arvinxiang.com) · [me@arvinxiang.com](mailto:me@arvinxiang.com)

---

### 在做的产品

| 产品 | 是什么 |
|---|---|
| **[初创.site](https://chuchuang.site)** | 一句话生成能直接上线的产品官网 |
| **[初创.work](https://chuchuang.work)** | 让你的新产品被看见，找到最早的一批用户 |
| **[穿搭日记](https://apps.apple.com/cn/app/id6761793902)** &nbsp;`iOS` | 拍一张今天的穿搭，AI 给你打分、点评和改进建议 |
| **[Luma SEO](https://lumaseo.com)** | 批量生成能被 AI 搜索引用的内容 |
| **[咋约](https://zayue.com)** | 不用滑卡：AI 先读懂你，一次只推一个人，目标是真的见上面 |
| **[打赏网](https://dashang.me)** | 国内版 Ko-fi：一分钟拿到收款主页，粉丝微信支付宝直接打赏 |
| **[每周见](https://meizhoujian.com)** | 在自己的城市认识 6–10 个聊得来的人，一杯咖啡的价格 |
| **[远程.work](https://yuancheng.work)** | 中文远程工作招聘平台 |

这些产品共享一套自己写的底座：**order-first 通用收银台**（微信 / 支付宝，服务端定价、订单先行、支付后凭单自交付）、**邮箱即身份的免登录会员体系**（付款态或验证码换 JWT，不做注册登录）、模块化的 headless WordPress 后端。一个 pnpm monorepo 装下 25 个应用和 14 个共享包。

几个值得说的点：初创.site 把「AI 生成 → 行内编辑 → 一键发布」做成了一条路，
子域名和自定义域名都能绑；初创.work 收了 2300+ 个初创产品，全站静态预渲染加按需失效，导航栏是即时补全、回车才走完整检索；穿搭日记跑在 RN + Expo 新架构上，双模型容灾加自建反代解决国内直连不通，订阅内购和 OTA 热更新都是自己接的。

---

### 我解决的问题

- **Agent 工作流** — MCP 工具设计、可被人打断的状态机、重试安全的幂等契约、版本链与 supersede 语义
- **Agent 交互层** — Tool Call → UI 编排、实时语音的打断与时序控制、长会话状态的持久化与恢复
- **一个人跑完全链路** — 从产品定义、架构、开发到支付、部署、增长，每一环都真的上线收过钱

---

### 技术栈

```
AI/Agent    LiveKit · WebRTC · Tool Call 编排 · MCP · LangGraph/LangChain SDK · pgvector · RAG
Web         React 19 · Next.js · TypeScript · Tailwind · TanStack Query · Zustand
Mobile      React Native · Expo · EAS · RevenueCat
Backend     PostgreSQL · Prisma · Node.js · Headless WordPress · Docker · Nginx
```

---

### 履历

`2025 – 至今` &nbsp;**Quantum Temple** · 资深全栈工程师 — AI 语音产品 Dunia，主导移动端与 Agent 交互层<br>
`2020 – 2025` &nbsp;**优必选机器人** · 高级前端工程师 — AIGC 3D 教育产品，获深圳市教育局采购落地全市中小学<br>
`2014 – 2020` &nbsp;**Flashbay** · 前端负责人 — 10 亿级 B2B 电商平台全球化与增长，覆盖 30+ 国家站点<br>
`2011 – 2014` &nbsp;**富士康重庆研发中心** · 研发工程师

<sub>近几年的工作在私有仓库。公开仓库里 [landscape-plus](https://github.com/xiangming/landscape-plus)
还有人在用——2014 年给 hexo 写的主题优化，500+ star。</sub>

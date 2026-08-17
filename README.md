# Arvin Xiang

**AI Product Engineer.** 15 年工程经验，现在做 AI Native 产品——把 Agent 的能力
落成用户真的会用、也愿意付费的东西。

- 🎙️ 白天在 Quantum Temple 主导 AI 语音旅行助手 **[Dunia](https://dunia.co)** 的移动端与 Agent 交互层：
  把 Tool Call 编排成界面，让「语音说了什么」和「屏幕显示什么」实时对齐。已上架 App Store。
- 🔀 同期做 **agent 驱动的提案流水线**：21 工具的 MCP server、人在环的状态机、
  以及把整套 MCP 服务端灰度迁移到新后端。
- 🚀 晚上一个人做产品：7 个上线的 Web 产品 + 1 个 [App Store 应用](https://apps.apple.com/cn/app/id6761793902)，
  支付、会员、内容后台全部自建。
- 📮 [arvinxiang.com](https://arvinxiang.com) · [me@arvinxiang.com](mailto:me@arvinxiang.com)

---

### 在做的产品

| 产品 | 是什么 |
|---|---|
| **[初创.site](https://chuchuang.site)** | 一句话生成能直接上线的产品官网 |
| **[初创.work](https://chuchuang.work)** | 让你的新产品被看见，找到最早的一批用户 |
| **[远程.work](https://yuancheng.work)** | 中文远程工作招聘平台 |
| **[每周见](https://meizhoujian.com)** | 在自己的城市认识 6–10 个聊得来的人，一杯咖啡的价格 |
| **[打赏网](https://dashang.me)** | 国内版 Ko-fi：一分钟拿到收款主页，粉丝微信支付宝直接打赏 |
| **[咋约](https://zayue.com)** | 不用滑卡：AI 先读懂你，一次只推一个人，目标是真的见上面 |
| **[Luma SEO](https://lumaseo.com)** | 批量生成能被 AI 搜索引用的内容 |
| **[穿搭日记](https://apps.apple.com/cn/app/id6761793902)** | 拍一张今天的穿搭，AI 给你打分、点评和改进建议 |

这些产品共享一套自己写的底座：**order-first 通用收银台**（微信 / 支付宝，服务端定价、订单先行、
支付后凭单自交付）、**邮箱即身份的免登录会员体系**（付款态或验证码换 JWT，不做注册登录）、
模块化的 headless WordPress 后端。一个 pnpm monorepo 装下 25 个应用和 14 个共享包。

几个值得说的点：初创.site 把「AI 生成 → 行内编辑 → 一键发布」做成了一条路，
子域名和自定义域名都能绑；初创.work 收了 2300+ 个产品，全站静态预渲染加按需失效，
导航栏是即时补全、回车才走完整检索；穿搭日记跑在 RN + Expo 新架构上，
双模型容灾加自建反代解决国内直连不通，订阅内购和 OTA 热更新都是自己接的。

---

### 我解决的问题

**Agent 工作流与人机协同** — MCP 工具设计、可被人打断的状态机（任一决策点转人工）、
重试安全的幂等契约、版本链与 supersede 语义。
做 agent 流水线真正难的不是接 LLM，是**出错时怎么收场**：
接单幂等键怎么定、改主意了旧版本怎么退休、哪一步必须停下来等人。

**Agent 的人机交互层** — Tool Call → UI 编排、实时语音打断与时序控制、
长会话状态的持久化与恢复。会搭 Agent 的人很多，能把语音交互调顺的很少。

**一个人跑完全链路** — 产品定义 → 架构 → 开发 → 支付 → 部署 → 增长。
不是「什么都会一点」，是每一环都真的上线收过钱。

**让东西被找到** — Technical SEO 与性能优化的老本行：
在一个年销售额 10 亿级的 B2B 平台上做到自然流量 +50%、加载提速 60%、转化率 +20%，覆盖 30+ 国家站点。

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

<sub>下面的仓库大多是 2013–2016 年的旧作，近年的工作在私有仓库里。
[landscape-plus](https://github.com/xiangming/landscape-plus) 是早年给 hexo 写的主题优化，攒了 500+ star，留个纪念。</sub>

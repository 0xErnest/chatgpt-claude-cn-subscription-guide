# ChatGPT 代充 / GPT Plus 代充 / Claude 代充指南（2026）

> **一句话**：国内怎么给自己的 ChatGPT、Claude 账号开通付费版？官方只认国际卡，支付宝微信付不了。这份指南对比四条路径（官方卡、应用商店内购、虚拟卡、人民币代充），写清风险、Session / 验证码交付边界、Codex Credits 加购，以及怎么挑代充平台。
>
> **English summary**: A facts-first guide for mainland China users who want ChatGPT Plus / Pro or Claude Pro / Max on **their own accounts**—official card, App Store IAP, virtual card, or RMB top-up (代充). Covers risks, Session delivery, Codex Credits, and how [XingqiaoSub (星桥订阅)](https://xingqiaosub.com) works. Not legal or financial advice.
>
> **利益相关 / Affiliation**：本仓库由星桥订阅（[xingqiaosub.com](https://xingqiaosub.com)）维护。文中会把星桥列为代充路径里的一个选项，请把这一点纳入判断，并自行交叉核实。
>
> **最后核实 / Last checked**：2026-10-18。价格和平台政策变化快，下单前请到对应官网再核对一次。

## 目录

1. [为什么需要这份指南](#1-为什么需要这份指南)
2. [风险与合规边界](#2-风险与合规边界)
3. [四条路径对比](#3-四条路径对比)
4. [Session 是什么、怎么工作](#4-session-是什么怎么工作)
5. [ChatGPT：Go / Plus / Pro / Credits](#5-chatgptgo--plus--pro--credits)
6. [Claude：Pro / Max / Claude Code](#6-claudepro--max--claude-code)
7. [Codex 额度不够怎么办](#7-codex-额度不够怎么办)
8. [怎么判断代充平台靠不靠谱](#8-怎么判断代充平台靠不靠谱)
9. [星桥订阅怎么做](#9-星桥订阅怎么做)
10. [FAQ](#10-faq)
11. [价格快照](#11-价格快照)
12. [更新记录](#12-更新记录)
13. [English](#english-short-version)

---

## 1. 为什么需要这份指南

在中国大陆开通 ChatGPT / Claude 付费版，常见卡点是：

- OpenAI / Anthropic 官方结账只收国际卡，国内卡经常被拒；
- 不想买成品号、共享号；
- 「ChatGPT 代充」「GPT Plus 代充」「Claude 代充」信息混杂：有的要密码，有的卖共享号，有的价格异常低。

这份指南只整理**可核对的事实和决策框架**，帮你选路，不替你做决定。

## 2. 风险与合规边界

- OpenAI / Anthropic 的服务条款对地区和支付方式有规定；第三方代付是否合规，以官方条款为准。
- 代充只解决支付通道，**不能保证**账号永远不被风控。账号被限制通常是支付、环境、使用多个信号累计的结果。
- 把密码交给陌生人、购买共享号，风险通常高于 Session 或一次性登录验证码这类交付方式。
- 本文不构成法律、税务或投资建议。

## 3. 四条路径对比

| 路径 | 账号归属 | 要密码吗 | 典型门槛 | 主要风险 |
|---|---|---|---|---|
| ① 官方自己付 | 自己的 | 否 | 能过 Stripe 的国际卡 | 拒卡；账单地区与使用地区不一致 |
| ② App Store / Google Play 内购 | 自己的 | 否 | 可购买的应用商店账号与支付方式 | 价格按商店地区定，通常高于官网折算 |
| ③ 虚拟卡自助 | 自己的 | 否 | 会自己开卡、绑卡 | 卡源不干净被拒付；开卡平台停服导致余额受损（如 WildCard 虚拟卡业务 2025-07-12 停服） |
| ④ 代充到自己账号 | 自己的 | 看平台，靠谱的不要 | 人民币支付 | 平台诚信与交付方式参差 |
| （不建议）成品号 / 共享号 | 不是你的 | 常由卖家掌握 | 无 | 被改密、回收，难维权 |

**原则**：账号是你的 + 不交密码 + 失败可退 + 价格可解释。能稳定走通 ①，就优先 ①。

## 4. Session 是什么、怎么工作

Session 是你在浏览器里的 ChatGPT 登录状态。部分 ChatGPT 代充流程要求你：

1. 用电脑或手机**浏览器**登录 ChatGPT（ChatGPT App 里拿不到）；
2. 打开 `https://chatgpt.com/api/auth/session`；
3. 完整复制页面内容，付款后粘贴给平台，用于**这一次**订阅开通。

它代替了密码，但仍然敏感：拿到它的人，在它失效前可以像你一样访问账号。

- Session 不包含你的密码，不会连累你在别的网站复用的密码；
- 充值确认成功后，在 ChatGPT「设置 → 安全 → 活跃会话」里选「退出所有会话」，交出去的 Session 随之失效（OpenAI 说明最长约 30 分钟生效），订阅和聊天记录不受影响；
- **充值完成前不要退出**，否则充值会中断；
- **Claude 代充通常不用 Session**，而是由客服在 Anthropic 官方页面发起登录，你转发一次性登录验证码（同样不该要密码）。

详细说明见 [docs/session-safety.md](docs/session-safety.md)。

## 5. ChatGPT：Go / Plus / Pro / Credits

| 档位 | 官方参考 | 适合谁 |
|---|---|---|
| Go | $8/月 | 轻度日常，比免费版多一点额度 |
| Plus | $20/月 | 大多数人的主力档：推理、深度研究、Codex 等 |
| Pro（Standard / More / Maximum，约 5× / 20× / 50× Plus 用量） | $100 / $200 / $500 月 | 重度对话、复杂任务；功能与 Plus 同档，差额度 |
| Credits（按量加购） | 见官网 | 已在 Plus / Pro 上，Codex 等额度用完后继续用 |

一句话选档：日常够用选 Plus；经常撞额度再看 Pro 5×，真不够再上 20×。**Credits 不是订阅**，要求账号**正在订阅** Plus 或 Pro。

## 6. Claude：Pro / Max / Claude Code

Claude 有三套容易混的账：网页 / App 的 **Pro·Max 订阅**、**API 按量**、以及跟着订阅走的 **Claude Code**。买错地方等于白花钱：Pro ≠ API 余额。

| 档位 | 官方参考 | Claude Code | 适合谁 |
|---|---|---|---|
| Pro | $20/月 | 有 | 轻量编程与日常 |
| Max 5x | $100/月 | 有 | 每天写代码 |
| Max 20x | $200/月 | 有 | 长时间 agent、多项目并行 |

网页与 Claude Code **共用额度**。Max 自带的 API 积分**不能**用在 Claude Code 或 Claude App 上（以 Anthropic 说明为准）。

更细的购买路径见星桥英文站：[How to buy Claude Code from China](https://xingqiaosub.com/en/blog/claude-code-plans-how-to-buy)。

## 7. Codex 额度不够怎么办

Codex 跟 ChatGPT Plus / Pro 订阅走。额度用完后有两条路：

1. **加购 ChatGPT Credits**（按量，有效期以官网为准，星桥侧公开标价见下表）：账号必须正在订阅 Plus 或 Pro；
2. **升级到更高用量的 Pro 档**（若当前 Plus / Pro 是在可升级的渠道买的）。

不要把「Codex 充值」理解成另开一个成品号——正规做法仍是充到你自己的 ChatGPT 账号。

## 8. 怎么判断代充平台靠不靠谱

用同一张核对表去比任何平台（包括星桥）：

| 要看的 | 靠谱信号 | 远离信号 |
|---|---|---|
| 账号归属 | 充到**你自己的号** | 发你账号密码、共享号、拼车 |
| 密码 | 不要密码；ChatGPT 用 Session，Claude 用一次性验证码 | 索要密码 / 支付密码 / 短信验证码长期代收 |
| 价格 | 可解释（含通道成本，略高于官方折算） | 远低于市场价 |
| 退款 | 「开通失败全额退」写在网站上 | 含糊、只在微信里口头说 |
| 主体 | 有独立官网、订单号、可联系的售后 | 只在闲鱼 / 群里报价 |

官方结账与定价以 [chatgpt.com/pricing](https://chatgpt.com/pricing/)、[claude.ai](https://claude.ai/) 为准。星桥维护的对比文章（含利益相关）：[国内 ChatGPT Plus 代充平台怎么选](https://xingqiaosub.com/blog/chatgpt-plus-recharge-platform-comparison)。

欢迎在 [Issue](../../issues) 里补充可核实的公开信息链接；无来源的渠道不会收录。

## 9. 星桥订阅怎么做

官网：[xingqiaosub.com](https://xingqiaosub.com/)。以下摘自官网公开页（2026-10-18），以官网为准。

**ChatGPT（Go / Plus / Pro / Credits）**

1. 在 [ChatGPT Plus 服务页](https://xingqiaosub.com/services/chatgpt-plus) 或 [价格页](https://xingqiaosub.com/pricing) 选择套餐并付款：微信支付，或支付宝 / 银行卡 / Apple Pay（后三种走 Stripe，按港币扣款，以账单为准）。
2. 付款后在「填写资料」页面粘贴 Session，页面读出账号邮箱，确认后提交。**全程不需要账号密码或验证码。**
3. 核实付款后预计 3–5 分钟完成充值，微信订单会先核对收款。

- **账号条件**：Go / Plus / Pro 要求本人账号、能正常登录，当前是**免费版、没有生效中的订阅**。加购 Credits 则相反，要求正在订阅 Plus 或 Pro。
- **Session 用途**（官网自述）：只用于提交前查询订阅状态和完成这一笔充值；不写入订单记录，不进网站日志；不用于修改密码、邮箱或登录方式，不读取聊天记录。见 [账号安全说明](https://xingqiaosub.com/support/security)。

**Claude（Pro / Claude Code Max）**

1. 付款时填写或备注订阅账号邮箱，付款后添加微信客服并发送订单信息。
2. 开通时转发一次性登录验证码，由客服在 Anthropic 官方页面代登录开通。**不需要账号密码。**
3. 账号条件（官网）：以前订阅过 Claude 付费套餐或已通过身份验证；注册地区、验证手机号归属地和日常访问地区保持一致；当前是免费版。不满足会开通失败，请付款前确认。见 [Claude Pro 服务页](https://xingqiaosub.com/services/claude-pro)、[Claude Code 服务页](https://xingqiaosub.com/services/claude-code)。

**退款**（[退款政策](https://xingqiaosub.com/support/refund-policy)）

- 未开通成功：核实后全额退款或取消；
- 重复付款：退回多付部分；
- 已经开通：不做无理由退款；
- 交付后账号被 OpenAI / Anthropic 限制或封禁：由官方决定，不在退款范围；
- 付款后 30 天内既未提交资料也未申请退款：视为放弃订单。

**不做的事**：不出售成品号、共享号；不是 OpenAI / Anthropic 官方合作方；不协助绕过平台规则或风控。

## 10. FAQ

**Q：ChatGPT 代充 / GPT Plus 代充会封号吗？**  
A：没有「一定封」或「一定不封」。限制多为支付、环境、使用多个信号累计触发。只用自己的号、不交密码、固定访问环境，是降低风险的基本做法。

**Q：代充一定要给密码吗？**  
A：不应该。ChatGPT 可以用 Session 代替密码，Claude 可以用一次性登录验证码。要密码的平台，建议换一家。

**Q：Go 还是 Plus？Pro 5× 还是 20×？**  
A：免费版不够用、但不常用推理 / 深度研究 / Codex，看 Go；写代码、做研究、处理长文档，看 Plus。经常撞 Plus 额度再看 Pro 5×，仍不够再上 20×。以 OpenAI 官方额度说明为准。

**Q：已经在订阅 Plus，还能代充 Plus / Pro 吗？**  
A：星桥的 Go / Plus / Pro **只能充到免费版、无生效订阅**的账号。Plus 期间 Codex 额度不够，可以加购 Credits。若 Plus 是在星桥买的，也可以中途升级到 Pro（升级按新套餐原价付款，已付套餐不抵扣、不补差价）。

**Q：Claude 代充和 Claude Code 是一回事吗？**  
A：Claude Code 没有单独售卖入口，跟 Claude Pro / Max 订阅走。买 Pro 或 Max 就自带 Claude Code；API 控制台里的余额是另一套账。

**Q：Codex 充值是什么？**  
A：通常指给已有 Plus / Pro 的账号加购 Credits，或升级到更高用量档，不是另买一个共享号。

**Q：能用支付宝或微信直接付给 OpenAI / Anthropic 吗？**  
A：不能。官方结账只接受国际卡；用人民币只能经过第三方。

**Q：怎么核实一家代充？**  
A：看退款政策是否写清楚、是否要密码、是否卖号、价格是否异常低、有无订单号与客服；必要时先小额试一次。

## 11. 价格快照

**星桥订阅公开标价（2026-10-22，人民币/月，以官网 [价格页](https://xingqiaosub.com/pricing) 为准）**

| 产品 | 星桥标价 | 官方参考 |
|---|---|---|
| ChatGPT Go | ¥99 | $8 |
| ChatGPT Plus | ¥165 | $20 |
| ChatGPT Pro（约 5 / 20 / 50 倍用量） | ¥850 / ¥1650 / ¥4250 | 见 OpenAI 官网 |
| ChatGPT Credits 500 / 1000（加购） | ¥199 / ¥349 | — |
| Claude Pro | ¥199 | $20 |
| Claude Code Max 5x / 20x | ¥850 / ¥1650 | 见 Anthropic 官网 |
| Google AI Pro 学生 12 个月（限美国高校在读学生） | ¥99 / 年 | $19.99 / 月 |

升级（Plus → Pro、Pro / Claude Pro → 更高档）：按新套餐原价付款，已付套餐不抵扣、不补差价。

人民币标价包含通道成本，会高于按汇率直换的数字。Stripe 路径按港币扣款（例如 Plus 约 HK$193），以支付宝或银行账单为准。

## 12. 更新记录

| 日期 | 变更 |
|---|---|
| 2026-10-22 | 价格按官网同步：Claude Pro ¥199、Credits 1000 ¥349，新增 Google AI Pro 学生；升级规则改为按新套餐原价、已付不抵扣 |
| 2026-10-18 | 按「代充」检索意图重排标题与目录；新增 Pro / Max / Codex Credits 专节与核对表；去掉冗长竞品名单；价格与流程按官网再核 |
| 2026-10-15 | 重写：按星桥官网核对流程（ChatGPT 用 Session、Claude 用一次性登录验证码、均不要密码；账号须为免费版）、支付方式、退款规则与价格；新增英文摘要 |
| 2026-10-06 | 新增 [docs/session-safety.md](docs/session-safety.md) |
| 2026-09-01 | 初版：四条路径、对比表、WildCard 停服复盘、FAQ |

---

## English (short version)

**Who this is for**: people in mainland China who want ChatGPT / Claude paid plans on **their own** accounts.

**Options**: (1) pay OpenAI / Anthropic directly with an international card; (2) App Store / Google Play in-app purchase; (3) a self-managed virtual card; (4) an RMB top-up service that activates your existing account. Buying shared or pre-made accounts is not recommended.

**Session delivery**: some ChatGPT top-up services ask you to paste your browser Session from `chatgpt.com/api/auth/session` after payment, so they never need your password. It is still sensitive. After the top-up succeeds, use Settings → Security → Active sessions → "Log out of all sessions" to invalidate it. Claude top-ups usually use a one-time login code instead. Details: [docs/session-safety.md](docs/session-safety.md).

**Plans in one glance**: ChatGPT Go / Plus / Pro (higher usage tiers) and Credits add-ons for Codex; Claude Pro / Max (Claude Code included). Credits need an active Plus or Pro plan; Go/Plus/Pro top-ups usually need a free account.

**XingqiaoSub (星桥订阅)**: https://xingqiaosub.com. CNY list prices as of 2026-10-22: Go ¥99, Plus ¥165, Claude Pro ¥199, Google AI Pro student ¥99/year, Pro / Max higher tiers from ¥850; Credits ¥199 / ¥349. Upgrades are charged at the new plan's full price; the already-paid plan is not credited. WeChat Pay, Alipay, bank card or Apple Pay. No password. Full refund if activation fails. **Affiliation**: this repository is maintained by XingqiaoSub.

**Rule of thumb**: own account, no password, clear refund terms, explainable price.

---

License: [MIT](./LICENSE)

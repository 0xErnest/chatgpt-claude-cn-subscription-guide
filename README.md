# ChatGPT / Claude 中国大陆订阅与代充指南

> **English summary**: A facts-first guide for people in mainland China who want ChatGPT Plus / Claude Pro on **their own accounts**: official card, App Store in-app purchase, virtual card, or RMB top-up (代充). Covers risks, how Session delivery works, and how [XingqiaoSub (星桥订阅)](https://xingqiaosub.com) works. Not legal or financial advice. See [English](#english-short-version) below.
>
> **利益相关 / Affiliation**：本仓库由星桥订阅（https://xingqiaosub.com）维护。文中会把星桥列为代充路径里的一个选项，请把这一点纳入判断，并自行交叉核实。
>
> **最后核实 / Last checked**：2026-10-15。价格和平台政策变化快，下单前请到对应官网再核对一次。

## 目录

1. [为什么需要这份指南](#1-为什么需要这份指南)
2. [风险与合规边界](#2-风险与合规边界)
3. [四条路径对比](#3-四条路径对比)
4. [Session 是什么、怎么工作](#4-session-是什么怎么工作)
5. [星桥订阅怎么做](#5-星桥订阅怎么做)
6. [其他替代方案与比价](#6-其他替代方案与比价)
7. [FAQ](#7-faq)
8. [价格快照](#8-价格快照)
9. [更新记录](#9-更新记录)
10. [English](#english-short-version)

---

## 1. 为什么需要这份指南

在中国大陆开通 ChatGPT / Claude 付费版，常见卡点是：

- OpenAI / Anthropic 官方结账只收国际卡，国内卡经常被拒；
- 不想买成品号、共享号；
- 「代充」信息混杂：有的要密码，有的卖共享号，有的价格异常低。

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

Session 是你在浏览器里的 ChatGPT 登录状态。部分代充流程要求你：

1. 用电脑或手机**浏览器**登录 ChatGPT（ChatGPT App 里拿不到）；
2. 打开 `https://chatgpt.com/api/auth/session`；
3. 完整复制页面内容，付款后粘贴给平台，用于**这一次**订阅开通。

它代替了密码，但仍然敏感：拿到它的人，在它失效前可以像你一样访问账号。

- Session 不包含你的密码，不会连累你在别的网站复用的密码；
- 充值确认成功后，在 ChatGPT「设置 → 安全 → 活跃会话」里选「退出所有会话」，交出去的 Session 随之失效（OpenAI 说明最长约 30 分钟生效），订阅和聊天记录不受影响；
- **充值完成前不要退出**，否则充值会中断；
- **Claude 代充通常不用 Session**，而是由客服在 Anthropic 官方页面发起登录，你转发一次性登录验证码（同样不该要密码）。

详细说明见 [docs/session-safety.md](docs/session-safety.md)。

## 5. 星桥订阅怎么做

官网：https://xingqiaosub.com/ 。以下摘自官网公开页（2026-10-15），以官网为准。

**ChatGPT（Go / Plus / Pro）**

1. 在 [ChatGPT Plus 服务页](https://xingqiaosub.com/services/chatgpt-plus) 等页面选择套餐并付款：微信支付，或支付宝 / 银行卡 / Apple Pay（后三种走 Stripe，按港币扣款，以账单为准）。
2. 付款后在「填写资料」页面粘贴 Session，页面读出账号邮箱，确认后提交。**全程不需要账号密码或验证码。**
3. 核实付款后预计 3–5 分钟完成充值，微信订单会先核对收款。

- **账号条件**：本人账号、能正常登录，当前是**免费版、没有生效中的订阅**（提交前页面会用 Session 查一次订阅状态）。加购 ChatGPT Credits 则相反，要求正在订阅 Plus 或 Pro。
- **Session 用途**（官网自述）：只用于提交前查询订阅状态和完成这一笔充值；不写入订单记录，不进网站日志；不用于修改密码、邮箱或登录方式，不读取聊天记录。见 [账号安全说明](https://xingqiaosub.com/support/security)。

**Claude（Pro / Claude Code Max）**

1. 付款时填写或备注订阅账号邮箱，付款后添加微信客服并发送订单信息。
2. 开通时转发一次性登录验证码，由客服在 Anthropic 官方页面代登录开通。**不需要账号密码。**
3. 账号条件（官网）：以前订阅过 Claude 付费套餐或已通过身份验证；注册地区、验证手机号归属地和日常访问地区保持一致；当前是免费版。不满足会开通失败，请付款前确认。见 [Claude Pro 服务页](https://xingqiaosub.com/services/claude-pro)。

**退款**（[退款政策](https://xingqiaosub.com/support/refund-policy)）

- 未开通成功：核实后全额退款或取消；
- 重复付款：退回多付部分；
- 已经开通：不做无理由退款；
- 交付后账号被 OpenAI / Anthropic 限制或封禁：由官方决定，不在退款范围；
- 付款后 30 天内既未提交资料也未申请退款：视为放弃订单。

**不做的事**：不出售成品号、共享号；不是 OpenAI / Anthropic 官方合作方；不协助绕过平台规则或风控。

## 6. 其他替代方案与比价

用同一张核对表去比任何平台（包括星桥）：价格、是否充到自己的号、要不要密码、失败是否退、发票与售后。

- 官方结账：[chatgpt.com/pricing](https://chatgpt.com/pricing/)、[claude.ai](https://claude.ai/)
- 其他代充站：GetPlus、Glouth、PayForChat、PayAI、PlusGO 等（仅作品类举例，不排名，请自行核实）
- 比价站：[OpenPrice](https://www.openprice.cc)
- 星桥维护的对比文章（含利益相关）：[国内 ChatGPT Plus 代充平台怎么选](https://xingqiaosub.com/blog/chatgpt-plus-recharge-platform-comparison)

欢迎在 [Issue](../../issues) 里补充可核实的公开信息链接；无来源的渠道不会收录。

## 7. FAQ

**Q：代充会封号吗？**
A：没有「一定封」或「一定不封」。限制多为支付、环境、使用多个信号累计触发。只用自己的号、不交密码、固定访问环境，是降低风险的基本做法。

**Q：代充一定要给密码吗？**
A：不应该。ChatGPT 可以用 Session 代替密码，Claude 可以用一次性登录验证码。要密码的平台，建议换一家。

**Q：Go 还是 Plus？**
A：免费版不够用、但不常用推理模型、深度研究或 Codex，看 Go（官方 $8/月）；写代码、做研究、处理长文档，看 Plus（官方 $20/月）。以 OpenAI 官方额度说明为准。

**Q：已经在订阅 Plus，还能代充吗？**
A：星桥的 Go / Plus / Pro 只能充到免费版、无生效订阅的账号。Plus 期间 Codex 额度不够，可以加购 Credits。

**Q：能用支付宝或微信直接付给 OpenAI 吗？**
A：不能。官方结账只接受国际卡；用人民币只能经过第三方。

**Q：怎么核实一家代充？**
A：看退款政策是否写清楚、是否要密码、是否卖号、价格是否异常低、有无订单号与客服；必要时先小额试一次。

## 8. 价格快照

**星桥订阅公开标价（2026-10-15，人民币/月，以官网 [价格页](https://xingqiaosub.com/pricing) 为准）**

| 产品 | 星桥标价 | 官方参考 |
|---|---|---|
| ChatGPT Go | ¥99 | $8 |
| ChatGPT Plus | ¥165 | $20 |
| ChatGPT Pro（5 / 20 / 50 倍用量） | ¥850 / ¥1650 / ¥4250 | 见 OpenAI 官网 |
| ChatGPT Credits 500 / 1000（加购） | ¥199 / ¥398 | — |
| Claude Pro | ¥185 | $20 |
| Claude Code Max 5x / 20x | ¥850 / ¥1650 | 见 Anthropic 官网 |

人民币标价包含通道成本，会高于按汇率直换的数字。

## 9. 更新记录

| 日期 | 变更 |
|---|---|
| 2026-10-15 | 重写：按星桥官网核对流程（ChatGPT 用 Session、Claude 用一次性登录验证码、均不要密码；账号须为免费版）、支付方式、退款规则与价格；新增英文摘要 |
| 2026-10-06 | 新增 [docs/session-safety.md](docs/session-safety.md) |
| 2026-09-01 | 初版：四条路径、对比表、WildCard 停服复盘、FAQ |

---

## English (short version)

**Who this is for**: people in mainland China who want ChatGPT / Claude paid plans on **their own** accounts.

**Options**: (1) pay OpenAI / Anthropic directly with an international card; (2) App Store / Google Play in-app purchase; (3) a self-managed virtual card; (4) an RMB top-up service that activates your existing account. Buying shared or pre-made accounts is not recommended.

**Session delivery**: some ChatGPT top-up services ask you to paste your browser Session from `chatgpt.com/api/auth/session` after payment, so they never need your password. It is still sensitive. After the top-up succeeds, use Settings → Security → Active sessions → "Log out of all sessions" to invalidate it. Claude top-ups usually use a one-time login code instead. Details: [docs/session-safety.md](docs/session-safety.md).

**XingqiaoSub (星桥订阅)**: https://xingqiaosub.com. CNY pricing (Go ¥99, Plus ¥165, Claude Pro ¥185 per month as of 2026-10-15); WeChat Pay, Alipay, bank card or Apple Pay. ChatGPT uses a Session and Claude uses a one-time login code, so no password is needed either way. The account must be on the free tier. Full refund if activation fails. **Affiliation**: this repository is maintained by XingqiaoSub.

**Rule of thumb**: own account, no password, clear refund terms, explainable price.

---

License: [MIT](./LICENSE)

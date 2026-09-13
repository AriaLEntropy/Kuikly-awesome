# OpenSourceTalent 课题作业

## 基本信息

| 项目 | 内容 |
| --- | --- |
| ⭐ GitHub ID | [@zeriehan](https://github.com/zeriehan) |
| ⭐ 完成的 Task | Task 1 与 Task 2 |

---

## 代码仓库

| 项目 | 链接 |
| --- | --- |
| ⭐ 仓库地址 | https://github.com/zeriehan/KuiklyStock |

仓库为公开仓库，9 月 14 日当天可正常访问。

clone 后用 Android Studio 打开即可运行，**不需要申请任何 Key、也不需要新建配置文件** —— 仓库里带了一个共享的智谱 GLM 免费池 Key，AI 部分直接就是真模型。详细步骤见仓库 README 的「本地运行（Android）」一节。

- 演示视频：https://www.bilibili.com/video/BV1PWYE6LEke
- 免构建安装包：https://github.com/zeriehan/KuiklyStock/blob/main/KuiklyStock-debug.apk

---

## 课程说明

**Task 1 · AI 行情原型**：完成行情、自选、个股与板块详情、多股对比、开始选股等模块，共 13 个页面。行情数据接的是腾讯、新浪、东方财富三个真实接口，覆盖大盘指数、板块、个股榜单、K 线、分时与 F10 基本面。

**Task 2 · AI 股票问答**：接入智谱 GLM 免费池，实现真正的 SSE 流式输出。AI 回复支持富文本渲染，提到的股票会生成可点开的迷你走势卡；走势图可以点选任意一个点后追问 AI，做到「看哪根 K 线就问哪根」；AI 分析还会给出风险档与买卖建议的结论徽章。

此外做了一块超出题目要求的功能：**让 AI 直接操作 App**。用户用自然语言说「把主题色改成蓝色」「给茅台设个跌破 1300 的预警」「宁德时代加进自选」，模型自行判断意图并真实执行，共支持 9 个操作。

项目为个人独立开发。13 个页面全部写在 Kuikly 共享层（`shared/src/commonMain`），Android 宿主只负责桥接平台能力。完整说明、架构与演示视频见仓库 README 与 `架构说明.md`、`亮点与创新.md`。

---

## 功能展示

| AI 聊天 + AI Agent | 个股详情 |
| :---: | :---: |
| ![AI 聊天与 Agent](https://raw.githubusercontent.com/zeriehan/KuiklyStock/main/docs/screenshots/01-ai-chat-and-agent.jpg) | ![个股详情](https://raw.githubusercontent.com/zeriehan/KuiklyStock/main/docs/screenshots/02-stock-detail.jpg) |
| **多股对比** | **自选与个性化** |
| ![多股对比](https://raw.githubusercontent.com/zeriehan/KuiklyStock/main/docs/screenshots/03-compare.jpg) | ![自选](https://raw.githubusercontent.com/zeriehan/KuiklyStock/main/docs/screenshots/04-watchlist.jpg) |

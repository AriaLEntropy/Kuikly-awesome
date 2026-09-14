# OpenSourceTalent 课题作业

## 基本信息

| 项目 | 内容 |
| --- | --- |
| ⭐ GitHub ID | [@MKX-1](https://github.com/MKX-1) |
| ⭐ 完成的 Task | Task 1 |

## 代码仓库

| 项目 | 链接 |
| --- | --- |
| ⭐ 仓库地址 | https://github.com/MKX-1/kuiklyDemo |

## 课程说明

本项目完成了 Task 1：基于 Kotlin Multiplatform、Kuikly（Compose DSL）与 MVVM
实现 AI 股票行情助手。行情总览、个股详情（分时 / 60分 / 日K / 周K / 月K 蜡烛图，
Canvas 自绘并支持十字光标与跨度缩放）、AI 分析等业务全部收敛在 KMP shared 模块；
数据侧提供自建 Ktor 后端（腾讯行情归一化代理 + 因子计算），并接入阿里云百炼
qwen 大模型生成 AI 分析结论，按「大模型 → 规则引擎 → 样例数据」三级降级，
结论来源在界面如实标注。客户端支持市场维度切换、分组展示与下拉刷新。

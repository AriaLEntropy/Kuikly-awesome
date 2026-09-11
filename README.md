# Kuikly-awesome

> Kuikly is a Kotlin Multiplatform based cross-platform native rendering framework.
> It enables developers to write one set of Kotlin code and deploy across Android, iOS, Web, MiniProgram and more platforms.
> 
> 📝 A curated list of awesome Kuikly libraries, projects, articles and resources.
> 
> **[KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI)**: A Kotlin Multiplatform UI framework from Tencent TDS — high-performance, one codebase for six platforms, with dynamic delivery.
> 
> 本仓库精选 Kuikly 相关库、开源项目、技术文章与学习资源。

## 📚 Kuikly Resources

## 🎓 OpenSourceTalent 课题作业提交指南

本目录用于收录 OpenSourceTalent 计划中学员的课题作业。请按照下面的规范提交 Pull Request，方便统一管理与展示。

### 📁 目录结构

每位学员**单独一个目录**，**目录名使用你的 GitHub ID**，目录内包含一个 `README.md`：

```
OpenSourceTalent/
├── _example/                  # 示例模板，请复制后改名
│   └── README.md
└── GithubId/                  # 你的 GitHub ID
    └── README.md              # 作业说明（必需）
```

> **目录名 = 你的 GitHub ID**，即个人主页地址里的用户名。
> 例如主页是 `https://github.com/GithubId`，目录就命名为 `GithubId`。

### 📝 文件内容

直接复制 [`OpenSourceTalent/_example/README.md`](./OpenSourceTalent/_example/README.md) 的内容填写。

**必需字段**

| 字段            | 说明                                                  |
| ------------- | --------------------------------------------------- |
| **GitHub ID** | 你的 GitHub 用户名（**必须与目录名一致**）                         |
| **代码仓库链接**    | 你的项目 GitHub / Gitee 地址（**必须有，且须在 9 月 14 日当天可公开访问**） |
| **课程说明**      | 简要说明完成的是哪个 Task、实现了什么                               |

> 一个 `README.md` 说清「**谁、做了哪个 Task、代码在哪**」即可，不必长篇大论。
> 
> 注：你的仓库的 `README.md` 和 文档 要详细！！！

### 🚀 提交步骤

**1. Fork 并克隆仓库**

```bash
# 在 GitHub 上 Fork Kuikly-contrib/Kuikly-awesome
git clone https://github.com/GithubId/Kuikly-awesome.git
cd Kuikly-awesome
```

**2. 基于目标分支创建你的分支**

```bash
git fetch origin
git checkout -b submit/GithubId origin/Tencent/OpenSourceTalent
```

**3. 创建目录并填写作业**

```bash
mkdir -p OpenSourceTalent/GithubId
# 把 _example/README.md 复制过去，按模板填写
cp OpenSourceTalent/_example/README.md OpenSourceTalent/GithubId/README.md
```

**4. 提交并推送**

```bash
git add OpenSourceTalent/GithubId
git commit -m "feat(OpenSourceTalent): GithubId finish Practical Project"
git push origin submit/GithubId
```

**5. 发起 Pull Request**

在 GitHub 上创建 PR，注意目标分支选择 **`Tencent/OpenSourceTalent`**。

### ✅ PR 规范

| 项目    | 要求                                     |
| ----- | -------------------------------------- |
| PR 标题 | `[OpenSourceTalent] GithubId - Task 1` |
| 目标分支  | `Tencent/OpenSourceTalent`             |
| 源分支   | 建议以 `submit/<你的 GitHub ID>` 命名         |
| 改动范围  | **只新增自己的目录**，不要修改他人目录或仓库其他文件           |

PR 描述里请附上你的代码仓库链接，方便 reviewer 查看。

### ⚠️ 注意事项

1. **一个 PR 只提交自己的作业**，不要顺手改动别人的内容或仓库配置。
2. **目录名统一使用 GitHub ID**，只包含字母、数字和连字符，不要使用中文、空格或其他特殊符号。
3. **代码仓库链接必须可公开访问，并确保在 9 月 14 日当天可正常打开**（私有仓库请提前转为公开，或提供可访问的镜像地址）。逾期未开放的仓库将无法查看，视同未提交。

# Vibe Coding 项目实战

![K12](https://img.shields.io/badge/%E5%AE%9A%E4%BD%8D-%E9%AB%98%E4%B8%AD%E4%BF%A1%E6%81%AF%E7%A7%91%E6%8A%80%E8%AF%BE%E5%A0%82-blue) ![课标](https://img.shields.io/badge/%E5%AF%B9%E6%A0%87-%E5%BF%85%E4%BF%AE1%E3%80%8A%E6%95%B0%E6%8D%AE%E4%B8%8E%E8%AE%A1%E7%AE%97%E3%80%8B-green) ![许可证](https://img.shields.io/badge/License-MIT-yellow)

> 🏫 **国内首个面向高中信息科技课堂的 AI 辅助编程（Vibe Coding）实战课程**——对齐《普通高中信息科技课程标准》必修1《数据与计算》。学生通过自然语言与 AI 对话，从零完成 3 个递进式实战项目，理解"提出需求 → 生成代码 → 验证迭代"的现代开发范式。
>
> ✨ **差异化定位**：现有 Vibe Coding 教程（如 datawhalechina/vibe-vibe）均面向成人开发者，本课程专为 K12 课堂设计——含课标对照、三维过程性评价、分层任务卡与课堂实施预案，零开发环境依赖，浏览器即可上课。

## 课程定位

| 项目 | 主题 | 对应课标 | 难度 |
|------|------|----------|------|
| 01 猜数字游戏 | 第一个 AI 生成程序：循环、判断、随机数 | 必修1《数据与计算》- 算法与程序实现 | ⭐ |
| 02 二进制转换器 | 人机交互界面：进制运算与网页交互 | 必修1 - 数据编码 | ⭐⭐ |
| 03 班级数据看板 | 数据可视化：读取数据、图表呈现 | 必修1 - 数据分析与呈现 | ⭐⭐⭐ |

## 什么是 Vibe Coding

Vibe Coding 是 2025 年由 Andrej Karpathy 提出的开发方式：**用自然语言描述需求，让 AI 生成代码，开发者专注于描述、验证和迭代**，而非逐行手写。

核心循环：

```
描述需求 → AI 生成 → 运行验证 → 反馈修改 → 重复迭代
```

学生仍然需要掌握：需求拆解、算法思想、代码阅读、调试验证 —— AI 负责"手"，学生负责"脑"。

## 目录结构

```
vibe-coding-practice/
├── docs/                    # 讲义
│   ├── 01-什么是Vibe-Coding.md
│   ├── 02-Prompt提问技巧.md
│   └── 03-课堂实施建议.md
└── projects/                # 3 个实战项目（每个都是单文件，双击即可运行）
    ├── 01-猜数字游戏/
    ├── 02-二进制转换器/
    └── 03-班级数据看板/
└── tools/                   # 课堂配套工具
    └── 作品收集评价系统.html  # 学生提交 + 教师三维评分 + 成绩导出（单文件，本地运行）
```

## 快速开始

1. 打开任意 AI 编程工具（如 GitHub Copilot、ChatGPT、文心一言等）
2. 参考 `docs/02-Prompt提问技巧.md` 中的模板向 AI 提问
3. 将生成的代码粘贴到对应项目的 `index.html` 中，用浏览器打开验证
4. 每个项目目录下的 `README.md` 含分步任务卡与验收标准

## 环境要求

- 浏览器（Chrome / Edge 均可）
- 可访问的 AI 对话工具
- 无需安装任何开发环境 ✅

## 教学建议

- 课时安排：3 课时（每项目 1 课时），也可拆为 6 个 45 分钟小节
- 评价方式：以"需求描述质量 + 验证迭代次数 + 最终作品"三维评价
- 参见 `docs/03-课堂实施建议.md`

## 作品收集与评价

配套工具 `tools/作品收集评价系统.html`（单文件，双击即用，数据存本机浏览器）：

- 🎓 **学生端**：填写姓名/班级/项目、Prompt 使用记录与验证迭代记录后提交，可重复提交自动更新
- 📝 **教师端**：密码进入（默认 `teacher`，可修改），按三维评价滑杆打分（30+30+40），自动算总分等级
- 📊 **成绩总览**：提交数、已评数、班级平均分、最高分与成绩明细表
- 💾 **数据管理**：JSON 导出/导入合并、成绩 CSV 导出（Excel 直开）、修改密码、清空数据

## 相关资源

- [datawhalechina/vibe-vibe](https://github.com/datawhalechina/vibe-vibe) — Datawhale 系统性 Vibe Coding 教程（面向成人开发者，可作为教师备课参考）
- [FidStyle/Vibe-Coding-Practical-Handbook](https://github.com/FidStyle/Vibe-Coding-Practical-Handbook) — 从入门到项目实战手册

## License

MIT

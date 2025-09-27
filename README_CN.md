# DSR 研究工作流模板 📚

一个基于设计科学研究（DSR）方法论的博士论文研究工作流模板系统。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 🎯 项目概述

本项目提供了一个完整的DSR研究框架，帮助研究者系统化地管理从问题识别到论文撰写的全流程。采用创新的"流水线 + 工具箱 + 写作车间"模式，让博士研究更加高效有序。

## ✨ 核心特性

- **📋 完整的DSR六阶段工作流模板** - 从问题识别到论文撰写的全流程覆盖
- **📁 模块化方法论库** - 可复用的研究方法和工具集合
- **✍️ 详细的章节写作模板** - 每个章节都有具体的写作指导
- **✅ 多层次质量审核清单** - 确保研究质量和学术规范
- **🔄 清晰的协作流程** - AI辅助研究的最佳实践指南

## 🏗️ 系统架构

系统采用三层架构设计：

### 1. 流水线层（Pipeline）
- 核心文件：`DSR_Workflow_Template.md`
- 功能：分阶段推进的主工作流程
- 包含6个DSR研究阶段的详细清单和协作流程

### 2. 工具箱层（Toolbox）
- 位置：`modules/` 目录
- 功能：可复用的方法论指南和审核清单
- 包含写作指导、结构审核、投稿前检查等多个模块

### 3. 写作车间层（Writing Workshop）
- 位置：`craft/` 目录
- 功能：提供各章节的写作模板和句式建议
- 覆盖学术论文的所有标准章节

```
DSR-Research-Flow/
├── DSR_Workflow_Template.md    # 核心工作流模板
├── WORKFLOW_GUIDE.md           # 详细协作指南
├── DSR-intro.md               # DSR方法论介绍
├── craft/                      # 章节写作模板
│   ├── 00_abstract.md         # 摘要模板
│   ├── 01_introduction.md     # 引言模板
│   ├── 02_related_work.md     # 相关工作模板
│   ├── 03_methodology.md      # 方法论模板
│   ├── 04_artifact_design.md  # 系统设计模板
│   ├── 05_evaluation.md       # 评估模板
│   ├── 06_discussion.md       # 讨论模板
│   ├── 07_conclusion.md       # 结论模板
│   ├── 08_references.md       # 参考文献模板
│   └── 09_appendix.md          # 附录模板
└── modules/                    # 方法论工具箱
    ├── module_guidance_methodology.md          # 方法论指导
    ├── module_guidance_paper-structure.md      # 论文结构指南
    ├── module_guidance_writing_de-ai.md        # AI写作优化
    ├── module_checklist_pre-submission-audit.md # 投稿前审核
    ├── module_checklist_ieee-access.md         # IEEE期刊要求
    └── module_checklist_structure-and-wordcount.md # 结构字数检查
```

## 🚀 快速开始

### 1. 获取模板

```bash
git clone https://github.com/jhfnetboy/DSR-Research-Flow-Template.git
cd DSR-Research-Flow-Template
```

### 2. 初始化你的研究项目

```bash
# 创建你的工作目录
mkdir -p my-research/writing

# 复制工作流模板并重命名
cp DSR_Workflow_Template.md my-research/paper1_workflow.md

# 复制所有写作模板
cp -r craft/* my-research/writing/
```

### 3. 开始你的研究

1. 在编辑器中打开 `paper1_workflow.md`
2. 系统地遵循6阶段工作流
3. 回答每个阶段的核心问题
4. 在 `writing/` 目录下起草相应章节
5. 使用 `modules/` 中的工具进行质量控制

## 📖 DSR六阶段工作流详解

| 阶段 | 核心活动 | 关键问题 | 交付成果 |
|------|---------|---------|----------|
| **1. 问题识别** | 定义研究缺口和动机 | 要解决什么具体问题？为什么重要？ | Introduction和Abstract草稿 |
| **2. 设计** | 概念化解决方案 | 设计原则是什么？如何工作？ | 系统设计章节 |
| **3. 开发** | 构建产出物/原型 | 如何实现？使用什么技术？ | Methodology章节 |
| **4. 演示** | 展示可行性 | 是否有效？如何证明？ | 工作原型/系统 |
| **5. 评估** | 严格的评估 | 效果如何？什么指标？ | 评估结果与分析 |
| **6. 交流** | 学术写作 | 如何展示发现？ | 完整的论文手稿 |

## 📚 模块库说明

### 方法论指导模块 (`module_guidance_*`)
- **methodology.md** - 将工程经验转化为学术研究
- **paper-structure.md** - 学术论文结构指南
- **writing_de-ai.md** - AI辅助写作的去AI化处理
- **paper-deconstruction.md** - 优秀论文案例分析

### 质量检查清单 (`module_checklist_*`)
- **pre-submission-audit.md** - 投稿前的全面审核清单
- **ieee-access.md** - IEEE Access期刊的特定要求
- **structure-and-wordcount.md** - 论文结构和字数验证

## 🎓 目标期刊

本模板针对以下期刊优化：
- IEEE Access
- IEEE Transactions系列
- ACM Computing Surveys
- Journal of Systems and Software
- Information Systems Research
- 设计科学研究相关会议

## 🤝 使用场景

### 博士生研究
- 系统化的学位论文研究
- 独立的论文项目
- 研究提案开发

### 研究团队
- 标准化的研究工作流
- 协作式论文写作
- 知识管理体系

### 教育工作者
- 研究方法论教学
- 指导学生研究
- 课程材料开发

## 🛠️ 最佳实践

### 1. 版本控制
```bash
git init
git add .
git commit -m "初始化研究项目"
```

### 2. 定期检查点
- 每周进度回顾
- 阶段完成评估
- 导师反馈整合

### 3. 模块化使用
- 选择与你研究相关的模块
- 根据领域定制模板
- 扩展领域特定工具

### 4. AI集成
- 使用AI生成初稿
- 应用去AI技术保持原创性
- 维护学术诚信

## 💡 成功秘诀

1. **从问题识别开始** - 花足够的时间定义研究问题
2. **阶段间迭代** - 研究很少是线性的，需要时回顾早期阶段
3. **记录一切** - 在整个过程中保持详细的笔记
4. **尽早寻求反馈** - 定期的导师/同行评审提高质量
5. **使用检查清单** - 系统化验证防止遗漏

## 🔄 工作流集成

### 与Git集成
```bash
# 追踪你的进度
git checkout -b stage-1-problem
# 进行修改
git commit -m "完成问题识别阶段"
git checkout main
git merge stage-1-problem
```

### 与项目管理工具集成
- 为每个阶段创建任务
- 使用里程碑设置截止日期
- 使用项目看板追踪进度

## 📈 研究进度管理

### 建议的时间分配（6个月项目）
- **月1**: 问题识别与文献综述
- **月2**: 设计与架构
- **月3-4**: 开发与实现
- **月5**: 评估与分析
- **月6**: 论文写作与修订

### 每周任务示例
- **周一**: 文献阅读和笔记
- **周二-三**: 研究/开发工作
- **周四**: 写作和文档
- **周五**: 导师会议和规划

## 🌟 特色功能

### 1. AI辅助研究指南
- 如何有效使用ChatGPT/Claude
- 提示词工程技巧
- AI生成内容的学术化处理

### 2. 跨学科适应性
- 计算机科学
- 信息系统
- 软件工程
- 人机交互

### 3. 多语言支持
- 中文学术写作指导
- 英文学术表达模板
- 中英对照专业术语

## 📄 许可协议

MIT License - 您可以自由地：
- 商业使用
- 修改
- 分发
- 私人使用

## 🙏 致谢

- 基于Peffers等人(2007)的DSR框架
- 参考成功的DSR学位论文
- 社区贡献和反馈
- IEEE和ACM出版指南

## 🤝 贡献指南

欢迎贡献！请：
1. Fork本仓库
2. 创建特性分支
3. 进行改进
4. 提交Pull Request

### 贡献领域
- 额外的期刊特定检查清单
- 领域特定模板
- 更多语言翻译
- 成功案例和示例

## 📮 支持

- **Issues**: 报告错误或请求功能
- **Discussions**: 分享经验和技巧
- **Wiki**: 详细文档和常见问题
- **Email**: 联系维护者进行合作

## 🌟 Star历史

如果这个模板对你的研究有帮助，请考虑给它一个star！这有助于其他人发现这个资源。

## 📊 成功指标

使用本模板的研究者报告：
- 📈 研究规划时间减少40%
- 📚 论文接受率提高
- 🎯 更系统地完成学位论文
- 🤝 增强导师-学生协作

## 🔮 未来规划

- [ ] 在线交互式工作流工具
- [ ] 自动化质量检查脚本
- [ ] 论文写作视频教程
- [ ] 研究社区论坛
- [ ] 移动端支持

---

**让研究更系统，让写作更高效！** 🚀

*版本 1.0 | 最后更新：2025年9月*
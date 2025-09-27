# DSR Research Flow Template 📚

一个基于设计科学研究(DSR)方法论的博士论文研究工作流模板系统。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 项目简介

本项目提供了一个完整的DSR研究框架，帮助研究者系统化地管理从问题识别到论文撰写的全流程。采用"流水线 + 工具箱 + 写作车间"的创新模式，让博士研究更加高效有序。

## ✨ 核心特性

- **📋 完整的DSR六阶段工作流模板** - 从问题识别到论文撰写的全覆盖
- **📁 模块化方法论库** - 可复用的研究方法和工具
- **✍️ 详细的章节写作模板** - 每个章节都有具体指导
- **✅ 多层次质量审核清单** - 确保研究质量
- **🔄 清晰的协作流程** - AI辅助研究的最佳实践

## 🏗️ 系统架构

```
DSR-Research-Flow/
├── DSR_Workflow_Template.md    # 核心工作流模板
├── WORKFLOW_GUIDE.md           # 详细协作指南
├── craft/                      # 章节写作模板
│   ├── 00_abstract.md
│   ├── 01_introduction.md
│   └── ...
└── modules/                    # 方法论工具箱
    ├── module_guidance_*.md
    └── module_checklist_*.md
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

# 复制工作流模板
cp DSR_Workflow_Template.md my-research/paper1_workflow.md

# 复制写作模板
cp -r craft/* my-research/writing/
```

### 3. 开始研究

1. 打开 `paper1_workflow.md`
2. 按照六阶段逐步推进
3. 使用 `modules/` 中的工具进行质量控制

## 📖 DSR六阶段工作流

| 阶段 | 任务 | 产出 |
|------|------|------|
| 1. 问题识别 | 定义研究问题和动机 | Introduction草稿 |
| 2. 设计 | 设计解决方案 | System Design章节 |
| 3. 实验设计 | 制定评估方案 | Methodology章节 |
| 4. 执行 | 实施和数据收集 | 实验数据和图表 |
| 5. 分析 | 结果分析和讨论 | Results & Discussion |
| 6. 写作 | 整合和润色 | 完整论文 |

## 📚 模块说明

### 方法论指导 (Guidance Modules)
- `module_guidance_methodology.md` - 工程背景研究方法
- `module_guidance_paper-structure.md` - 论文结构指南
- `module_guidance_writing_de-ai.md` - AI辅助写作优化

### 审核清单 (Checklist Modules)
- `module_checklist_pre-submission-audit.md` - 投稿前审核
- `module_checklist_ieee-access.md` - IEEE期刊要求
- `module_checklist_structure-and-wordcount.md` - 结构与字数

## 🤝 使用场景

- 📊 博士生论文研究
- 🔬 设计科学研究项目
- 📝 系统化学术写作
- 🎓 研究方法教学

## 🛠️ 最佳实践

1. **版本控制** - 使用Git追踪研究进展
2. **定期备份** - 保护研究成果
3. **模块化使用** - 灵活调用工具箱
4. **AI辅助** - 结合AI工具提升效率

## 📄 许可证

MIT License - 自由使用、修改和分发

## 🙏 致谢

- 基于Peffers等人的DSR框架
- 参考了IEEE Access等期刊要求
- 感谢所有贡献者

## 📮 联系与支持

- 提交Issue报告问题
- Pull Request贡献改进
- Star支持项目发展

---

**让研究更系统，让写作更高效！** 🚀

*最后更新：2025年9月*
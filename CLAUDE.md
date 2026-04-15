# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库用途

这是一个 **Claude Code 配置模板库**，存放项目中常用的 CLAUDE.md 文件，方便在新项目中快速复用。

## 文件说明

| 文件 | 用途 |
|------|------|
| `coding-md.md` | 通用编码规范（语言无关） |
| `python-md.md` | Python 项目指南（uv/ruff/pyrefly/pytest） |

## 工作流约定

**代码版本管理**：涉及 git 操作（提交、分支、推送等）时，**必须使用 `git-commit-manager` 子代理**，不要直接执行 git 命令。

## 用户偏好

- **`.gitignore` 不提交到仓库** — 仅本地使用
- 提交消息遵循 Conventional Commits：`type: 描述`
- 分支命名：`feat/xxx`、`fix/xxx`、`refactor/xxx`

## 远端仓库

- `origin` → `https://github.com/hukaiedu/ClaudemdRep.git`

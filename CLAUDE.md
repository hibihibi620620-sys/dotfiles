# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment

- **OS**: Windows 11, shell: bash (Git Bash / WSL syntax)
- **Git identity**: hibihibi620620-sys (hibihibi620620@gmail.com)

## Active Repository

`Documents/life/` — personal planning repo (Markdown files, no build system).

## Python Scripts

Standalone learning scripts on Desktop and Downloads (`hello.py`, `omikuji.py`, `bmi.py`, `turtle3.py`). Run directly with `python <file>`.

## Jupyter Notebooks

Located in `Downloads/`. Open and run with `jupyter notebook` or VS Code's notebook viewer.

## Integrations

- **Notion MCP** is configured — use `mcp__notion-mcp__*` tools to read/write Notion pages when the user references Notion.

## 基本ルール

- 必ず日本語で応答する
- 技術的な用語は非エンジニア向けに補足説明を入れる

## 情報の置き場所

- プロジェクト情報・タスク・議事録はすべてNotionに置く
- ローカルには「Claudeへの指示」と「技術的な設定」だけを置く

## MEMORY.mdに書いていい情報のルール

- ✅ 書いていいもの：技術スタック、API仕様、MCPの接続先情報
- ❌ 書いてはいけないもの：プロジェクト固有の情報、一時的なタスク、案件の要件

## セッション中の作業状態管理

- Notionページが渡された場合 → そのページに作業ログを書く
- 渡されていない場合 → 以下のページを使う
  - アクティブコンテキストページ: https://www.notion.so/328f7a6af93b80dca84fc83ae44a711a

### ログの書き方ルール

- 書く前に必ずページを読む
- 「現在の状態」セクションは追記せず全面書き直し
- 古い状態と新しい状態を並存させない

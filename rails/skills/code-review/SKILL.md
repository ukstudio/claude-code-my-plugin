---
name: code-review
description: Railsプロジェクトのコードレビューを実行する。mainブランチとの差分に対してベストプラクティスに基づくレビューを行う。
---

# Rails Code Review

mainブランチとの差分を確認し、Railsのベストプラクティスに従ってコードレビューを行います。

## 実行手順

1. `git diff main...HEAD` を実行してdiffを取得
2. 変更されたファイルの内容を確認
3. 以下の観点からレビューコメントを作成
4. 問題点がある場合は具体的な改善案を提示

@../templates/code-review-guidelines.md

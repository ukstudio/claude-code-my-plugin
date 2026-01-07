---
description: $ARGUMENTSブランチとのdiffを確認し、Railsのベストプラクティスに従ってコードレビューを行う
---

# Rails Code Review

指定されたブランチ（デフォルト: main）との差分を確認し、コードレビューを行ってください。

## 実行手順

1. `git diff $ARGUMENTS...HEAD` を実行してdiffを取得
2. 変更されたファイルの内容を確認
3. 以下の観点からレビューコメントを作成
4. 問題点がある場合は具体的な改善案を提示

@../templates/code-review-guidelines.md

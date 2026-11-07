# claude-codex-lab

Claude Code と Codex を連携させた開発フローを試し、育てるためのリポジトリです。

## 流れ

1. Claude Code がブランチを切って実装し、PRを出す
2. Codex がPRをレビューする（`@codex review` とコメント、または自動レビュー）
3. Claude Code が指摘に対応する
4. 人間が確認してマージする

ルールの詳細は [AGENTS.md](./AGENTS.md) を参照してください。

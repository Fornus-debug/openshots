# CLAUDE.md

## 共通開発コンテキスト（AI必読）
- 作業前に AGENTS.md / CLAUDE.md と docs/project-context.md, docs/todo.md, docs/decisions.md, docs/handover.md を確認する。
- 共通正本: https://github.com/Fornus-debug/github-context-collector/blob/main/docs/ai-development-policy.md
- 正本が読めなくても、根本原因検証、最小変更、機密情報保護、外部APIの件数/時間/並列上限、正常0件とエラーの区別、本番相当の認証/DB/HTTP確認を守る。
- 難易度/推奨モデル→現状→影響→作業。ユーザー向けコマンドは1つずつ。削除・課金・公開・本番データ操作・外部送信は事前承認、rm禁止。
- 変更後に実行した検証と未実施項目、docs更新案、失敗候補を記録する。既存の固有ルールは優先。private情報をpublicへ持ち込まない。

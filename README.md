# UNTOLD Promotion

UNTOLDのプロモーション運用専用リポジトリ。

このリポジトリは、ゲーム本編の仕様正本 `fg79sw4nvw-dot/untold-wiki` とは独立して管理する。
ゲーム仕様・世界設定・ストーリー・実装判断の根拠として、このリポジトリを使用してはならない。

## 役割

- SNS公式人格の管理
- SNS運用方針の管理
- 投稿企画・キャンペーンの管理
- 公開済み情報の履歴管理
- 下書きの保管
- ChatGPTによるプロモーション運用の継続性確保

## 正本の関係

- `untold-wiki` = ゲームについての真実
- `untold-promotion` = その真実を、いつ・どこまで・どう見せるか

プロモーション側は必要に応じて `untold-wiki` を参照してよい。
ゲーム開発側は原則として `untold-promotion` を参照しない。

## 主要ファイル

- `AGENTS.md` — ChatGPT / AIエージェントの入口
- `ai-current.json` — 現在のプロモーション運用状態
- `persona/social-persona.md` — 公式SNS人格
- `strategy/social-operation.md` — SNS運用方針
- `social/publication-ledger.md` — 公開済み情報台帳
- `campaigns/` — 期間企画・キャンペーン
- `drafts/` — 未公開の投稿下書き

## 基本原則

1. ゲーム本編の設定を勝手に追加・変更しない。
2. 宣伝表現をゲーム内設定として扱わない。
3. 未公開情報は公開済み情報と明確に分離する。
4. ネタバレを避けるため、投稿前に公開台帳を確認する。
5. 実用情報（対応環境、更新、障害、公開日など）は世界観演出より明確さを優先する。

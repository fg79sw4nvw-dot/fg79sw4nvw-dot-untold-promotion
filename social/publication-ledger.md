# UNTOLD SNS 公開台帳

## 目的

SNS上ですでに何を公開したかを追跡し、
未公開情報との混同、重複投稿、意図しないネタバレを防ぐ。

## 状態区分

- `published` — 公開済み
- `scheduled` — 公開予定
- `draft` — 下書きのみ
- `retired` — 再利用しない

## 公開レベル

- `L0` — 一般情報。ネタバレなし
- `L1` — 軽い世界観・ゲーム情報
- `L2` — 発見の楽しみに少し影響する情報
- `L3` — ストーリー・条件・真相に関わる情報。原則慎重
- `L4` — 重大な真相・核心。通常のSNS投稿では公開しない

## 記録フォーマット

各投稿ごとに以下を記録する。

```md
### YYYY-MM-DD / ID
- platform:
- status:
- category:
- publicationLevel:
- title:
- summary:
- exactText:
- media:
- gameCanonSources:
- revealedFacts:
- deliberatelyHiddenFacts:
- spoilerNotes:
- reusable:
- campaign:
- url:
```

## 公開済み投稿

まだなし。

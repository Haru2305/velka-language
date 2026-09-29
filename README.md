# Velka Language

Velka語の設計・辞書・文法・コーパス・専門語彙を履歴管理するリポジトリです。

## Current status

- 基礎辞書: **v2.1**
- 辞書登録行: **913**
- ユニーク語形: **911**
- 歴史的固有語根: **128**
- 共時的な独立暗記単位: **162**
- L2専門語彙: **35ユニーク見出し**
- 語順: **SOV**

## Repository layout

```text
docs/
  dictionary/       現行辞書・語根監査
  grammar/          文法体系
  corpora/          実際のVelka語文章
  specialized/      分野別専門語彙
  audits/           語彙・運用監査
  design/           言語全体の設計規則
```

## Source of truth

GitHubを**履歴管理の中心**として使用します。

Google Driveは、作業用・閲覧用・バックアップとして併用します。
GitHub上では原則としてMarkdown版を管理し、変更はコミット履歴に残します。

## Lexicon layers

- **L0**: 基礎辞書
- **L1**: 生産的な透明複合
- **L2**: 分野別専門見出し
- **L3**: 国際記号・固有技術名

基礎辞書を専門語で過剰に肥大化させず、文章コーパスから必要性を確認して語彙を増やします。

## Development principle

1. 文章を先に作る
2. 表現できない概念を抽出する
3. 既存語・意味拡張・透明複合を優先する
4. 本当に必要な語だけを追加する
5. 複数領域で反復する語のみL0昇格を検討する
6. 専門限定語はL2へ置く
7. 変更をコーパスと監査で検証する

## Canonical documents

- `docs/dictionary/modern-dictionary-v2.1.md`
- `docs/dictionary/root-audit-v0.1.md`
- `docs/design/specialized-layer-v0.1.md`
- `docs/specialized/`
- `docs/corpora/`

---

This repository is under active development.

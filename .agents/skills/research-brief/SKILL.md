---
name: research-brief
description: "架空データを使う公開検証用の Skill。営業調査や選択肢の比較を、出典付きの短い調査メモにまとめる手順を検証するときに使用する。"
metadata:
  aachat.headline.ja: "公開検証：調査メモ"
  aachat.headline.en: "Publication Test: Research Notes"
  aachat.description.ja: "架空データを使う公開検証用。一次情報を優先し、指定条件で選択肢を比較して、要点・根拠・次のアクションを調査メモに整理する。"
  aachat.description.en: "For publication testing with fictional data. Prioritize primary sources, compare options against specified constraints, and organize conclusions, evidence, and next actions into research notes."
  aachat.discovery.listed: "true"
---

# 公開検証：調査メモ

架空データを使う公開検証用として、営業調査や選択肢の比較を短い調査メモにまとめる。

## 入力

調べるテーマ、読者、判断したいこと、比較する選択肢と評価基準を確認する。
予算・通貨・対象期間・期限など、比較に必要な条件は利用者の指定を使う。
未指定の会社名、担当者名、予算や社内ルールを推測して補わない。
結論を左右する不足情報は確認し、確認できない場合は未確認事項として明示する。

## 手順

1. 入力と調査範囲を整理する。
2. 一次情報を優先し、主張に対応する出典と確認日を記録する。参照できない情報を確認済みと扱わない。
3. 利用者が指定した条件と同じ評価基準で選択肢を比較し、利点・制約・不明点を整理する。
4. この Skill ディレクトリ内の [資料の書き方](references/report-format.md) に合わせ、要点、根拠、次のアクションを簡潔に書く。比較が必要な場合は根拠に比較表を添える。
5. 事実と仮説が区別され、不確かな記述が断定になっていないか確認する。担当者や期日が未定のアクションは確定事項にせず、要確認事項にする。出典にアクセスできなかった場合は未確認と明記する。

## 利用条件

同梱の書式以外に、専用スクリプトや元の作成者のリポジトリへのアクセスは不要。
調査には実行環境で利用できる検索・閲覧手段、または利用者が提供した資料を使う。
特定の外部サービスや API キーの設定は必須としない。
社内資料や顧客情報は利用者に閲覧・利用権限がある範囲で扱い、共有先に応じて固有名や非公開情報を匿名化・省略する。

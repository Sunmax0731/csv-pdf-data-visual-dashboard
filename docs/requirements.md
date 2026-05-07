# 要件定義

| 項目 | 内容 |
| --- | --- |
| Rank | 72 |
| Domain | WebApp |
| Idea No. | 6 |
| Repository | csv-pdf-data-visual-dashboard |
| 主な公開先 | GitHub Pages / GitHub Release |

## 背景

軽いデータ確認のために専用ツールを行き来する。

## 目的

CSV、PDF、OCR結果をドラッグして表やグラフに整える。 入力、確認、履歴保存、次アクションを同じ作業単位で扱えるようにする。

## 必須要件

- visualization dataset を複数件まとめて検証できる。
- required fields: `id`, `title`, `dataPath`, `schema`, `chartType`, `owner`。
- warning field: `sampleRows`。
- 代表シナリオ、QCDS metrics、docs ZIP、release evidence を再生成できる。

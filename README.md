# Mak.K

Workflow Automation / Business Process Improvement

EC運営やバックオフィス業務で発生する
手作業・待機時間・ヒューマンエラーの削減を目的として、
業務改善ツールの開発と運用設計を行っています。

---

## 📚 Published Book

### 実務者のためのAI業務改善ノート

「なんとなく面倒」を小さな自動化に変える考え方を、  
実務経験をもとにまとめたKindle書籍です。

[Amazonで見る]([本のURL](https://amzn.asia/d/066FyH8h))

---

## What I Do

* 業務フロー改善
* EC運用の自動化
* Web制作 / 実装（HTML / CSS / JavaScript）
* Python / C# / .NET による業務ツール開発
* ローカルAI活用による開発効率化

---

## Main Project

## Sales Aggregation Automation Tool

複数ECモールで発生する売上集計業務を自動化するために開発したツールです。

---

### ■ Background

売上集計業務では、

* CSVダウンロード
* Excel転記
* オートフィル
* 親品番集計
* SKU集計

などを手作業で行っており、多くの工数が発生していました。

さらに、

* 楽天市場
* Yahoo!ショッピング
* au PAY マーケット
* Amazon
* Qoo10
* dショッピング

それぞれでCSV形式や管理項目が異なるため、
担当者の経験に依存しやすい運用になっていました。

---

### ■ Solution

Pythonを利用し、

* CSVデータ読込
* Excel転記
* オートフィル
* 親品番集計
* SKU集計

を自動化しました。

また、

* pandas

  * CSVデータの読込・変換

* openpyxl

  * Excel転記・オートフィル処理

* YAML

  * モールごとの差分設定管理

* tkinter

  * 非エンジニア向けGUI作成

* logging

  * 実行結果・エラー内容の記録

を活用し、

* GUI操作
* ログ出力
* モール判定
* CSV取り違え防止

を実装しました。

---

### ■ Design Decisions

売上データを扱うため、
処理速度よりも安全性と運用性を重視しました。

* サイレントエラーを防ぐ
* 成功・失敗を問わずログを出力
* 最終確認は人間が行う
* CSV取り違えを防止
* 非エンジニアでも利用できるGUI
* モール追加を考慮したYAML設定

単なる作業自動化ではなく、
継続して運用できる仕組みづくりを重視しています。

---

### ■ Result

* 日次集計時間 約25分 → 約3分へ短縮見込み
* 月40時間規模の作業削減見込み
* 転記ミス削減
* 集計作業の標準化
* 属人化の解消

---

## Skills

### Development

* Python
* C#
* .NET
* HTML
* CSS
* JavaScript
* SQL

### Tools

* Git
* GitHub
* VS Code
* Photoshop

### Business

* EC運営
* 業務改善
* 運用設計
* 自動化
* ヒューマンエラー削減

---

## Development Philosophy

単に作業を自動化するのではなく、

* なぜその作業が必要なのか
* どこでミスが発生するのか
* 本当にその手順は必要なのか

を考えながら改善を行っています。

重視しているのは、

* 安全性
* 確認性
* 運用性

です。

完全自動化よりも、
継続して運用できる仕組みづくりを優先しています。

---

## Featured Projects

* Sales Aggregation Automation Tool
* CSV Upload Scheduler
* HTML Conversion Tool
* Local AI Coding Assistant

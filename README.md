# gBizINFO APIを用いた宮城県補助金データ分析パイプライン

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rioto3/gbizinfo-subsidy-analysis/blob/main/gbizinfo_miyagi.ipynb)



      
## プロジェクト概要

本プロジェクトは、gBizINFO APIを活用して宮城県の補助金データを収集・分析するためのデータサイエンスパイプラインです。特に、補助金受給の構造的な傾向を可視化することを目的としています。

## 使用方法

1. 上記のColabバッジをクリックしてノートブックを開きます。

2. APIトークンの設定:
   - セルの`API_TOKEN`変数に、自身のgBizINFO APIトークンを入力してください。

## 注意点

- APIトークンは個人で取得する必要があります。
- 生成されるCSVファイルおよびSQLiteデータベースは、必要に応じて別途保存してください。

## 出力データ

- `miyagi_subsidies.csv`: 補助金データ（法人名付き）
- `miyagi_subsidies_count.csv`: 補助金受給回数・総額集計データ
- `gbizinfo_miyagi.sqlite3`: SQLiteデータベースファイル

## 貢献方法

### バグ報告・機能改善

- GitHubの[Issues](https://github.com/Rioto3/gbizinfo-subsidy-analysis/issues)から新規Issueを作成してください。
- バグ報告の際は、できる限り詳細な情報（環境、エラーメッセージ、再現手順）を記載してください。

## ライセンス

MIT License

## 免責事項

このツールは情報提供のみを目的としており、特定の法的助言や財務分析を意図するものではありません。

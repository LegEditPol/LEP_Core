# 「法編」エディタ 開発資料
## 上メニュー

- ファイル
- 編集
- 挿入
- 実行
- 機能
- 校閲
- 開発
- ヘルプ

## 左タブ

- Lライブ共有 for 右列 1/3
- S検索と置換 for 右列 1/3
- Fファイル for 左列 1/1
- E編集 for 左列 1/1
- A挿入 for 右列 1/3
- E出力 for 右列 1/3
- F拡張機能 for 左列 1/1
- R実行 for 右列 1/3
- Mソース管理 for 左列 1/1
- S設定 for 右列 1/3

## 右タブ

- Source, ソース
- Edit up, 編集
- View for, プレビュー

## 標準ターミナル

LEPC: LegEditPol Commander

## マクロ自動制御

lep.exe -auto -sys ccmi

- Arguments

| Type | Argument | Definission | Notion |
|---|---|---|---|
| マクロ | -auto | マクロ自動制御の実行 | -run,-mfのいずれかを伴う |
| マクロ | -sys \<system interface key> | マクロ共通インタフェースの指定 | デフォルト：ccmi |
| マクロ | -run | マクロ | マクロ命令群 |
| マクロ | -mf | マクロ | マクロファイルの指定 |
| 設定 | -profile \<sub cmd> | ユーザプロファイルの作成・変更・削除 |  |
| 設定 | -cfg  \<sub cmd> | プロジェクト設定の作成・編集 |  |
| 設定 | -env  \<sub cmd> | レポジトリ設定の作成・編集 |  |
| 拡張機能 | -legmap | 法参照構造図の生成 | 可視化法学 |

- System Interface Key

| key | Name | Full Name | Leading Project |
|---|---|---|---|
| tuls | TULS | TRON Universal Language System | TRON Project, TRON Distr. |
| ccmi | CCMI | Common Command Macro Interface | Chetro Project, TRON Distr. |

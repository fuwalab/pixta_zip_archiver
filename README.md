# illust_stock_zip_archiver
このツールは Windows 向けの ZIP アーカイバーです。
同じ名前の `png` または `jpg` と `eps` があるとき、それらを ZIP で圧縮します。

## 対象
- PIXTA をお使いのイラストレーター
  - 提出時に `png`, `eps` を ZIP 圧縮するのが毎回面倒な方
- Adobe Stock をお使いのイラストレーター
  - 提出時に `jpg`, `eps` を ZIP 圧縮するのが毎回面倒な方
  
## 動作要件
- Windows 7 以上
- PowerShell version 5.0 以上

## 動作確認環境
- Windows 10 Pro 64 bit
- PowerShell version 5.1

## 使い方
1. 本ツールのダウンロード
    - [ここ](https://github.com/fuwalab/illust_stock_zip_archiver/releases) から、最新のリリース（ `zip` ）をダウンロード

### PIXTA の場合
1. 作業フォルダへの配置
    - 解凍してできた `archive` フォルダをそのまま `png`, `eps` ファイル群のある作業フォルダへコピー
        ![1](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/1.png)
1. スクリプトの実行
    1. `archive` フォルダへ移動する
    1. `archive_pixta.bat` をダブルクリックする
        ![2](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/2.png)
    1. 実行中
        - 処理が始まると自動で表示され、完了すると閉じます
          ![3](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/3.png)
1. ファイルの確認
    1. 一つ上の階層（作業フォルダ）に作成されている `zip` フォルダに移動する
       ![4](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/4.png)
       ![5](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/5.png)
    1. ファイルの中身を確認して正しく圧縮できていることを確認する
        ![6](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/6.png)
        
### Adobe Stock の場合
1. 作業フォルダへの配置
    - 解凍してできた `archive` フォルダをそのまま `jpg`, `eps` ファイル群のある作業フォルダへコピー
        ![1](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/1.png)
1. スクリプトの実行
    1. `archive` フォルダへ移動する
    1. `archive_adobe.bat` をダブルクリックする
        ![2](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/2.png)
    1. 実行中
        - 処理が始まると自動で表示され、完了すると閉じます
          ![3](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/3.png)
1. ファイルの確認
    1. 一つ上の階層（作業フォルダ）に作成されている `zip` フォルダに移動する
       ![4](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/4.png)
       ![5](https://raw.githubusercontent.com/fuwalab/illust_stock_zip_archiver/master/assets/5.png)

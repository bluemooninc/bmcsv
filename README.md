bmcsv
=====
csv export/import tool for xoops cube

Copyright : Bluemoon inc. 2013 All right reserved.
Author : Yoshi Sakai
Licence : GPL Version 3

You can Export/Import as CSV file for XOOPS Cube Style module.

## これは何？

B.M.CSV は、 XOOPS Cube 2.1以降のモジュール専用に書かれたインポート／エクスポート・ツールです。
このモジュールをインストールすると、XOOPS Cube ハンドラを持つモジュールの全てのテーブルがCSVでインポート・エクスポートする事が可能となります。

B.M.Cart モジュールでは、ショッピングカートの掲示用に沢山の商品を登録する必要がありました。これをブラウザで行うのは大変時間の掛かる作業です。
そこでマイクロソフト・エクセル等のワークシートで一覧編集して一度に大量のデータを投入する方法が求められました。

## 制限

ハンドラを参照しているので、旧来のXOOPS2や、Cube Styleではない旧式のモジュールでは動作しません。

現在は、１行目にヘッダ、データは必ず”（ダブルクォーテーション）で囲んで、項目は,（カンマ）区切りでなければなりません。


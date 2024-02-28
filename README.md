# dashboard_Population_ShizuokaCity
Population data provided as open data for Shizuoka City.

ダッシュボードの作成講座用のデータが取得できるための、リポジトリです。

静岡市にてオープンデータで提供されている人口データを加工したものです。

このリポジトリでは静岡市の以下の種類の人口データを格納しています。

      １．年月ごとの学区別人口データ
          ファイル名　221007_population_YYYYMM
          連合自治会・学区ごとの総数のデータがあります。男女別データはありません。
      ２．年度を結合した学区別人口データ
          ファイル名　221007_population_CombYear
          総数データがあり、男女別データはありません。
          
          ※221007は市区町村コードで静岡市を示します。
          ※YYYYMMは人口調査年月を西暦表示したものです。
          ※ファイル名の末尾がceはカラム名が日本語、ceはカラム名が英語を意味しています。
          
データ形式は以下です。

      csv
          
データセットはデジタル庁の自治体標準オープンデータセットの準拠し、記載のないものは独自定義しています。

[デジタル庁　自治体標準オープンデータセット](https://www.digital.go.jp/resources/open_data/municipal-standard-data-set-test/?fbclid=IwAR1AisrpdlBnTRR0QHrOXEPAv1wpC4MZxtdtu0KDWcd0cXUH9F-RNYibKVc)
<br>
<br>
<br>
このリポジトリの人口データを用いた人口ダッシュボードの作成方法として、以下のPDFが参考いただけます。<br>
ダッシュボードはLookerを利用しています。<br>
人口データがあれば、様々な自治体で人口ダッシュボードが作成できます。

      人口ダッシュボード作成講座資料.pdf  
<br>
<br>
ダッシュボードの作成例は以下のURLを参考してください。

[趣味で作った　静岡市人口ダッシュボード](https://lookerstudio.google.com/reporting/4b5f3d68-7f27-4c4e-9a50-253889ae45f6)

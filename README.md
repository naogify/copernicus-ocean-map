# Copernicus Sea Current Map

このリポジトリは[Copernicus Marine Service](https://data.marine.copernicus.eu/)が提供する海流データを、Geolonia地図上に可視化するシンプルなウェブページです。データセットは「[GLOBAL_ANALYSISFORECAST_PHY_001_024](https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_PHY_001_024/description)」に含まれるWMTSタイルを利用しています。

## 表示しているデータ
- 2025年5月23日 0時（UTC）時点の海水流速データ
- 深さおよそ50cmの表層データ
- WMTSの`sea_water_velocity`レイヤから取得

## 使い方
1. GeoloniaのAPIキーを取得して`index.html`内の`YOUR-API-KEY`を置き換えます。
2. `index.html`をブラウザーで開くだけで海流マップを表示できます。

## Attribution
データはEUのCopernicus Marine Serviceが提供する情報を使用しており、ファイル内で以下の帰属を表示しています。

```
<a href="https://doi.org/10.48670/moi-00016">Generated using E.U. Copernicus Marine Service Information</a>
```

## ライセンス
このリポジトリ内のコードはMITライセンスです。データの利用条件についてはCopernicus Marine Serviceの規約をご確認ください。

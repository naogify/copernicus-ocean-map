# Copernicus Sea Current Map

このリポジトリは[Copernicus Marine Service](https://data.marine.copernicus.eu/)が提供する海流データを、Geolonia地図上に可視化するシンプルなウェブページです。データセットは「[GLOBAL_ANALYSISFORECAST_PHY_001_024](https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_PHY_001_024/description)」に含まれるWMTSタイルを利用しています。

![スクリーンショット 2025-05-24 8 31 43](https://github.com/user-attachments/assets/ec62d8f7-83b5-4c13-9b4e-731bb42deb00)

## URL

https://naogify.github.io/copernicus-ocean-map


## 表示しているデータ
- 2025年5月23日 0時（UTC）時点の海水流速データ
- 深さおよそ50cmの表層データ
- WMTSの`sea_water_velocity`レイヤから取得

## Attribution
データはEUのCopernicus Marine Serviceが提供する情報を使用しており、ファイル内で以下の帰属を表示しています。

```
<a href="https://doi.org/10.48670/moi-00016">Generated using E.U. Copernicus Marine Service Information</a>
```

## ライセンス
このリポジトリ内のコードはMITライセンスです。データの利用条件については [Copernicus Marine Serviceの規約](https://marine.copernicus.eu/user-corner/service-commitments-and-licence) をご確認ください。

#  experimental_rdcl
国土地理院ベクトルタイル提供実験（地図情報（道路中心線））

## 地図情報（道路中心線）の GeoJSON タイル
国土地理院が整備している地図情報（道路中心線）について、GeoJSONタイルに変換したものを提供実験いたします。

## 地図情報（道路中心線）
テンプレート URL: http://cyberjapandata.gsi.go.jp/xyz/experimental_rdcl/{z}/{x}/{y}.geojson

サンプル：http://cyberjapandata.gsi.go.jp/xyz/experimental_rdcl/16/58242/25798.geojson

ベクトルタイルスタイル定義：http://cyberjapandata.gsi.go.jp/xyz/experimental_rdcl/style_canvas.js

## データについて
地図情報（道路中心線）をズームレベル 16の GeoJSON タイルに変換したものを提供実験いたします。
提供範囲は日本全国になります。
データの内容の詳細は、電子国土基本図地図情報ファイル仕様書（PDFファイル）（http://www.gsi.go.jp/common/000189294.pdf ）等をご覧ください。

## デモサイト
地理院地図  
http://maps.gsi.go.jp/#17/35.707179/139.959544/&base=ort&ls=ort%7Cexperimental_railcl%7Cexperimental_anno&disp=111&lcd=experimental_anno&vs=c1j0l0u0t0z0r0f0&d=l

github　　
http://gsi-cyberjapan.github.io/vector-tile-experiment/

github(canvas)　　
http://gsi-cyberjapan.github.io/vector-tile-experiment/canvas.html


## 提供の位置づけ
国土地理院ベクトルタイル提供実験におけるデータの提供の位置づけは次のとおりです。
- 本提供実験は、ベクトルタイル提供における技術的・施策的課題を国土地理院が把握するとともに、外部からの技術的な提案を受け取り、外部との技術的な議論を通じてベクトルタイルの適切な提供方法を研究開発することを目的とするものです。
- 本提供実験の期間は、2014年8月1日から本提供実験終了までとなります。
- 本提供実験のデータは、国土地理院コンテンツ利用規約( http://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html )に従って利用できます。
- 本提供実験のベクトルタイルは基本測量成果と位置付けているものではありませんが、基本測量成果としての提供を検討するにあたって、提供を行うものです。
- 本提供実験の利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。

## 履歴
2014-08-01 道路中心線ベクトルタイル提供実験を開始（茨城県つくば市周辺、新潟県新潟市周辺）

2015-08-03 道路中心線、鉄道中心線、河川中心線ベクトルタイル提供実験を開始（日本全国）

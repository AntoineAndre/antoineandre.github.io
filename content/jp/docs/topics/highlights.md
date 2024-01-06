---
title: "主な研究"
lead: "現在および過去の研究が一目で分かる"
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  research:
    parent: "topics"
weight: 100
toc: true
---

## ポスドク研究

**十二面体に分割された球面画像を基にした高解像度方位推定**

![球面画像サンプリング](https://antoineandre.github.io/content/images/research/post-doc/pyramnidal_sphere_sample.gif)

十二面体に分割された球面画像を基に、高解像度の方位推定を提供します。

**全方位画像の安定化のためのビジュアルジャイロスコープ 3 ステップパイプライン**

CVPR OmniCV 2023 ワークショップで発表予定です。

## 博士号研究

**デシメートリック範囲でのナノメートリックポーズ推定のための符号化された周期パターン**

![符号化周期パターン位相解析によるポーズ計測処理](https://antoineandre.github.io/content/images/research/post-doc/tmech_pose_measure_process.png)

ポーズ推定プロセス：（$a$）取得した対象画像、（$b$）2D 離散フーリエ変換のモジュラス。円は対象画像の 2 つの方向の周波数ピークを示しています。ガウシアンフィルタと逆フーリエ変換の適用により、画像ピクセルフレームに対するラップされた位相マップ（$c_1$）と（$c_2$）が得られます。 （$d_1$）は、符号化セルと 2D LFSR シーケンスを識別するために必要なバイナリデコーディングを示しています。 （$d_2$）は、コーディングセルの単一の拡大ビューで、コーナーとコーディングラインおよび列を区別するための色付きの四角形が表示されます。その結果、（$e$）は符号化された対象内の現在の画像の正確な登録を示しています。

![絶対符号化された周期的なパターン位置のロバストな復号化](https://antoineandre.github.io/content/images/research/post-doc/explicationThumbnailRatio.png)

サムネイルの前景強度画像から 2 値判定を行う。($a_{1}$) ホワイトノイズ、オクルージョン、可変光によって変化した画像のサムネイル。($a_{2}$)と($a_{3}$)の棒グラフは、3 つの行と列の各セットについて、コーディング強度（マゼンタ）と前景（黄）および背景（緑）の平均強度を比較し、横に決定した 2 値とを表示した。($b_{1}$) は、12$~ビットの定量化で許されるダイナミクスを示す。($b*{2}$) は、($a*{1}$) の赤い矩形内の符号化列の、$4096$ グレーレベル範囲に対する決定基準を示している。

**マイクロロボティクスへの応用**

これらの研究は、他の研究者（主に AS2M の研究部門）が、「非接触で広範囲に高精度の位置センサーを埋め込む必要がある」と考え、実施したものです。
---
title: "史料からみる日本の歴史"
description: ""
draft: false
image : "images/portfolio/science.png"
link: "https://www.hi.u-tokyo.ac.jp/collection/degitalgallary/science/"
bg_image: "images/feature-bg.jpg"
category: "リニューアル"
information:
  - label : "タイプ"
    info : "リニューアル"
---

2005年12月に、日本学術振興会による研究成果の社会還元・普及事業として、「史料からみる日本の歴史」を実施し、高校生の方々に史料やデータベースから歴史を探る楽しみを紹介したサイト「ひらめき☆ときめきサイエンス　史料からみる日本の歴史」を紹介したサイトをリニューアルしました。

リニューアルにあたり、画像共有のための国際規格**IIIF**（International Image Interoperability Framework）とプロジェクトドキュメント構築向け静的サイトジェネレータ**MkDocs**を活用しました。

データ駆動型のシステム構築における、データ（画像、メタデータ）の構造化プロセスに位置付けられます。

<br/>
<br/>

## Pickup

<br/>

> ### [倭寇図巻](https://www.hi.u-tokyo.ac.jp/collection/degitalgallary/science/013/)

[Digirati](https://digirati.com/)が開発したImage Viewer [Canvas Panel](https://cultural-heritage.digirati.com/building-blocks/canvas-panel/)を用いたストーリーテリング機能を利用しています。アノテーションについては、「須田牧子, 『倭寇図巻』再考, 東京大学史料編纂所研究紀要, 第22号, 2012年３月」を参考にしました。

また、静的ファイルのみでIIIF Image APIに対応する[iiif_static][1]を採用しています。


[1]: https://github.com/zimeon/iiif/blob/master/iiif_static.py
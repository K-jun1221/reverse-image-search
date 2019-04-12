# reverse-image-sarch

## **概要**
画像の類似検索をおこなったもの。1000枚の画像で簡単な画像検索を試せる。

## **使用技術**
VGG16, Annoy

## **手順**
コードを見ればわかるがVGG16の中間層を特徴量抽出して、ベクトルとして利用しAnnoyに食わせただけ。結構お手軽に実装できる。
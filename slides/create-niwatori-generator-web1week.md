---
marp: true
paginate: true
theme: uncover
---

# 庭には2羽ニワトリがいるジェネレーターを1週間で作った話

## 2021/05/30

---

# 自己紹介

![h:100](../assets/create-niwatori-generator/sushidesu.jpg) 

- Tomoki Ishihara 
- 北海道のクリーニング・雑貨を扱う会社 (2020/08〜)
- 社内向けの会計システムを開発中
- 以前: 雑貨商品リスト管理/ネットショプの商品登録のアルバイト
- Next.js, Firebase, Tailwind CSS, Graph CMS ← 好き

---

# 目次

- 庭には2羽ニワトリがいるジェネレーターとは？
- どうやって作ったか (技術的な話)
- なぜ1週間で作ったか？
- まとめ

---

# 庭には2羽ニワトリがいるジェネレーターとは？

---

# 庭には2羽ニワトリがいるジェネレーターとは

## → OGP画像シェアする系サービス

---

![bg](../assets/create-niwatori-generator/concept.png)

---

## 選ぶ → 作る → シェアする

---

## 選ぶ

![height:560px](../assets/create-niwatori-generator/erabu.png)

---

## 作る

![height:560px](../assets/create-niwatori-generator/tsukuru.png)

---

## シェアする

![height:560px](../assets/create-niwatori-generator/share.jpg)

---

## 「庭には〜」のいいところ

### 自由

---

## 投稿①

![](../assets/create-niwatori-generator/cool01.jpg)

---

## 投稿②

![](../assets/create-niwatori-generator/cool02.jpg)

---

## 投稿③

![](../assets/create-niwatori-generator/cool03.jpg)

---

## ドメイン名 (niwatori.dayo.app)

- dayo.app のサブドメインとして運用
- 独自ドメインがあるとちょっと良い
- 短い・汎用的なドメイン名 + サブドメイン ← おすすめ
- 他には・・・
  - cookie.dayo.app
  - janken.dayo.app

---

# どうやって作ったか

---

# どうやって作ったか

- Next.js (TypeScript) + Firebase Storage
- トップページ SSG
- 共有用ページ (OGP) SSR
- OGP画像まわりが一番大変だった
  - OGPNGを参考

---

# なぜ1週間で作ったか

---

# なぜ1週間で作ったか

- web1week (一週間でWebサービスを作るイベント)
- お題がある
  - 「Home」
  - 「Like」
  - 「2」 (参加: 「庭には〜」)
  - 「増やす」 (参加: 「クッキークリッカーメーカー」)

---

## web1weekのいいところ

---

## web1weekのいいところ①

### 見てもらえる

- ハッシュタグ 「#web1week」
- 主催: だらさん
- 他の参加者

---

## web1weekのいいところ②

### ハードルが低い

> 1週間しかありませんので、練習程度に作ったちょっとした1機能のものでも、不具合だらけでほとんど動かないようなものでも大丈夫です。逆に余裕があれば大作を作っていただいても大丈夫です。他の人とネタがかぶっちゃっても全然だいじょうぶです。
>
> [Webサービスを1週間で作るイベント開催の概要 - Crieit](https://crieit.net/posts/Web-1#%E9%96%8B%E5%82%AC%E6%A6%82%E8%A6%81)

---

## web1weekのいいところ③

### 期限がある (1週間)

→ 期限があると、完成する

---

# まとめ

---

# まとめ

- イベントに参加すると、サービスが一つできる
- おすすめイベント → web1week

---

# リンク

- [庭には2羽ニワトリがいるジェネレーター](https://niwatori.dayo.app)
- [Webサービスを1週間で作るイベント開催の概要 - Crieit](https://crieit.net/posts/Web-1)
- [だら🎄リリース！ノベルゲーム風ムービーメーカーさん (@dala00) / Twitter](https://twitter.com/dala00)

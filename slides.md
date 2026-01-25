---
# シンプルに始めるなら 'default' も試してみてください
# スライド全体のデザインテーマを指定します（外観やレイアウトが変わります）
theme: light-icons

# カバースライドの背景画像
# 最初のスライドの背景画像URLを指定します
#background: https://cover.sli.dev

# スライドに関する情報（Markdown記法が使えます）
# プレゼンテーションのメタ情報を記述します（発表者モードなどで表示されます）
title: 2025年振り返り・学び 本との出会い

# 現在のスライドに適用するUnoCSSクラス
# スライド全体に適用するCSSクラスを指定します（レイアウトや配置が変わります）
class: text-center

# 描画機能の設定 https://sli.dev/features/drawing
# プレゼンテーション中の手書きメモの永続化を制御します（trueで保存、falseで破棄）
drawings:
  persist: false

# スライド遷移のアニメーション https://sli.dev/guide/animations.html#slide-transitions
# ページ切り替え時のアニメーション効果を指定します（slide-left, fade, slide-upなど）
transition: slide-left

# MDC記法を有効化 https://sli.dev/features/mdc
# Markdown内でVueコンポーネント的な記法を使えるようにします
mdc: true

# プレゼンテーションの想定時間
# 発表時間の目安を設定します（タイマー表示などに使用されます）
duration: 10min

# フォント設定
fonts:
  # 標準テキスト用
  # 本文や見出しで使用されるフォントを指定します
  sans: Noto Sans JP
  # UnoCSS で `font-serif` クラスを指定したとき用
  # セリフ体が必要な箇所で使用されるフォントを指定します
  serif: Noto Serif JP
  # コードブロック用
  # プログラムコード表示時に使用される等幅フォントを指定します
  mono: Firple
---

# 私のおすすめする技術書２冊

2026/1/30
みんなで創る最高のブックリスト  
エンジニアのための技術書LT会

<div class="abs-br m-6 flex items-center">
  <div class="text-sm text-right" style="max-width: 250px;">
    <p style="margin-bottom: 4px;">本スライドはSlidevで作ってます<br>お手元で確認したい方はQRコードを<br>スキャンしてください</p>
    <p style="margin-bottom: 4px;">
      <a href="https://github.com/amu1017/LT-best-book-list">ソースコードはこちら</a>
    </p>
  </div>
  <img src="/images/qr-ghpages.drawio.svg" alt="QR Code" class="w-35 h-35" />
</div>

---
layout: image-right
image: './images/p2.drawio.svg'
---

# 自己紹介：<ruby>鈴木<rt>すずき</rt></ruby> <ruby>歩<rt>あゆむ</rt></ruby>

- 所属
  - 株式会社エーピーコミュニケーションズ
- 業務
  - 10 年くらいインフラエンジニアとして色々やってた(器用貧乏)
    - クラウド／サーバー／ネットワーク／クライアント PC
- 反応しそうなワード(キーワード)
  - AWS(IaaS 系や管理系), ActiveDirectory, WSUS, SKYSEA, vSphere, OpenStack, Fortigate, YAMAHA, Allied Telesis, Windows ADK, Kubernetes, OpenTelemetry, Python

---
layout: image-right
image: './images/p3.drawio.svg'
---

# 今年の振り返り

## 2025/01～02

- 今の会社に転職した(ついでに関東に引っ越した)

## 2025/03

- 本格的に業務を行い始めた：クラウドネイティブのR&D
  - R&Dとは・・・体系的な調査・研究・技術

## 2025/06

- 2025 Japan All AWS Certifications Engineerに認定された

## 2025/09

- レビューに協力した、まさるさんの本が発売した

---
layout: image-right
---

# 今年辛かったこと／頑張ったこと

- 新しい業務はベース知識こそ一緒だが、よりモダンな技術が多く業務内だけでは追いきれなかった
  - コンテナオーケストレーション　→　Kubernetes
  - オブザーバビリティ(可観測性)　→　OpenTelemetry
- 業務内容が「体系的なこと」を優先する
  - 今までの「現場マター」の考え方が通用しにくい

## **IT勉強会に参加しまくった**

<br>

## **本を読みまくった** <span style="font-size: 50%;">← LTではここを深堀</span>

---
layout: image-right
image: './images/p5.drawio.svg'
---

# 今年読んだ本の紹介①

## **Docker&Kubernetesネットワークのしくみ**
発売日：2025/6/5　頁数：296ページ

## 概要

- L1～L7の基礎的な解説
- Linuxの中での複雑なネットワーク制御の解説
- コンテナ利用時の抽象化したネットワーク制御の解説

## 感想

抽象化の概念が多い話の中で、ハンズオンの操作と的確な図が完璧に紐づいているのが読みやすい

---
layout: image-right
image: './images/p6.drawio.svg'
---

# 今年読んだ本の紹介②

## **入門OpenTelemetry／<br>実践OpenTelemetry**

発売日：2025/1/21　頁数：212ページ  
発売日：2025/4/23　頁数：276ページ  

## 概要

- 前編／後編的な構成(だと個人的には思ってる)
- コードの書き方というより考え方がメイン
- 可観測性自体の考え方も、OpenTelemetry計装の考え方も

## 感想

英語を訳しているので遠回しな表現が多いが、概念の深い所(思想や思惑的なところ)を書いている本は見ないかも。深読みしたくなる。

---
layout: image-right
image: './images/p7.drawio.svg'
---

# 今年読んだ本の紹介③

## **SREをはじめよう<br>個人と組織による信頼性獲得への第一歩**
発売日：2024/10/4　頁数：320ページ

## 概要

- SRE(Site Reliability Engineering)という役割になる為の道しるべ
- SREとして「働く」ことにフォーカスを当てている
- SRE自体の考え方とかの話はあまり書いていない

## 感想

「どうやったらSREとして雇われるか」「SREの１日の業務」の話題が出てくるのが面白かった。あんまり教科書としてのお勉強という形ではないのが逆に自分としては良かった。

---
layout: image-right
image: './images/p8.drawio.svg'
---

# 今年読んだ本の紹介④

## **AWSコスト最適化ガイドブック**
発売日：2023/3/29　頁数：384ページ

## 概要

- AWSの中の人（日本人）が書いた本
- AWSコスト管理フレームワークCloud Financial Management(CFM)を網羅的に説明
- 実際のコスト最適化の実現方法まで書いてる

## 感想

AWS公式で本を出すのは珍しい例だと思った。しかも日本語ネイティブ。具体的にサービス名を出してコスト削減方法を書いているのは非常に役に立つ。

---
layout: image-right
image: './images/p9.drawio.svg'
---

# 今年読んだ本の紹介⑤

## **サーバーレスのまわりの技術**
発売日：2025/6/1　頁数：91ページ

## 概要

- コミケ106(2025夏)で買ったいわゆる技術系同人誌
- 同人誌ということを生かしてとにかく最新の内容を書いている
- Serverless GPU、Feature Flag、eBPF、GreenOps・・・

## 感想

図が無く文字しか書いていないが、「最新を知る」という意味では参考になった。インターネット上に転がってるブログ記事よりも、知見のある人が書いているという点で信ぴょう性がありそう。

---
layout: image-right
image: './images/p10.drawio.svg'
---

# まとめ

## 体系的に学ぶなら本が手っ取り早い

- 個人ができる範囲で体系的に学ぶには本が一番早いと感じた
- 本が情報ソースであれば誰かへ説明する際の説得力も大きいことがわかった

## 来年は本を書いてみたい

- まずは技術系同人誌からチャレンジ！
- チャンスがあれば商用本も書いてみたいなぁ・・・

<br><br><span style="font-size: 70%;">買いすぎた積読がいっぱいあるので隙間時間はなるべく読むようにしたい・・・</span>

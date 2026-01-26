---
# シンプルに始めるなら 'default' も試してみてください
# スライド全体のデザインテーマを指定します（外観やレイアウトが変わります）
theme: light-icons

# カバースライドの背景画像
# 最初のスライドの背景画像URLを指定します
#background: https://cover.sli.dev

# スライドに関する情報（Markdown記法が使えます）
# プレゼンテーションのメタ情報を記述します（発表者モードなどで表示されます）
title: 私のおススメする技術書２冊

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

# 私のおススメする技術書２冊

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
  - AWS(IaaS 系や管理系), ActiveDirectory, OpenStack, FortiGate, YAMAHA, Windows ADK
- 最近注力していること
  - Kubernetes, ローカルLLM

---
layout: image-right
image: './images/p3.drawio.svg'
---

# おススメの本① -概要-

<br>

## **Docker&Kubernetes<br>ネットワークのしくみ**

発売日：2025/6/5  頁数：296ページ

## 章立て

- ネットワーク基礎
- Linuxでのネットワークの要素技術
- Dockerネットワークのしくみ
- k8sネットワークのしくみ
- CNI(Container Network Interface)
- サービスメッシュ

---
layout: image-right
image: './images/p4.drawio.svg'
---

# おススメの本① -所感-

## 読んだきっかけ

- すごく運命的な出会いをした
  - 業務でk8sを触ることになって苦戦してた
  - 特にネットワークがわからないのがモヤモヤ
  - 新発売で本が出た
  - connpassで輪読会が開かれた

## 感想

- ネットワーク図が直感的に理解できる
  - 点(インターフェース)と空間(サブネットなど)が色分け
  - 初耳のワードでも、どの範囲なのかイメージしやすい
- 1コマンドの裏側の動作が理解できてモヤモヤが少なくなった
  - iptablesで非常に複雑なことをやっててびっくり😲

---
layout: image-right
image: './images/p5.drawio.svg'
---

# おススメの本② -概要-

## **Kubernetesの知識地図**

発売日：2023/6/24　頁数：304ページ

## 章立て

- 使用するツール／サービス
- アプリケーションの展開
- Infrastructure as Code
- アプリケーションの運用
- セキュリティ

---
layout: image-right
image: './images/p6.drawio.svg'
---

# おススメの本② -所感-

## 読んだきっかけ

- 業務内容上、教科書通りのことしか触れない
  - k8sが"実際使われているか"が知りたかった
  - 以前読んだ「知識地図シリーズ」が現場視点で実践的だった記憶があり、手に取った

## 感想

- 全体的に現場目線で書かれている
  - k8sで使うGitリポジトリ運用の仕方など
  - 設計時にどういった観点で考えるべきなのか参考になった
- k8sに関連する有名なOSSの戦略も触れられている
  - GitOpsのArgoCDや証明書管理のCert-Managerなど
  - 自分が知らなかったOSSも出てきて、試してみたくなった

---
layout: image-right
image: './images/p7.drawio.svg'
---

# まとめ

-  
-
-

# おススメしたい人

---
theme: seriph
---

<!--
TODO:
  音声・スライドの確認
  出欠確認
  チャット・Q&Aについて
  音声・カメラについて
  本日の流れ
    はじめ30min：説明（座学）
    残り：実技
      説明2h、制作30min
-->

---
layout: cover
---

# Inkscapeチュートリアル
## 第1回〜名刺を作ろう〜  
<br>
<br>

### 大阪公立大学工業高等専門学校  谷口 陽音

<!--
みなさん、こんにちは。
本日はInkscape講習会第１回へご参加いただき、ありがとうございます。
テーマは「名刺をつくろう」、講師は大阪公立大学工業高等専門学校、総合工学システム学科の谷口です。
本日はよろしくお願いいたします。
-->
---
layout: cover
---

# 1 Inkscape概要

---
layout: center
---

# 1.1 オープンソースとは
## 1 Inkscape概要

---

# オープンソースとは

### オープンソース[Open Source] 

<v-clicks>

  ソースコードを公開して開発すること。<br>
  また、その成果物。  


* ソースコード：主にGitHubで公開されている  

本プロジェクトもGitHubでソースコードをすべて公開している。

</v-clicks>

---
layout: center
---

# 1.2 オープンソース・プロジェクトの例
## 1 オープンソース

---

# 本プロジェクト  


先述の通り、本プロジェクトはGitHubでソースコードをすべて公開している。
![github](/github.png)

---
# Inkscape
  
今回のテーマのInkscapeは、名の知れたオープンソース・プロジェクトである。  
詳しくは後述する。
![Inkscapeリポジトリ](/inkscape-repo.png)

---

# GIMP(GNU Image Manipuiation Program)

GIMPは画像編集ソフトとしてとても有名なGNUのソフトウェアである。  
Photoshopの代替ソフトとして有名
![GIMP](/gimp.png)

---
# GNU

GNU(GNU is Not Unix)は、Unixに似たオペレーティング・システムをオープンソースで構築するプロジェクトである。成果物として有名なのがGIMP,GNOME,Emacsなどである。後述するLinuxの発展にも大きく寄与した。
![GNU Bash](/bash.png)

---
# Linux

LinuxはLinus Torvalds氏によって開発されたUNIX互換OSである。講師が使用しているのもこれである。詳しくはWeb概論講習で説明するが、現在のWeb環境はLinuxなしではあり得なかったとされている。
![Kernel](/kernel1.png)

---

# Git

Linuxの創始者Linus Torvalds氏によって作られた。分散型バージョン管理システム。今や開発に欠かせないものである。
![git](/git.png)

---
layout: center
---

# 1.3 フリーとは
## 1 オープンソース

---

# 英語の意味

### Free:
<v-clicks>

* 無償の
* **自由な**

</v-clicks>

<br>
<br>

# オープンソースにおける「フリー」

<v-clicks>

* 無償の
* **自由に改変できる**
* **自由に再配布が可能**

</v-clicks>

---
layout: center
---

# 1.4 「フリー」の実例
## 1 オープンソース

---

#  「無償」の実例

<v-clicks>

* Inkscapeは無償でインストールできるし、広告も表示されない
* Linuxは無償でありながら十分実用に耐えうる、かつWindowsやMacのような高いポテンシャルを持ったOSである。

</v-clicks>

# 「自由に改変可能」の実例

<v-clicks>

* Googleは、Linux Kernelをモバイル用に最適化してAndroidを作った。
* 「Vi」というエディタを改変してより高いポテンシャルを誇る「Vim」が誕生した。

</v-clicks>

---

# 「自由に再配布可能」の実例

<v-clicks>

* Linuxは、Kernelのみだと動作しないので、周辺ソフトウェアと組み合わせたものが配布されている。これのことをLinuxディストリビューションという。
* いくつかのOSSの組み合わせが非常に使いやすかったので、設定ファイルごとリポジトリに登録して、それを入れるだけで同じ状況にできるようにする。

</v-clicks>

---
layout: center
---

# 1.5 ライセンス
## 1 オープンソース

---

# オープンソース・ライセンス
オープンソース・ライセンスには様々なものがある。   
以下に代表例を挙げる。

<v-clicks>

* GPL(GNU General Public License)
* MPL(Mozilla Public License)

</v-clicks>

# ライセンスの継承

<v-click>

OSSを改変して再配布するときは、改変後のものも改変前と同じライセンスを適用しなければならない。

</v-click>

---
layout: cover
---

# 2 Inkscape

---
layout: center
---

# 2.1 Inkscapeの特徴

---

# オープンソース

先述のとおり、Inkscapeの一番の特徴はオープンソースであることである。  
ベクター・グラフィックス・スイートでのデファクト・スタンダードはIllustratorである。  
しかし、とても価格が高い=>通称「Adobe税」

OSSは基本的に無償なので

<v-clicks>

* 学生でも手を出しやすい
* 少しやってみたいという人にもちょうどいい
* 気に入らないところは改変できる(やったことはない)

</v-clicks>

といった特徴がある。

---

# ベクター形式

先述の通り、Inkscapeは数少ないベクター・グラフィックス・スイートの1つである。ベクター画像のメリットについては後述する。

# クロスプラットフォーム

Inkscapeは、Windows版、Mac版、Linux版が存在し、多くのLinuxのパッケージマネージャーに含まれる。よって、OSが違っても同じように使えるアプリである。  
ちなみにオリジナルはLinux版である。

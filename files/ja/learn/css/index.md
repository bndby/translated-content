---
title: CSS
slug: Learn/CSS
tags:
  - Beginner
  - CSS
  - CodingScripting
  - Debugging
  - Landing
  - NeedsContent
  - Topic
  - length
  - specificity
translation_of: Learn/CSS
---
{{LearnSidebar}}

Cascading Style Sheets — {{glossary("CSS")}} — は{{glossary("HTML")}} を学んだら、まず次に勉強すべき技術です。HTML はコンテンツの構造と{{glossary("Semantics","意味論")}}を定義するのに使用されるのに対し、CSS はそのコンテンツにスタイルを与えたりレイアウトを決めるために使われます。例えばフォント、色、サイズ、余白を変更したり、コンテンツを複数の列に分割して段組を作成したり、アニメーションやその他の装飾機能を追加するのに CSS は利用できます。

> **Callout:** ### フロントエンドのウェブ開発者になりたいですか？目標に向かって頑張るために必要な情報をまとめたコースをご用意しました。[開始する](/ja/docs/Learn/Front-end_web_developer)

## 学習の道のり

CSS に挑戦する前に HTML の基礎を学習しておくべきです。まず、[HTML 入門](/ja/docs/Learn/HTML/Introduction_to_HTML) に取り組むことを推奨します — その後に、以下のことについて学んでください:

- [CSS 入門](/ja/docs/Learn/CSS/First_steps) から始まる CSS モジュール
- より高度な [HTML モジュール](/ja/docs/Learn/HTML#Modules)
- [JavaScript](/ja/docs/Learn/JavaScript) と、動的な機能をウェブページに追加する方法

HTML の基本のキが理解できたら、HTML と CSS の 2 つのトピックスを行き来しながらふたつを同時に学習することを推奨します。なぜなら、CSS を理解すると HTML を勉強するのが更に興味深くまたもっと楽しくなり、また HTML を知ることなくして CSS を学習することはできないからです。

またこのトピックを開始する前に、コンピューターの基本的な使い方と、ウェブを受動的に使用すること (つまり、ウェブコンテンツを消費すること) に慣れている必要があります。 [基本的なソフトウェアをインストールする](/ja/docs/Learn/Getting_started_with_the_web/Installing_basic_software) に詳しく書かれているような基本的な環境を持っており、 [ファイルの扱い](/ja/docs/Learn/Getting_started_with_the_web/Dealing_with_files) に詳しく書かれているようなファイルの作成・管理方法を理解している必要があります — なおこれらについては初心者向けの記事集である[ウェブ入門](/ja/docs/Learn/Getting_started_with_the_web)のなかに入っています。

このトピックに取り組む前に [ウェブ入門](/ja/docs/Learn/Getting_started_with_the_web) を読むと良いでしょう。ただ、このウェブ入門のなかの[CSS basics](/ja/docs/Learn/Getting_started_with_the_web/CSS_basics)の記事で紹介されていることの多くは、[CSS 入門](/ja/docs/Learn/CSS/Introduction_to_CSS) でもカバーされているのでこれは必須ではありません。

## モジュール

このトピックは、以下のモジュールで構成されており、取り組むべき順に記載していますので、上から始めていくとよいでしょう。

- [CSS の第一歩](/ja/docs/Learn/CSS/First_steps)

  - : CSS (Cascading Style Sheets) はウェブページをスタイリングしたりレイアウトしたりするのに使われます — 例えば、文字、色、大きさを変えたり、コンテンツに余白を設けたり、複数列に分けたり、 あるいはアニメーションを加えたりなど様々な装飾機能があります。このモジュールでは、CSS のはたらきから CSS の構文、そしてそれを使って HTML をどうデザインしていくのかといった CSS をマスターするための入門編を丁寧に解説します。

- [CSS の構成要素](/ja/docs/Learn/CSS/Building_blocks)

  - : このモジュールは [CSS の第一歩](/ja/docs/Learn/CSS/First_steps)から派生しています。CSS にちょっと慣れて簡単な経験も積んだところで、それをもう少し掘り下げてみましょう。カスケードと継承・セレクター・単位・サイズ設定・背景と枠線についてやデバッグの方法などを見ていきます。ここでの目的は、[テキストの装飾](/ja/docs/Learn/CSS/Styling_text)や [CSS レイアウト](/ja/docs/Learn/CSS/CSS_layout)などのより具体的な分野に進む前に、適切な CSS を書くための手法を知り、すべての重要な理論を理解できるようになることです。

- [テキストの装飾](/ja/docs/Learn/CSS/Styling_text)
  - : CSS 言語の基本を習得したら、次に取り組むべき CSS のトピックはテキストの装飾です — これは、CSS で最もよく使うことの一つです。ここでは、フォント、太字、イタリック、ラインと文字の間隔、ドロップシャドウやその他のテキスト機能の設定を含む、テキストの装飾の基本を見ていきます。あなたのページにカスタムフォントを適用し、リストとリンクを装飾するところを見ることによって、このモジュールを締めくくります。
- [CSS レイアウト](/ja/docs/Learn/CSS/CSS_layout)
  - : ここまでで既に CSS の基本、テキストの装飾方法、コンテンツを格納するボックスの装飾方法と操作方法を見てきました。今度は、ビューポートを基準にしてボックスを適切な場所に配置する方法、および互いの配置方法を検討します。 必要な前提知識はカバーされているので、奥深い CSS レイアウトの世界に飛び込むことができます。さまざまな `display` の設定、flexbox のようなモダンなやり方から、CSS grid、positioning、そしてまだまだ知っておきたいと思うかもしれないレガシーなテクニックまでを概観していきます。

## CSS でよくある問題を解決するには

[CSS を使ってよくある問題を解決する](/ja/docs/Learn/CSS/Howto) には、ウェブページを作成する際よく発生する問題を CSS を使って解決する方法へのリンクがまとめられています。

最初から、HTML 要素とその背景に色を付けたり、要素の大きさや形や位置を変えたり、要素のボーダー（境界線）を定義することがもっとも多かったでしょう。 しかし CSS の基本をしっかり理解していれば、できないことはそれほど多くありません。 CSS 学習のなかで最も嬉しいことの 1 つは、一度基礎を理解してしまうと、やり方が実はまだよくわかっていなくても、できることとできないことに対して大抵はかなり良い感触が得られることです！

## "CSS は奇妙です"

CSS は、ほとんどのプログラミング言語や設計ツールとは少し異なる動作をします。なぜ、それがそのように動作するのか？　次のビデオでは、CSS がそのように動作する理由と、そのように進化した理由について、Miriam Suzanne が役に立つ説明をしています。

{{EmbedYouTube("aHUtMbJw8iA")}}

## 関連情報

- [MDN での CSS](/ja/docs/Web/CSS)
  - : MDN での CSS ドキュメントの主な出発点です。 CSS 言語のすべての機能を詳しく説明したリファレンスドキュメントがあります。プロパティがとりうるすべての値を知りたいですか？ ここは良い場所です。
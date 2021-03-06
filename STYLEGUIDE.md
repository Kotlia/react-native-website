# React Native ドキュメンテーションスタイルガイド



テクノロジー、経験、国、年齢、人種、性別に関わらず、誰もが React Native を学ぶことができるべきです。そしてドキュメンテーションガイドラインもその方針を反映しています。

## “ゼロから 360 まで”

「Effective JavaScript」のような本が上級者だけでなく、初心者にも効果的なのは、各章が読者がJavaScriptの知識がないことを想定して始まっているからです。しかし章が終わる頃には、内容は専門家レベルにまで達しています。これは、私達がドキュメンテーションに求めるものです。つまり、各ページは基本的な内容から高度な内容に発展するべきです。読者は、専門知識と理解が深まるにつれてコンテンツを再訪することになります。

## 誰もが React 経験者ではありません

読者があなたと同じ知識や経験があるとは限りません。iOS や Android、また様々なフィールドから読者はやってきます。私たちはすべての学習者を包括的に受け入れなければなりません。

- **React の知識が無いことを前提とする。** 2019年9月の調査によると、訪問者の 31% が React JS の経験がないと回答しています。React の概念を説明するときは、簡単な説明をしてから、適切な React のドキュメントにリンクしましょう。
- **Web 開発の知識がないことを前提とする。** 調査によると、76% の訪問者のみがWeb開発の経験があると答えました。つまり、24% は Web 開発に対して全く知識がありません！ また、7.4% は開発の経験がないと答えました。iOS / Android / web 的比喩 ( ReactNative の `View` は HTML の `div` のようだ、等) の使用は極力控えるべきです。
- **他のテクノロジーも参照する。** iOS や Android に造詣が深い読者の為に、web だけでなく、他のテクノロジーを参照するべきです。

**悪い例** 「 React Native は React のようですが、web コンポーネントの代わりにネイティブコンポーネントを使用します。」 Web 開発と React の経験を前提としています。読者は片方、もしくは両方の知識を欠いている可能性があります。

**良い例** 「 React Native は React を使って構築されています。Web 上では、React は Web コンポーネントを組み合わせて UI を作成します。同様に、React Native はネイティブコンポーネントを組み合わせ使用します。」

## あなたにとっての “native”？

Web 以外の技術を固有名詞 ( `Kotlin` や `Swift `) ないしは「アプリ」と呼び、"native" と一括りにしないことに注意して下さい。Android / iOS 開発者と React Native 開発者は、 "native"  の意味に対して違う理解があるかもしれません。より具体的にすることで、Web 開発者とアプリ開発者がお互いに学び、協力し合えるように、包括的な共有語彙を作ることができます。

**悪い例** 「ネイティブアプリのアクセシビリティ」

**良い例** 「 Android / iOS のアクセシビリティ」

## 柔らかすぎず硬すぎず

トーンはとても重要です。表現が硬すぎると、数学の教科書のようになり、アレルギーを起こす人がいるでしょう。柔らかすぎると、馴れ馴れしすぎて嫌になる人がいるかもしれません。「柔らかすぎず硬すぎず」。何事もバランスです。

**悪い例**「古来の伝統に従って、"Hello, world!" と言うしか能のないアプリを作らなければならない！」 面白いかもしれませんが、ドキュメントには適していません。

**良い例** 「まずはどの言語でも基本である、"Hello, world!" と表示するアプリを作ってみましょう。」 簡潔かつ硬すぎない表現で誰にでも読みやすいです。

## 言語・文化依存のジョークの禁止

言語・文化に依存しているジョークは他の言語に翻訳するのがとても難しくなります。漫才は英語ではあまり面白くないかもしれません。更に、一過性のもの、例えば流行りの映画等を参照することも好ましくありません。5年後には時代遅れになってしまい、将来のドキュメント編集者が更新する手間が増えます。

## 「あなた」、「私たち」、そして「彼ら」

- 「あなた」(you) は読者を指します。
- 「私たち」(we) は紛らわしくて曖昧な表現です。これは、React Native コミュニティ、React Native 貢献者、または Facebook の React Native Core チームを指している可能性があります。そのため、対象を明示的に参照した後でのみ「私たち」 (we) を使用してください。
- 「彼ら」とは、この「あなた/私たち」以外の人や組織のことを指します。
  - 「私たち」(we) と同様に対象を明確にしましょう。

**悪い例** 「ジーニアス社さんが作ってくださった Web シミュレータでサンプルコードを直接弄れることができます。(素晴らしいツールです。**あなた**のおかげです！)  **彼ら**の貢献が React Native を発展させます。**彼らが**協力するのは素晴らしいですね！」

**良い例** 「ジーニアス社さんが作ってくださった Web シミュレータでサンプルコードを直接弄れることができます。(素晴らしいツールです。**彼ら**のおかげです！)  **React Native コミュニティ**の貢献が React Native を発展させます。**私たち皆で**協力するのは素晴らしいですね！」

## 代名詞は避ける

代名詞は言語によっては翻訳が難しいものがあります。また、代名詞は性別で表現される場合 (he, she; 彼、彼女 等) があり、不必要なバイアスがかかっています。

**悪い例** 「彼がアプリを開くと ローディング画面が表示される」

**悪い例** 「ユーザーがアプリを開くと ローディング画面が表示される」

## 動名詞は使わない

日本語では相当する動詞活用がないため割愛。

英語での例：

**Bad** “Coding with React Native is fun!“

**Good** “It is fun to code with React Native!“

## 短く簡潔に

短い文章の方が、機械にも人間にも翻訳しやすいです。一つの長い文章よりも、短く、簡潔な文章を心がけましょう。

**悪い例** 「まず、ES2015（ES6とも呼ばれています）は、現在では公式規格の一部となっている JavaScript の改良セットですが、まだ一部のブラウザでサポートされていないため、Web開発では使われていないことが多いです。」

**Good** 「ES2015 は現在では公式規格の一部となっている JavaScript の改良セットです。まだ一部のブラウザでサポートされていないため、Web開発では使われていないことが多いです。」


# ド技術的キュメンテーションのガイドライン

## メニューパスのフォーマット

OS のメニューをナビゲートする際には、メニュー選択パスを**太字**にし、サブメニューを示すために「 **>** 」を使用します。

**悪い例** 「Xcode の "Preferences..." を開いてから "Components" をクリックします。」

**良い例** 「**Xcode** **>** **Preferences...** を開いてから **Components** をクリックします。」

## “Android” は “iOS” の前

Android の開発者の数は iOS を上回っており、iOS を Android の前に置くことは、軽蔑的で特権的だと感じるかもしれません。少なくとも一貫性を保つために、技術をリストアップする際には、iOS よりも Android の方が優先されます。

**悪い例** 「React、iOS、Android の開発に関する予備知識がないことを前提に最善を尽くしていますが、これらは React Native 開発者にとって貴重な研究トピックです。」

**良い例** 「React、Android、iOS の開発に関する予備知識がないことを前提に最善を尽くしていますが、これらは React Native 開発者にとって貴重な研究トピックです。」

## 値については明確に

プロパティの値を記述する際には、何が許可されていて何が許可されていないかを明確にしましょう。何かがオプションである場合は、オプションであることを明言します。何かが複数の値を持つことができる場合は、どの値を受け入れることができるかを述べます。

**悪い例** 「A は整数であるべき。」

**良い例** 「A は整数です。」

## その他

* “Hooks” は大文字から始まります。

## 読者を思いやる

ステップバイステップの解説（例えば、何かをインストールする方法）を書くときは、そのトピックについて知っていることをすべて忘れてみてください。書き終わったら、初心に戻り、あなたが書いた指示に従うことを想像してみて下さい。多くの場合、言及するのを忘れていた暗黙の知識があったり、指示の中に不足していたり、順序から外れたステップがあったりすることに気づくでしょう。プロのヒント：誰か他の人にあなたの指示に従ってもらい、彼らがどこで行き詰っているか見てみましょう。

## もっと詳しく

## 執筆のコツ

- まずはアウトライン（概要）を作成
- アウトラインを拡張
- 5W1H を意識する

## リソース

- 参考 (英)：[React JS’s contibuting guidelines](https://github.com/reactjs/reactjs.org/blob/master/CONTRIBUTING.md#guidelines-for-text)、 特に [code examples guidelines](https://github.com/reactjs/reactjs.org/blob/master/CONTRIBUTING.md#guidelines-for-code-examples)

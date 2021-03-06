# 難題には一番最初に取り組もう (Tackle the Hard Stuff First)
原文: [https://www.codingvc.com/tackle-the-hard-stuff-first](https://www.codingvc.com/tackle-the-hard-stuff-first)  
Credit: Leo Polovets([https://www.codingvc.com/about](https://www.codingvc.com/about))

> もし一匹のカエルを食べることが君の仕事だとしたら、一番良いのは朝一にそれを済ませてしまうことだ。そして、もし二匹のカエルを食べることが君の仕事だとしたら、一番良いのは大きい方から食べることだ。
> 
> マーク・トウェイン

(訳注: 「カエルを食べてしまえ」で知られる逸話)

役に立つソフトウェア・エンジニアリングのプラクティスとして「プログラムの最も難しい部分に最初に取り組む」があります。もしプログラムの最も難しい部分が完成しなかったら、システム全体を動作させるところまでは持っていけないからです。例を挙げます。もしそのプログラムに10個のコンポーネントがあって、10番目のコンポーネントがもっとも難しかったとしましょう。このとき、先に1番目から9番目までをコーディングしてしまうことは、プロジェクト全体が不可能であることをエンジニアが気づくまでに多くの時間を浪費してしまうことを意味します。 そもそもプロジェクトが遂行可能かどうかを理解するためには、10番目から始める方が賢明です。簡単なことから着手するやり方は、基本的に難しいことを先延ばししているだけだからです。

リーン・スタートアップのアプローチはこのエンジニアリング・プラクティスによく似ています。全機能を備えたプロダクトを前もって構築する代わりに、見込み客と話をしてMVP (Minimum Viable Product: 実用最小限の製品) を迅速に作り上げ、そのアイディアがより大きな投資に値するかを見極めます。コードを書くという行為は取り組みやすくて楽しいものですけど、だいたいそういうのは災禍を招くレシピになります。

ピッチ (短時間で行うサービスの売り込みプレゼンテーショントーク) をするとき、真正面から向き合うのではなく難しい部分を避けてしまうことがよくあります。プロダクトやスタートアップ、VCファンドに投資するように説得しようとするとき、プレゼンター多くは厳しい質問に対して軽率な、あるいは浅はかな回答をしてしまいます。ありがちなことではありますが、それが正しい行動と言える場合は滅多にないでしょう。具体的な例をいくつか挙げてみましょう。

## 例 #1
- 投資家: 「競争上、優位な点は何ですか？」
- ファウンダー: 「この分野においては、他の企業よりも優れた実行力と専門知識を持っている点です」
  (ほぼすべての競合他社が全く同じことを言うでしょう）

## 例 #2
- ファウンダー: 「100万ドルを調達しようとしていますが、総額500万ドルの投資オファーがあります。他の投資家からではなく、御社から資金オファーを受ける必然性はどのようなものでしょうか？」
- VC: 「我々は他のファンドよりも付加価値が高く、私たちの抱えるパートナーは運営に関して深い専門知識を持っていますよ」
  (ほとんどのVCファンドも似たようなことを主張しているので、これは基本的に答えになっているとは言えません)

## 例 #3
- 見込み顧客: 「私のビジネスはダウンタイムのリスクを取れません。御社の製品に100％の稼働を期待できるかという点について説明してもらえますか？」
- 営業担当者: 「私たちは10週間の実際に稼働させてきましたが、まだクラッシュはありません。またこの状況がすぐには変わらないと信じています」
  (見込み客の懸念に対して真っ当には対処していない、個人的な見解に基づいた回答)

スタートアップのピッチでは、私はたくさん質問するのが好きです。質問の中には難しいものもあり、実際、良い答えとはどのようなものか分からないこともあります。最悪の回答は他者を見下したような回答です。例えば、「Googleは我々と競合することはないでしょう。なぜならそれは彼らのDNAにないからです」とか、「我々の技術チームは他の誰よりも優れているので、我々は勝つつもりです」といったものです。私は、軽蔑的な回答よりも、「わからない」という答えの方を聞きたい。最高の回答は、よく考えられていて説得力のあるものです。それらは将来的には間違っていることが判明するかもしれませんし、その場では同意できないかもしれませんが、プレゼンターの心の底で考えていることと信念を表していると思います。

身近な例を挙げます。多くの創業者は、Googleは検索のような収益性の高いサービスに力を入れすぎているので、競合相手にはならないだろうと言うでしょう。それは戯言です。Googleは明らかに検索を重視していますが、オフィス・スイートから自動運転車に至るまでの製品の開発にも意欲も見せています。一方、別の創業者は、自分たちの製品が多くのパートナー企業との統合を必要とするため、特定の製品の強力な競争相手にはならないだろうと言うかもしれません。Googleは歴史的にその点で優れていなかったからだ、と。(Googleはほとんどのことを社内で行うのが好きですが、多くの企業は、最終的に同社が一部のパートナーと競合することになるため、Googleとの提携に慎重になっています)。これはもっと思慮深く意味のある答えだと思います。

なぜ人々は難しいことを避けているのでしょう? 多くの場合、直面することを恐れているからです。もしGoogleがあなたのアイデアをうまくコピーできたら(しようとしていたとしたら)? 適切な製品を構築していない場合はどうなりますか。CTOが十分な技術的リーダーでない場合はどうすればよいでしょうか。他のVCと比べて目立っていない場合はどうでしょうか? 製品の要となるアルゴリズムのパフォーマンスを十分に上げることができない場合はどうすればよいでしょうか。これらの質問を無視したり無視したりするのは間違いです。もしかしたらCTOが弱いかもしれない、そんな危惧があるからと言って、臭い物に蓋をしたままあとは行く先を見守るだけでもいい、なんてことにはなりません。

顧客や投資家、ファウンダーから厳しい質問をされても - あるいは自分自身に厳しい問いがあったとしても -、恐れないでください。それについて考えてみてください。本当によく考えてみてください。ベストを尽くして答えを考えてみてください。良い答えが思いつかない場合は、もう少し考えてみましょう。他の人からアドバイスをもらってください。実験をしてください。強い答えを思いつくためには何でもしてください。もしそれができなかったら、それはあなたの製品アイデアが弁護できないものであったり、正しいものを作っていないとか、新しいCTOが必要とか、優れた投資家になるために必要なものを持っていないか、あなたが取り組んでいるプログラムをコーディングするのは不可能だということを意味しているかもしれません。これらのことに気づくのは愉快なことではありませんが、希望のないことに取り組んで人生の何年も無駄にしてしまうことにはなりません。後になって難しい部分を完成させることができない可能性があることを知っていながら、簡単な部分に時間を費やすのはなぜなのでしょう。

こちらもどうぞ: [成功への道は不快感で舗装されている](http://codingvc.com/the-road-to-success-is-paved-with-discomfort/) (原文)

Ben Wienerへ、Mark Twainの引用を教えてくれて感謝します。

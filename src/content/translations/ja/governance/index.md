---
title: イーサリアムのガバナンス
description: イーサリアムに関する決定がどのように行われるかについてのご紹介
lang: ja
postMergeBannerTranslation: page-upgrades-post-merge-banner-governance-ood
---

# イーサリアムのガバナンスの概要 {#introduction}

_イーサリアムは誰かに所有されるものではないため、イーサリアムのこれまでの変更と今後の変更に関する決定はどのように行われるのでしょうか? イーサリアムのガバナンスとは、そのような意思決定を可能にするプロセスのことです._

<Divider />

## ガバナンスとは {#what-is-governance}

ガバナンスとは、意思決定を行うためのシステムです。 一般的な組織構造では、経営陣や取締役会が意思決定の最終決定権を持ちます。 あるいは、株主が提案に投票し、変更を成立させる場合もあります。 政治システムでは、選挙で選ばれた議員は、有権者の要望を代弁しようとする法案を制定することがあります。

## 分散型ガバナンス {#decentralized-governance}

イーサリアムプロトコルは誰にも所有されず、誰のコントロールも受けていませんが、ネットワークの今後と成長を確実にするためには、変更を実施するか、しないかの決定が必要になります。 所有権がないため、従来の組織的なガバナンスとは相容れない形態になっています。

## イーサリアムのガバナンス {#ethereum-governance}

イーサリアムのガバナンスは、プロトコルを変更するためのプロセスです。 ここで重要なのは、このプロセスは、人々やアプリケーションがプロトコルをどのように使用するかには関係しないということです。イーサリアムはパーミッションレスです。 世界のどこからでも、誰でもオンチェーン・アクティビティに参加できます。 誰がアプリケーションを構築したり、トランザクションを送信したりできるかどうかのルールは設定されていません。 しかし、これらのアプリケーションが動作する基盤となるコアプロトコルへの変更を提案するプロセスがあります。 非常に多くの人々がイーサリアムの安定性に依存しているため、イーサリアムへの変更が安全で広くコミュニティに支持されるように、社会的および技術的プロセスを含めて、コアの変更には非常に高いハードルが設定されています.

### オンチェーンとオフチェーンのガバナンス比較 {#on-chain-vs-off-chain}

ブロックチェーン技術では、オンチェーンガバナンスと呼ばれる新しいガバナンス機能が利用可能です。 オンチェーンガバナンスとは、提案されたプロトコルの変更が、通常はガバナンストークンの保有者であるステークホルダーの投票によって決定され、投票はブロックチェーン上で行われます。 オンチェーンガバナンスの一部の形態では、提案されたプロトコルの変更はすでにコード化されており、ステークホルダーが変更を承認すれば自動的に実装されます。

反対のアプローチであるオフチェーンガバナンスでは、プロトコル変更の決定は、社会的な議論による非公式なプロセスで行われ、承認されればコードで実装されます。

**イーサリアムのガバナンスはオフチェーン**で行われており、そのプロセスには様々なステークホルダーが関わっています。

_プロトコルレベルではイーサリアムのガバナンスはオフチェーンですが、分散型自律組織(DAO)などイーサリアム上に構築された多くのユースケースではオンチェーンのガバナンスを使用しています。_

<ButtonLink to="/dao/">
  分散型自律組織(DAO)の詳細
</ButtonLink>

<Divider />

## ステークホルダー {#who-is-involved}

[イーサリアムコミュニティ](/community/)には様々なステークホルダーがおり、それぞれがガバナンスプロセスでの役割を果たしています。 プロトコルから最も遠いステークホルダーから始めて、徐々に近づいて見ると、次のようになります。

- **イーサ所有者**: 任意の額の ETH の保有者。 [ETH の詳細](/eth/)
- **アプリケーションユーザー**: イーサリアムブロックチェーン上のアプリケーションを利用するユーザー。
- **アプリケーション/ツールデベロッパー**: イーサリアムブロックチェーン上で実行されるアプリケーション(分散型金融、非代替性トークンなど)、またはイーサリアムとやり取りするためのツール(ウォレット、テストスイートなど)のデベロッパー。 [分散型アプリ(Dapp)の詳細](/dapps/)
- **ノード運用者**: ブロックやトランザクションを伝播させるノードを実行し、見つけた不正なトランザクションやブロックを拒否します。 [ノードの詳細](/developers/docs/nodes-and-clients/)
- **EIP 起草者**: 起草者は、イーサリアムプロトコルの変更を、イーサリアム改善提案(EIP)の形で提案します。 [EIP の詳細](/eips/)
- **マイナー/バリデータ**: イーサリアムブロックチェーンに新しいブロックを追加できるノードを実行します。
- **プロトコルデベロッパー** (別名 「コアデベロッパー」): プロトコルデベロッパーは、様々なイーサリアムの実装を維持しています(例: 実行レイヤーの go-ethereum、Nethermind、Besu、Erigon、または合意レイヤーの Prysm、Lighthouse、Nimbus、Teku、Lodestar)。 [イーサリアムクライアントの詳細](/developers/docs/nodes-and-clients/)

_注: どの個人もこれらのグループの複数に参加できます(たとえば、プロトコルデベロッパーはイーサリアム改善提案チャンピオンを兼ね、またビーコンチェーンバリデータを行い、同時に分散型金融アプリケーションも使用できます)。 ただ、概念を明確にするために、これらを区別するのが最も簡単です。_

<Divider />

## イーサリアム改善提案(EIP)とは {#what-is-an-eip}

イーサリアムのガバナンスで使われる重要なプロセスの 1 つに、**イーサリアム改善提案**があります。 イーサリアム改善提案(EIP)とは、イーサリアムの新しい機能やプロセスを定める標準であり、 イーサリアムコミュニティの誰もが作成することができます。 例えば、非代替性トークン(NFT)を標準化した EIP-721 の起草者らには、イーサリアムのプロトコル開発に直接携わってはいません。

<ButtonLink to="/eips/">
  イーサリアム改善提案(EIP)の詳細
</ButtonLink>

<Divider />

## 公式プロセス {#formal-process}

イーサリアムのプロトコルを変更するための公式プロセスは以下の通りです。

1. **コア・イーサリアム改善提案**: [EIP-1](https://eips.ethereum.org/EIPS/eip-1#core-eips)に記述されているように イーサリアムに変更を正式に提案するには、まずコア・イーサリアム改善提案で詳述することです。 受け入れられると、プロトコルデベロッパーが実装するイーサリアム改善提案(EIP)の公式の仕様になります。

2. **プロトコルデベロッパーへイーサリアム改善提案(EIP)の提示**: コミュニティの意見を集めたコア・イーサリアム改善提案の作成後、プロトコルデベロッパーにそれを提示します。 [全コア開発コール](https://github.com/ethereum/execution-specs/tree/master/network-upgrades#getting-the-considered-for-inclusion-cfi-status)に提示し、議論します。 [イーサリアム・マジシャンズ・フォーラム](https://ethereum-magicians.org/)または[イーサリアム R&D ディスコード](https://discord.gg/mncqtgVSVw) で、議論が既に並行して行われている場合があります。

> この段階で起こり得る結果は、次のようなものがあります。

> - イーサリアム改善提案(EIP)は将来のネットワークアップグレードの際に検討される
> - 技術的な変更をリクエストする
> - 優先順位が低い場合や、開発労力に比べて改善効果が十分に大きくない場合には、却下される

3. **最終提案に向けた反復作業**: すべての関連するステークホルダーからのフィードバックを受けた後、セキュリティを向上させたり、さまざまなユーザーのニーズを満たすために、おそらく最初の提案に変更を加える必要がでてくるでしょう。 イーサリアム改善提案(EIP)に必要と思われる変更をすべて反映させたら、プロトコルデベロッパーに再度提示する必要があります。 その後、次のステップに進む、または新たな懸念事項が出てきて、提案を再度繰り返し行う必要が出てきます。

4. **ネットワーク・アップグレードに含まれる**: イーサリアム改善提案(EIP)が承認され、テストされ、実装されたと仮定すると、ネットワーク・アップグレードの一部に含まれます。 ネットワーク・アップグレードには高い調整コストがかかるため(全員が同時にアップグレードする必要がある)、イーサリアム改善提案(EIP)は一般的にアップグレードのタイミングにまとめられます。

5. **ネットワーク・アップグレード有効化**: ネットワーク・アップグレードが有効化されると、イーサリアム改善提案(EIP)はイーサリアムネットワークで稼働します。 _注: ネットワーク・アップグレードは通常、イーサリアムメインネットで有効化される前にテストネットで行われます_。

このフローは非常に簡略化されていますが、イーサリアム上でプロトコルの変更を有効にするための重要な手順の概要を示しています。 では、このプロセスにおける非公式な要素を見てみましょう。

## 非公式のプロセス {#informal-process}

### 過去の作業についての理解 {#prior-work}

イーサリアム改善提案チャンピオンは、イーサリアム改善提案(EIP)を作成する前に、イーサリアムメインネットでの展開を真剣に検討できるよう、過去の作業や提案をよく理解しておく必要があります。 これにより、過去に拒否されていない、新しい提案をもたらすことができます。 過去のイーサリアム改善提案(EIP)を調べるには、主に[イーサリアム改善提案(EIP)リポジトリ](https://github.com/ethereum/eips)、[ イーサリアム・マジシャンズ](https://ethereum-magicians.org/)および[etthresear.ch](https://ethresear.ch/)の 3 つの場所があります。

### ワーキンググループ {#working-groups}

最初のドラフトのイーサリアム改善提案は、編集や変更なしにイーサリアムのメインネットに実装されることはまずありません。 一般的に、イーサリアム改善提案チャンピオンは、プロトコルデベロッパーのサブセットと協力して、提案の具体化、実装、テスト、反復、提案の最終化を行います。 これまでの事例を見ても、これらのワーキンググループには数ヶ月(時には数年も!)の作業が必要でした。 同様に、このような変更を行うイーサリアム改善提案チャンピオンは、エンドユーザーからのフィードバックを収集し、展開上のリスクを軽減するために、関連するアプリケーション/ツールデベロッパーを早期の段階で参加させる必要があります。

### コミュニティコンセンサス {#community-consensus}

イーサリアム改善提案(EIP)の中には、差異を最小限に抑えた単純な技術的改善もありますが、中にはより複雑で本質的にトレードオフの関係にあり、異なるステークホルダーにさまざまな形で影響を与えるものもあります。 そのため、イーサリアム改善提案(EIP)の中にはコミュニティの中で論争になるものもあります。

争点となる提案をどのように扱うか、明確なプレイブックはありません。 プロトコルデベロッパーは、人々にネットワークのアップグレードを強制する手段を持たないため、一般的には、議論がコミュニティ全体の利益を上回ってしまうような提案の実装を避けるでしょう。

イーサリアム改善提案(EIP)チャンピオンは、すべての関連するステークホルダーのフィードバックを求めることが期待されています。 もし、あなたが論争中のイーサリアム改善提案(EIP)のチャンピオンになったとしたら、自分の提案に対する合意を得るために、反対意見に対処する必要があります。 イーサリアムコミュニティの規模と多様性を考えると、コミュニティの合意を測るために使用できる単一の指標(コイン投票など)はなく、イーサリアム改善提案(EIP)チャンピオンは提案の状況に応じて柔軟に対処することが求められます。

イーサリアムネットワークのセキュリティだけでなく、プロトコルデベロッパーは、アプリケーション/ツールデベロッパーやアプリケーションユーザーの価値を重視してきました。これは、アプリケーション/ツールデベロッパーやアプリケーションユーザーがイーサリアムを使用して開発することが他のステークホルダーにとってエコシステムを魅力的なものにするという観点によるものです。 さらに、イーサリアム改善提案(EIP)は、異なるチームによって管理されているすべてのクライアントに導入される必要があります。 そのため、このプロセスの一環として、変更が価値あるものであり、それがエンドユーザーを助けたり、セキュリティ問題を解決するものであることを、プロトコルデベロッパーの複数のチームに納得させることが大切です。

<Divider />

## 意見の不一致への対処 {#disagreements}

さまざまな動機や信念を持った多くのステークホルダーがいるため、意見の相違が生じることも少なくありません。

一般的に、意見の相違は、問題の根本を理解し、誰もが意見を述べることができるように、パブリックフォーラムでの長時間の議論の中で処理されます。 一般的には、一方のグループが譲歩するか、あるいは望ましい中間妥協案になります。 1 つのグループが強く反対しているのであれば、特定の変更を強制すると、チェーン・スプリットにつながる可能性があります。 チェーン・スプリットとは、一部の関係者がプロトコルの変更を抗議した結果、互換性のない異なるバージョンのプロトコルが動作し、そこから 2 つの異なるブロックチェーンが生まれることです。

### The DAO フォーク(DAO: 分散型自律組織) {#dao-fork}

フォークとは、ネットワークに大きな技術的なアップグレードや変更が必要となり、プロトコルの「ルール」を変更することです。 [イーサリアムクライアント](/developers/docs/nodes-and-clients/)は、新しいフォークルールを実装するためにソフトウェアをアップデートする必要があります。

The DAO フォークは、周到に脆弱性を突いた[2016 年の The DAO 攻撃](https://www.coindesk.com/understanding-dao-hack-journalists)で 360 万 ETH 以上の[分散型自律組織(DAO)](/glossary/#dao)コントラクトが流出した事件を受けたものです。 このフォークにより、欠陥をもったコントラクトから新しいコントラクトに資金が転送され、ハッキングで ETH を失った人が回収できるようになりました。

この行動指針はイーサリアムコミュニティの投票で行われました。 ETH 保有者は、 [投票プラットフォーム](http://v1.carbonvote.com/)でトランザクションを通じて投票することができました。 フォークの実行は、投票の 85%以上に支持されました。

ここで重要なのは、プロトコルがハッキングを元に戻すためにフォークしたものの、フォークを決定する際の投票の重要性については、いくつかの理由から議論の余地があるということです。

- 投票率は驚くほど低かった
- ほとんどの人が投票が行われていることを知らなかった
- 投票が ETH の保有者のみを代表するものであり、システムの他の参加者を代表するものではなかった

コミュニティの一部がフォークを拒否したのは、The DAO 事件がプロトコルの欠陥ではないと考えたことが主な理由です。 その後、彼らは[イーサリアムクラシック](https://ethereumclassic.org/)を形成しました。

現在、イーサリアムコミュニティでは、システムの信頼できる中立性を維持するために、コントラクトのバグや資金の損失の場合には介入しないという方針を採用しています。

The DAO ハッキング事件をもっと見る

<YouTube id="rNeLuBOVe8A" />

<Divider />

### フォークの効用 {#forking-utility}

イーサリアムとイーサリアムクラシックは、健全なフォークの良い例です。 2 つのグループは、いくつかの基本的な価値観においてお互いに強く意見を異にしていましたが、それぞれの行動方針を追求するのは、リスクに見合う価値があると考えました。

イーサリアムガバナンスの成功には、政治的、哲学的、経済的な大きな違いに直面しても、フォークできることが大きな役割を果たしています。 フォーク機能がなければ、対立が続き、最終的にイーサリアム クラシックを形成した人々は消極的な参加を余儀なくされ、イーサリアムの成功のビジョンはますます異なったものになっていました。

<Divider />

## ビーコンチェーン開発 {#beacon-chain}

イーサリアムガバナンスプロセスでは、スピードや効率性と、オープン性や包括性がトレードオフになることがよくあります。 ビーコンチェーンの開発を加速させるために、プルーフ・オブ・ワークのイーサリアムネットワークとは別に立ち上げられ、独立したガバナンスが行われています。

仕様と実装の開発は常に完全にオープンソースで行われてきましたが、前述のアップデートを提案する正式なプロセスは採用されませんでした。 プロセスを省略することにより、研究者と実装者が迅速に変更点を特定し、合意することができました。

ビーコンチェーンがイーサリアムの実行レイヤーにマージされると、変更を提案するガバナンスプロセスは調和されます。 このマージの実装プロセスは、[すでに進行中](https://eips.ethereum.org/EIPS/eip-3675)です。

<ButtonLink to="/upgrades/merge/">
  マージの詳細
</ButtonLink>

<Divider />

## 参加方法 {#get-involved}

- [イーサリアム改善提案(EIP)の提案](/eips/#participate)
- [現在の提案についての議論](https://ethereum-magicians.org/)
- [R&D ディスカッションへの参加](https://ethresear.ch/)
- [イーサリアム R&D ディスコードへの参加](https://discord.gg/mncqtgVSVw)
- [ノードの運用](/developers/docs/nodes-and-clients/run-a-node/)
- [クライアント開発への貢献](/developers/docs/nodes-and-clients/#execution-clients)
- [コアデベロッパー実習プログラム](https://blog.ethereum.org/2021/09/06/core-dev-apprenticeship-second-cohort/)

## 参考文献 {#further-reading}

イーサリアムのガバナンスは厳格には定義されていません。 さまざまなコミュニティ参加者が多様な視点を持っています。 下記にいくつかご紹介します。

- [ブロックチェーンガバナンスに関するノート](https://vitalik.ca/general/2017/12/17/voting.html) - _Vitalik Buterin_
- [イーサリアムのガバナンス](https://docs.ethhub.io/ethereum-basics/governance/) – _ETHHub_
- [イーサリアムのガバナンスの仕組み](https://cryptotesters.com/blog/ethereum-governance) – _Cryptotesters_
- [イーサリアムのガバナンスの仕組み](https://medium.com/coinmonks/how-ethereum-governance-works-71856426b63a) – _Micah Zoltu_
- [イーサリアムコアデベロッパーとは](https://hudsonjameson.com/2020-06-22-what-is-an-ethereum-core-developer/) - _Hudson Jameson_
- [ガバナンス、パート 2: 金権政治はまだ悪質](https://vitalik.ca/general/2018/03/28/plutocracy.html) - _Vitalik Buterin_
- [コイン投票ガバナンスを超えて](https://vitalik.ca/general/2021/08/16/voting3.html) - _Vitalik Buterin_
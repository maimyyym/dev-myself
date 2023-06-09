# Monthly Plan <202305>
start: 20230518

## WishList
- FastAPIリファクタリング
- JS非同期処理（zennの本を読破）


## Weekly 
### 0518-21
- Plan
    - FastAPIリファクタリング設計
    - JS非同期処理：目標70%
- Other
    - 読書10分の継続
    - 英語学習の模索
    - ヘルシーな生活をする
- Review
    - リファクタ設計：何をすべきかは分かった。
        - 同じことを繰り返し書いている箇所がある（JWTトークンの生成、get_userとall_get_user：passwordとrefresh_tokenを除く処理のみ足して書けば良い？）
        - トークン生成の関数を切り出す
        - users周りの関数は、DB操作あり・生成系・cookie等からの取得に分けられるのでディレクトリも分けるか検討
    - JS非同期処理：zennの本は隅々まで読むのはまだ早そう。ポイントを押さえて、徐々にレイヤーを深くしてからさくさく読みたい。
    - 読書：休みの日の継続が厳しかった。電車ではOK
    - 英語：かなり厳しい。どこに組み込むかが問題
    - ヘルシーな生活：お財布に現金を入れないのは効果大。朝プロテイン置き換えチャレンジ中（栄養不足だから）

### 0522-0528
- Plan
    - JS非同期処理：概要つかむ！ポイントとなる用語を説明できるようになる。背景、うれしいこと、仕組み、概念同士の関係性。
    - FastAPIリファクタリング：リソース減らす。隙間時間で継続。
- Other
    - 読書継続
    - 英語：やり方をなんとか探す
    - 生活習慣：ランチはスープジャーに野菜＋ご飯。夜はコンビニに行かない…代案を検討

- Review
    - JS非同期処理
        - ブラウザでJSが実行される仕組み、なぜ実現できているのか、という点を理解した。
        - 非同期処理のハンドリングが複雑になってくると、おもしろいことが起きていると分かった。
        - 期限を決めてやると全体を把握することができるのでこのサイクルを続けたい。
    - 読書：少しずつでも読むことが大切。1日途切れても再開できること。読むタイミングは決めすぎない方が良い。
    - 英語：英語を学ぶために英語に触れるのではなく、知りたいことのために積極的に英語を読む方が良さそう？
    - 生活習慣：最近はコントロールできている気がするけれどまだ分からない。

### 0529-0531
- Plan
    - セキュリティ：アプリ構築のため最低限知っておくべき項目を網羅。
    - デザイン：少しでも良いデザインが作れるよう知識と実践を行う。こちらも全体像を網羅。
- Other
    - ポートフォリオ作成
    - 読書継続
    - なるべく引き算思考をする

- Review
    - セキュリティ：ChatGPTで項目洗い出し→技術記事を探して読む→まとめる、がいい感じ。zennに記事投稿。
    - デザイン：なるほどデザイン読了。次に何をすべきか迷子なのでChatGPTで自分と相談。
    - 読書：朝の混んでいる時間は厳しい。
    - 引き算思考：意識はできていない。エッセンシャル思考を読むか迷う
    - ポートフォリオ：時間とって論理立てて作るべき

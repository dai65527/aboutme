経歴とスキルセットの紹介（20.4.5現在。随時更新）

# 要約
- 早稲田大学大学院基幹理工学研究科機械科学専攻（修士（工学））
- 前職はJFEエンジニアリング株式会社でプラントエンジニアとして都市環境プラントの設計を担当。
- 42Tokyoでソフトウェアエンジニアリング（C/C++/Linux/Docker/Kubernetes）を学習中。
- 独学でWeb技術（Go/Ruby/JavaScript/TypeScript/Vue\.js/NodeJS/AWS）を学習中。

# 基本情報
|key|value|
|----|----|
|名前|Daiki Nakano|
|年齢|26|
|所属中|[42Tokyo](https://42tokyo.jp/)|
|email|dai65527@gmail.com|
|Twitter|[@daitaidaidai789](https://twitter.com/daitaidaidai789)|
|Qiita|[@daitai-daidai](https://qiita.com/daitai-daidai)|
|英語力|TOEIC(L&R)950 (IP)|
|資格|修士（工学）、第3種電気主任技術者|
|特技|ラグビー（関東高校代表）、格安航空券探し|

# 経歴
### 2013年4月〜2017年3月 早稲田大学基幹理工学部機械科学・航空学科
- 東日本大震災がきっかけでエネルギー関連技術に興味を持ち機械工学を学ぶ
- 鳥人間（人力飛行機）サークル、ボートサークルに所属
- その他飛行ロボットコンテストに出場などものづくり系の活動を行う
- GPA：3.47/4.0
- 学士（工学）

### 2017年4月〜2019年3月 早稲田大学基幹理工学研究科機械科学専攻
- エネルギー工学系の研究室に所属し、ヒートポンプシステムの性能評価、制御検討に関する研究を行う
- インジェクションヒートポンプシステムについて、数値シミュレーションプログラムの構築（数理モデリング、設計、コーディング）、及び、実機と合わせ検証を実施し、制御の安定化を実現 (NTT系企業からの委託研究)
- その他NEDO採択プロジェクトの研究補助業務にも従事、数値シミュレーションによる排熱活用技術の実用化検討（数理モデル改善、性能評価、非定常特性評価）を担当。
- 修士（工学）

### 2019年4月〜2020年8月 大手プラントエンジニアリングメーカー
- 都市環境プラントの設計業務に従事。
- エネルギー工学の知識と持ち前の吸収力にて、新卒1年目にしてプロセスフローの標準化検討や既設工場不具合対策を主担当として任されるなど、早い段階から戦力に。
- その他、計画、実施設計業務、ベンダー・協力会社管理、海外子会社教育など幅広い業務に従事し、大規模プロジェクトに関する業務を一通り経験。
- 仕事にやりがいはあったものの、技術的に成熟した分野であることや、元請け企業ゆえの技術的業務の少なさにもの足りなさを感じる。
- 新技術が多く、エンジニアが企画〜設計〜コーディングまで携われるソフトウェアエンジニアに魅力を感じ、独学開始。

### 2020年8月 エンジニア養成機関42Tokyo 入学試験（Piscine）受験
- フランス発エンジニア養成機関42Tokyoの入学試験「Piscine」を受験。
- 1ヶ月間続く試験中、寝る時以外全ての時間をかけてコーディングに向きあう。
- 技術力、自走力、コミュニケーション力を問う試験に合格し、42Tokyo入学資格を得る。

### 2020年10月〜現在 エンジニア養成機関42Tokyo
- Linux、C/C++、Docker/Kubernetesを学習（内容は後述）。
- 講師、メンター不在の中で自走力とコミュニケーション力を鍛える。
- 現在のレベルは3ヶ月先行して入学した1期生も含め、3月18日現在学内トップ（Lv.5.32）
- 今後はWeb技術やAI/機械学習などを学習する予定。
- 42Tokyoと並行して、JavaScript/Rubyなどの技術も勉強中。
- 1日10時間以上毎日プログラムを書き続けています。
- 42Tokyoでの学習記録：https://note.com/daitai_daidai/n/nf69533f53646

# スキル
## C/UNIX
### libc再実装
- C言語の標準関数（libc）のサブセット及び汎用関数（split関数や単方向リスト）を実装（3700行程度）
- 最低限の関数（システムコール、malloc）のみ使用。（printf等の高級関数は不使用）
- 自分でprintfやatoiなどを実装し、メモリ操作、ビット演算などのコンピュータサイエンスの基礎を習得
- 学習記録：[浮動小数点型をprintfを使わずに出力する方法](https://qiita.com/daitai-daidai/items/44632da01d4b0a18c33e)
- リポジトリ：https://github.com/dai65527/libft

### レイトレーサ実装
- フルスクラッチのレイトレーサを実装。（3,200行程度）
- ウィンドウマネジメントシステム以外はの使用関数は上記の自作ライブラリのみ。
- 基本図形の描画、鏡面反射、拡散反射などを実装。
- リポジトリ：https://github.com/dai65527/miniRT 

![spheres](assets/spheres.png)

### Shell再実装
- 最低限の機能を備えたShellを自作(3,500行程度)
- パイプ、リダイレクトにも対応。
- 自作ライブラリとシステムコールのみ使用。
- スキル：マルチプロセス、プロセス間通信
- [TrainCoffeeBoy](https://github.com/TrainCoffeeBoy)さんとの共同プロジェクト。
- 全体設計、プロセス管理、パイプ、リダイレクト機能、組み込みコマンドの実装を担当。
- リポジトリ：https://github.com/dai65527/minishell
- 動画：https://twitter.com/daitaidaidai789/status/1346351715293904896

### その他
- マルチスレッド/プロセスプログラミング
- アセンブリ

## C++
### コンテナクラス再実装
- STLのコンテナクラスのlist、vector、map、stack、queue、及びイテレータシステムを再実装。（3,800行程度、テスト含まず）
- スキル：オブジェクト思考プログラミング、テンプレートプログラミング、データ構造(双方向リスト、平衡二分探索木)、アルゴリズム（探索、ソート、マージ、イテレータ）
- 実装関数が多いため、テスト駆動開発を実施(10,000ケース程度)。
- リポジトリ：https://github.com/dai65527/ft_containers

### Webサーバ（作成中）
- Nginxライクな軽量Webサーバを外部ライブラリなしで作成中
- イベント駆動による同時アクセス処理、CGIプログラムに対応
- スキル：HTTP、ソケットプログラミング、ノンブロッキングI/Oなど
- テストフレームワーク(google test)を導入。
- リポジトリ（追記予定）

![webservflow](assets/webserv_design.png)

## Web技術
### ft_server(Docker)
- Docker上でLEMP環境を構築
- ベースイメージ: Debian (Nginx、MySQL等の公式イメージは不使用)
- リポジトリ： https://github.com/dai65527/ft_server

### ft_services(Kubernetes)
- シングルノードのKubernetesでマイクロサービス環境を立ち上げ
- サービス構成: Nginx/WordPress/phpMyAdmin/MySQL/Grafana/InfluxDB/vsftpd/MetalLB
- ベースイメージ: Alpine Linux (Nginx、MySQL等の公式イメージは不使用)
- リポジトリ：https://github.com/dai65527/ft_services

## Webフレームワーク等
### Pokedex (Vue.js)
- Vue.jsによるポケモン図鑑。（[PokeAPI](https://pokeapi.co/)を使用）
- 使用技術：TypeScript、Vuetify、vuex、vue-router
- [ToYeah](https://github.com/ToYeah)さんとの共同プロジェクト。
- Page：https://dai65527.github.io/pokedex_vue/
- リポジトリ：https://github.com/dai65527/pokedex_vue

### Ruby/Ruby on Rails
- 学習中
- Webアプリケーション製作予定

- Go
  - 機能を絞ったシンプルな言語仕様で書きやすいながらも、高機能で気に入っています。
  - Gopher道場などの外部勉強会に参加し、実践的な知識をつけることを意識しています。
- Ruby/Ruby on Rails
  - 言語/フレームワークのみでなく、Webアプリケーション開発の全般的なの習得のために学習をしています。
- クラウド
  - 高機能かつ容易なWebアプリを開発する上で必要だと感じ、AWSの学習をしています。
  - 現在はAWS Academy Cloud Foundationsを受講しています。
  - 業務及び個人開発のWebアプリに活用したいと考えています。
- JavaScript/NodeJS/TypeScript
  - フロントエンドではJavaScriptは必須であり、バックエンドでも注目を集めていることから学習を進めています。
  - TypeScriptについても独特の型システムに慣れ、大規模開発に対応できるよう、JavaScript学習と並行して積極的に行っています。
  - 学習記録：[Nuxt.jsとNestJSでTypeScriptなTodoリストを作ってみる（バックエンド編）](https://qiita.com/daitai-daidai/items/a5e744120492bcc2c591)

## チーム開発
- 42Tokyoのプロジェクトでチーム開発を経験済み(Git/GitHubを活用した相互レビューを実施）
- 前職では100億円規模のプロジェクトのプラント設備設計者として配管、土建、電気計装との担当者とコミュニケーションを取りながら設計を行う。(設計担当者のみで十数人程度、PJ全体で数十人規模)。

# その他
## 自信のある点
### 自走力・キャッチアップ力
- 42Tokyoでは講師、教科書等の仕組みが無い中、上記の内容を4~5ヶ月で習得しました。
- 前職では、素早く業務にキャッチアップし、新卒1年目から一人で現場不具合対応を担当するなど早期に戦力として活躍し、「素直で吸収が早い」との評価をいただいていました。
- 42Tokyoのカリキュラム外でもWeb関係技術を積極的に学習しています。
- 予備校等には通わずに高校、大学受験突破した経験があります。
- 留学等の経験はなく、独学でTOEIC950点を獲得しています。

### 工学分野の基礎的な素養
- 大学で機械工学を専攻、また、独学で電気工学を勉強していたため、数学、物理、機械、電気、制御などの基本的素養はあります。
- 大規模プラントの設備設計などに携わった経験もあり、複雑なシステムを噛み砕いて理解する素養はあると思います。

### コミュニケーション
- 高校時代はラグビー部で副キャプテン、大学時代は鳥人間パートリーダーなど、リーダーシップを発揮して活動してきました。
- 前職では100億円オーダーのプロジェクトに携わり、客先、ベンダー、協力会社、現場作業員、他部署など幅広い関係者とコミュニケーションをとり仕事を進めてきました。
- 42Tokyoでは講師不在の中、他の生徒と教え合い、コードレビューをしあうことで、日々、質問力、説明力を鍛えています。

## 興味のある分野・領域
- 現在はコンピュータサイエンスやネットワーク寄りの基礎的な学習をしていますが、応用的な技術を用いてプロダクトを開発することにも興味があります。
- 技術的分野全般に興味がありますが、特にバックエンド/インフラ寄りの技術に興味があります。
- 特定の言語や技術というよりは各言語の特徴や機能などを踏まえて使いこなせるようになりたいと思っています。
- 人間がやっていたことを自動化する、人間のできることを広げる技術に興味があります。（AI/機械学習、アルゴリズムや最適化技術、ノーコードやDevOps、さらにはハードウェアの制御にも興味があります。）
- ものごとのなりたちを知ることが好きなので、低レイヤーや各種フレームワークの中身にも興味があります。

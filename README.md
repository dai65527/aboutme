経歴とスキルセットの紹介（20.3.11現在。随時更新）

# 要約

- 42Tokyoでソフトウェアエンジニアリングを学んでいます。
- 早稲田機械院卒、前職は元大手プラントエンジニアリング企業。
- 42TokyoでC/C++/Linux/Docker/Kubernetesを学習中
- 独学でWeb技術（JavaScript/TypeScript/Vue\.js/React/NodeJS/Ruby/Ruby on Rails/AWS）を学習中

# 基本情報
|key|value|
|----|----|
|名前|Daiki Nakano|
|年齢|26|
|所属中|[42Tokyo](https://42tokyo.jp/)|
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
- GPA：3.47/4
- 学士（工学）

### 2017年4月〜2019年3月 早稲田大学基幹理工学研究科機械科学専攻
- エネルギー工学系の研究室に所属し、ヒートポンプシステムの性能評価、制御検討に関する研究を行う
- 数値シミュレーションプログラムを構築し、実機と合わせ検証 (NTT系企業からの委託研究)
- その他NEDO採択プロジェクトの研究補助業務にも従事。
- 修士（工学）

### 2019年4月〜2020年8月 大手プラントエンジニアリングメーカー
- 都市環境プラントの設計業務に従事。
- 計画、実施設計業務、既設工場不具合対応、ベンダー・協力会社管理、海外子会社教育など幅広い業務に従事。
- エネルギー工学の知識と持ち前の吸収力にて、新卒1年目にして一人で現場対応を任されるなど、早い段階から戦力に。
- 仕事にやりがいはあったものの、調整業務が大半をしめており、エンジニアとしてのキャリアに不安を持つ。
- エンジニアが企画〜設計〜コーディングまで携われるソフトウェアエンジニアに魅力を感じ、独学開始。

### 2020年8月 エンジニア養成機関42Tokyo 入学試験（Piscine）受験
- フランス発エンジニア養成機関42Tokyoの入学試験「Piscine」を受験（4週間）
- 合格基準が不明確な中1ヶ月コーティングを続け、精神力と自走力を鍛え直す。

### 2020年10月〜現在 エンジニア養成機関42Tokyo
- Linux、C/C++、Docker/Kubernetesを学習（内容は後述）
- 講師、メンター不在の中で自走力とコミュニケーション力を鍛える。
- 現在Lv.5.02（3ヶ月先行して入学した1期生も含め、3月10日現在学内トップ）
- 今後はさらに低レイヤーなど基礎を深めつつ、Web技術やAIなど応用的な技術を習得する予定
- 並行して、JavaScript/Rubyなどの技術も勉強中
- 1日10時間以上毎日プログラムを書き続けています。
- 42Tokyoでの学習記録：https://note.com/daitai_daidai/n/nf69533f53646

# スキル
## C/UNIX
### libc再実装
- C言語の標準関数（libc）のサブセット及び汎用関数（split関数や単方向リスト）を実装
- printfやatoiなどを実装し、メモリ操作、ビット演算などの基礎を習得
- 学習記録：[浮動小数点型をprintfを使わずに出力する方法](https://qiita.com/daitai-daidai/items/44632da01d4b0a18c33e)
- リポジトリ：https://github.com/dai65527/libft

### レイトレーサ実装
- フルスクラッチのレイトレーサを実装
- 基本図形の描画、鏡面反射、拡散反射などを実装
- リポジトリ：https://github.com/dai65527/miniRT 
![spheres](assets/spheres.png)

### Shell再実装
- 最低限の機能を備えたShellを自作
- パイプ、リダイレクトにも対応
- スキル：マルチプロセス、プロセス間通信
- [TrainCoffeeBoy](https://github.com/TrainCoffeeBoy)さんとの共同プロジェクト
- リポジトリ：https://github.com/dai65527/minishell
- 動画：https://twitter.com/daitaidaidai789/status/1346351715293904896

### その他
- マルチスレッド/プロセスプログラミング
- アセンブリ

## C++
### コンテナクラス再実装
- STLのコンテナクラスのlist、vector、map、stack、queue、及びイテレータシステムを実装
- スキル：オブジェクト思考プログラミング、テンプレートプログラミング、データ構造、アルゴリズム
- リポジトリ：https://github.com/dai65527/ft_containers

### Webサーバ（作成中）
- Nginxライクな軽量Webサーバを外部ライブラリなしで作成中
- 同時アクセス処理、CGIプログラムに対応
- HTTP、ソケットプログラミング、ノンブロッキングI/Oなど
- リポジトリ（追記予定）

## ネットワーク/インフラ
### ft_server
- Docker上でLEMP環境を構築
- ベースイメージ: Debian
- リポジトリ：（追記予定）

### ft_services
- シングルノードのKubernetesでマイクロサービス環境を立ち上げ
- サービス構成: Nginx/WordPress/phpMyAdmin/MySQL/Grafana/InfluxDB/vsftpd/MetalLB
- ベースイメージ: Alpine Linux
- リポジトリ：（追記予定）

## JavaScript/TypeScript (Vue.js、React、Node.js)
### Pokedex
- Vue.jsによるポケモン図鑑。（[PokeAPI](https://pokeapi.co/)を使用）
- 使用技術：TypeScript、Vuetify、vuex、vue-router
- [ToYeah](https://github.com/ToYeah)さんとの共同プロジェクト。
- Page：https://dai65527.github.io/pokedex_vue/
- リポジトリ：https://github.com/dai65527/pokedex_vue

### その他
- NodeJSやVue.jsに関する学習をしています。
- 学習記録：[Nuxt.jsとNestJSでTypeScriptなTodoリストを作ってみる（バックエンド編）]（https://qiita.com/daitai-daidai/items/a5e744120492bcc2c591）

## Ruby/Ruby on Rails
- 現在勉強中
- Webアプリケーション制作予定

## チーム開発
- 42Tokyoのプロジェクトでチーム開発を経験済み(Git/GitHubを活用）。
- 前職では100億円規模のプロジェクトの一員として働いていました。

# その他自信のある点
### 自走力・キャッチアップ力
- 42Tokyoでは講師、教科書等の仕組みが無い中、上記の内容を4~5ヶ月で習得しました。
- 前職では、素早く業務にキャッチアップし、新卒1年目から一人で現場不具合対応を担当するなど早期に戦力として活躍しました。
- 42Tokyoのカリキュラム外でもWeb関係技術を積極的に学習しています。
- 予備校等には通わずに高校、大学受験突破した経験があります。

### コミュニケーション
- 高校時代はラグビー部で副キャプテン、大学時代は鳥人間パートリーダーなど、リーダーシップを発揮して活動してきました。
- 前職では100億円オーダーのプロジェクトに携わり、客先、ベンダー、協力会社、現場作業員、他部署など幅広い関係者とコミュニケーションをとり仕事を進めてきました。
- 42Tokyoでは講師不在の中、他の生徒と教え合い、コードレビューをしあうことで、日々、質問力、説明力を鍛えています。

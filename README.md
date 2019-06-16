# 職務経歴書

## 基本情報
- 氏名: 近藤大介
- GitHub: [gimKondo](https://github.com/gimKondo)
- Qiita: [gimKondo](https://qiita.com/gimKondo)

## サマリー
CAD開発の経験をバックボーンに持ち、メモリやCPUなどのコンピュータ寄りの領域への理解を強みとして、主としてWebシステムのバックエンドエンジニアとして働いています。
ただし、3～10人程度の比較的小さなチームでの開発が多く、ほとんどのケースでクラウドインフラの構築やフロントエンドの開発を兼務していました。結果として、サーバサイド中心としながら、クラウドインフラからフロントエンドまで対応できるスキルを習得しています。

開発言語やフレームワークは特定のものに拘泥せず使いますが、最近はサーバサイドの実装にElixir + Phoenixを好んで使っています。

開発プロセスやチーム改善にも強みを持っています。
例えば、テストが無いレガシーな開発チームでは、自動化されたユニットテストやCIを導入し安定した製品に繋げました。
顧客の要件が拾い切れず進行が遅れていたプロジェクトではスクラムを導入し、スクラムマスターとして納期に要件を満たした製品を納品するのに貢献しました。
新規技術の導入時には、ペアプログラミングやモブプログラミングを取り入れ、チームメンバーのスキルと生産性を高めました。

これらの実績から、現在は社内全体の技術選定やチーム横断的な開発プロセス改善を実施する職務に就いています。

## スキル
### 言語・フレームワーク
- Elixir
  - Phoenix
- C, C++03, C++11
  - Visual C++, GCC
  - MFC, Windows Form
- Go
- Ruby
  - Ruby on Rails, Sinatra
- JavaScript
  - Node.js
  - Electron
  - Vue.js
- C#
  - WPF, Windows Form
- Java8
  - Spring Boot
  - DBFlute
  - Thymeleaf
- Haskell

### ミドルウェア
- Database
  - MySQL, PostgreSQL, Oracle Database, DB2, SQLite3, Redis
- Webサーバ
  - Nginx, Apache HTTP Server

### クラウドプラットフォーム
- AWS
  - EC2, Lambda, ELB
  - S3, RDS, DynamoDB, ElastiCache
  - CloudFront
  - CloudWatch
  - CloudFormation
- GCP
  - Kubernetes Engine
  - Cloud Storage
- Firebase
  - Authentication
  - Cloud Firestore

### 開発ツール
- ソース管理
  - Git, VSS, TFS
- 仮想環境
  - Vagrant, Docker
- エディタ
  - Vim, VSCode
- CIツール／サービス
  - Jenkins
  - CircleCI

## 職歴・学歴
### 株式会社リゾーム
- 職務 2018.10～現在: CTM(Chief Technical Manager)
- 職務 2015.1～2018.9: PG, SE

#### クレジットカード バックエンドシステム 新規開発
- 期間: 2018.9～2019.2
- 担当: スクラムマスタ, アーキテクト, バックエンドエンジニア
- 開発規模: 15人月
- 使用技術
  - Go
  - C
  - git, GitLab
  - Vagrant
  - DB2, PostgreSQL

新規の取引先追加を機に、旧システムをGoにリプレースした案件です。
古いシステムのため、顧客も仕様を把握できていなかったため、C言語で書かれた旧システムから解析し仕様を解析するところからスタートしました。

顧客の要件が固まっていないこともあり、スクラムを導入してスプリントごとにソフトウェアと要件を擦り合わせながら進行しました。
また、経験の浅いメンバーが中心で、Goの経験者も少なかったため、適宜モブプログラミングを導入しました。
これにより各メンバーが一定水準のスキルを習得し、安定したプロジェクトの進行に繋がりました。

#### イラスト投稿サイト 新規開発
- 期間: 2017.10～2018.9
- 担当: プロジェクトマネージャ, バックエンドエンジニア, インフラエンジニア, フロントエンドエンジニア
- 開発規模: 50人月
- 使用技術
  - Elixir, Phoenix, ExUnit, credo
  - Vue.js, ESLint
  - git, Backlog
  - Jenkins
  - Selenium
  - Vagrant
  - Docker
  - Kubernetes
  - MySQL
  - AWS: S3, CloudFront
  - GCP: GKE, GCE
  - Firebase: Authentication

自社サービスとしてゼロから製作したBtoCサービスの開発案件です。

企画担当1人、技術者2人からスタートし、当初は主に要件定義、サーバサイドの技術選定と基本設計、およびフロントエンドの技術選定を担当しました。
後に2人の開発メンバーを迎えて以降は、プロジェクトマネージャを兼任しながら、サーバサイドを中心にインフラ、フロントエンドを含めた開発者を担当しました。

プロジェクトマネージャとしては、チケット管理、各種アジャイル開発イベントのファシリテートをしながら、テスト戦略の決定、CIの導入、デプロイ手順の整備などを実施しました。
特にCI、デプロイ周りでは社内で知見の少なかったDocker + Kubernetes(on GKE)を導入し、開発からステージングや本番への安定して素早いデプロイに寄与しました。
サーバサイドの開発者としては、基盤設計と主要部分を実装しました。

#### FXトレードツール バックエンド開発
- 期間: 2015.7～2017.10
- 担当: バックエンドエンジニア, プロジェクトマネージャ
- 開発規模: 3～5人チームの継続開発
- 使用技術
  - Ruby
  - Java8
  - C++11
  - PostgreSQL
  - Redis
  - WebSocket
  - git, BitBucket
  - Selenium

複数のマイクロサービスから構成されるアプリケーションの各種サービスを顧客側の技術者と連携して開発した案件です。

#### 葬儀会社ポータルサイト開発
- 期間: 2015.1～2015.7
- 開発規模: 8～15人の継続開発(途中参画)
- 使用技術
  - Java8
  - Thymeleaf
  - DBFlute
  - PostgreSQL
  - git, Backlog
  - Selenium

### 株式会社ダイテック
- 職務 2006.4～2014.12: PG, SE

#### 設備建築CADアプリケーション部 新規開発
- 担当: アプリケーションエンジニア
- 期間: 2012.6～2015.12
- 使用技術
  - Visual Studio2010
  - C++11, Google Test
  - Haskell
  - TFS(Team Foundation Server)
  - SQLite3

主力製品の後継製品として、新規にゼロから製作したプロジェクトです。
アプリケーション部の先行開発チームとして、基盤設計、テスト戦略の選定と主要部の先行実装を担当しました。

並行してカーネル部の開発者と協力し、CAD内部で動かすためのDSLの実行環境の開発にも関与しました。
DSLの言語仕様設計、およびVMとデバッガを担当しました。

後続メンバーの追加時には、C++11を使えるエンジニアが少なかったため、勉強会のファシリテートなど、導入補助も実施しました。
また、社内にコードレビューが無かったため、TFSの運用ルール策定とともにコードレビューのフローも導入しました。

#### 設備建築CADアプリケーション部 追加開発
- 期間: 2009.5～2012.5
- 使用技術
  - Visual Studio2005, Visual Studio2010
  - C++03
  - VSS

#### 電子入札システム 新規開発
- 期間: 2007.10～2008.10
- 担当: バックエンドエンジニア, フロントエンドエンジニア
- 使用技術
  - Java6
  - Oracle Database
  - VSS

#### 設備建築CADカーネル部 追加開発 2006.4～
- 期間: 2006.4～2009.4
- 担当: アプリケーションエンジニア
- 使用技術
  - Visual Studio6.0, Visual Studio2005
  - C++03
  - VSS

プログラミングはほぼ未経験で入社したため、OJTでプログラミングの基礎を教わりながらCADのカーネル部の実装を担当しました。
OJTで非常に良い師を持てたこともあり、コーディング、コンピュータのアーキテクチャなどを深く学びました。
CADのカーネルという性質上、メモリの効率的な利用が求められるため、低レベルな領域の知識を身に付けました。

### 岐阜大学・農学研究科修士課程
- 2006.3 修了
- 森林生態学専攻
- 主な研究テーマ
  - 河畔林の樹種分布と変遷
  - 冷温帯林の着生植物の分布

## OSS
### TRPG(テーブルトークRPG)用サウンドツール
- [リポジトリ](https://github.com/gimKondo/sound-of-cthulhu)
- 使用技術: Electron, Vue.js, CircleCI
- 企画、設計、実装を担当

### 音声文字起こし＆Slack転送ツール
- [リポジトリ](https://github.com/gimKondo/talkw2)
- 使用技術: HTML, JavaScript
- 機能追加、バグ修正、リファクタリング

### HTTP/3 explained 日本語訳
- [リポジトリ](https://github.com/mohikanz/http3-explained)
- QUICについての記述の一部を翻訳
- 翻訳レビュー

### Elixir School 日本語訳
- [リポジトリ](https://github.com/gimKondo/elixirschool)
- 11章の翻訳を担当
- 誤訳修正

### SQLite3クライアントツール
- [リポジトリ](https://github.com/sqlitebrowser/sqlitebrowser)
- 使用技術: Qt, C++, SQLite3
- バグ修正

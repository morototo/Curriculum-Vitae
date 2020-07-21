# 職務経歴書
## 基本情報

| key | value |
|:-----------|------------:|
| 名前       |諸角和希(Kazuki Morokado)|
| 出身       |北海道札幌市|
| 年齢       |３０|
| 居住地     |福岡県西区|

## スキル
- OS
  - Amazon Linux
  - Amazon Linux2
  - CentOS 6.9, 7.2
  - Ubuntu 14.04, 16.04
- 言語
  - Ruby
    - ３年程度使用
  - PHP
    - ３年程度使用
  - Python
    - ３年程度使用
  - Java
  - Javascript
  - HTML/CSS
  - Shellscript
  - 日本語
    - ネイティブ
  - 英語
    - 基本会話はOK
    - 半年のオフショア開発の経験あり。コミュニケーションは全て英語の文章ベース。
- フレームワーク
  - Ruby on Rails
    - 基本的に毎日いじっている。
    - ダッシュボード、マッチングアプリ、ブログ等を作成
  - Django
    - APIサーバとして構築経験あり
  - Laravel
    - APIサーバとして構築経験あり
    - passportを使用した認証サーバとして構築経験あり
  - FuelPHP
    - APIで開発経験あり
  - jQuery
  - React.js
  - Play Framework
- その他
  - DB/キャッシュ/検索エンジン
    - MySQL
    - PostgreSQL
    - Elasticsearch
    - MongoDB
    - Redis
  - Webサーバ
    - Nginx
    - Apache
  - 仮想環境
    - Docker
    - Vagrant
  - ログ管理
    - Fluentd
  - 構成管理
    - Ansible
    - Chef
    - Terraform
  - DevOps
    - Jenkins
    - Capistrano
    - CircleCI
  - 負荷ツール
    - Locust
    - Jmeter
  - 監視ツール
    - Mackerel
    - NewRelic
  - AWS
    - EC2
    - ECS(Fargate)
    - Route53
    - S3
    - Athena
    - RDS
    - Lambda
    - DataPipeline
    - IAM
    - Elasticsearch service
    - SageMaker
  - 機械学習系
    - mlflow
    
## 強み
- どちらかというとフロントよりインフラ/バックエンドの方が得意
- 経理経験があるので経理関係の開発は割と得意
- コミュニケーションは苦手ではないので人前に出て話すのも苦ではない

---

## 職務経歴
### 2020/05 ~  ソフトウェア開発会社(業務委託）
  システムエンジニアとして自社サービスの開発に従事
#### 2020/05 ~
##### ビジネスコミュニケーションツールのコミュニケーション解析APIの構築
- APIの開発、運用
- データの可視化
```
- Ruby 2.7.1
- Rails 6.0.2
- PosgreSQL 12.2
- Ruby on Rails ()
- AWS(S3, Athena, EC2)
```

---
### 2017/10 ~ 2020/05 ソフトウェア開発会社(業務委託）
  システムエンジニアとして自社サービスの開発に従事
#### 2017/10 ~
##### BtoC, BtoB マッチングWebサービス開発 
- 自社所有のマッチングWebサービスをカスタマイズ開発
```
使用言語/環境
- Ruby (2.3.5 ~ 2.5.1)
- Ruby on Rails (4.2.5 ~ 5.1.4)
- Heroku AWS S3 MySQL
```

---

### 2017/01 ~  ソフトウェア開発会社(正社員）
  システムエンジニアとして自社サービスの開発に従事

#### 2020/05 ~ 
##### 機械学習ツールの調査、移行
- 稼働中のmlflowをAWS SageMakerへ移行
- 管理コストの削減のため
- mlflow, SageMkaeへの負荷試験の実施
```
使用言語/環境
- Jmeter
- mlflow 1.9.1
- AWS(EC2, SageMaker)
```

#### 2020/03 ~ 2020/05
##### 位置情報データのDB整備
- POIデータ、オープンデータ（Zenrin, IncrementP, OpenStreetMap)の整備
- PostgreSQL, Athenaへのインポート
- 仕様整理
```
使用言語/環境
- PostgreSQL
- AWS(Athena)
```

#### 2020/01 ~ 2020/03
##### EC2からECRに移行し、Auto Scalingの設定・DevsOps環境を構築
- ユーザ増加により、サーバを自動スケーリングする必要性が出てきた
- 自社サーバを全てECRに移行し、Auto Scalingによる自動スケーリングを作成
- CircleCIとECRを接続し、DevOps環境を構築
```
使用言語/環境
- AWS(EC2, ECR(+Fargate))
- CircleCI2.1
```

#### 2019/12 ~ 2020/01
##### 外部公開API改修
- API速度改善の為、APIが自社サーバ（Elasticsearch）を参照している箇所を全てAthenaに変更する修正
```
使用言語/環境
- Django 2.0
- Python 3.5.1 
- AWS(Athena)
```

#### 2019/10~2019/11
##### 負荷試験ツールの作成
- 汎用性のある負荷試験ツールを作成し、シナリオを作成すれば本番同様の環境に負荷試験ができるようにした
```
使用言語/環境
- Jmeter
- Python 3.5.1 
- AWS(EC2)
```

#### 2019/8~2019/9
##### 管理画面開発
- 他社データを可視化する管理サーバ開発
- iOS,Androidアプリからのデータを動的に表示する管理画面を作成
```
使用言語/環境
- Ruby2.5.1
- Ruby on Rails 5.2.1
- AWS(S3, Lambda)
- MySQL 5.7
```

#### 2019/3~2019/7
##### 認可サーバ開発
- 自社APIの認可サーバを開発（Oauth2.0認証)
- FuelPHPで使用しているAPIの認証部分を全てLaravelに移行
- DBサーバをNoSQLからRDBMSへ移行
```
使用言語/環境
- FuelPHP 1.7.1
- Laravel 5.6
- MongoDB Atlas
- MySQL 5.7
```

#### 2019/2~2019/3
##### DevOps環境の整備
- Jenkinsを使用した自動デプロイ環境の構築 
- CircleCIの導入 
- ChefからAnsibleへの切り替え。 
- Mackerelによる監視システムの導入 
- 踏み台サーバの構築
```
使用言語/環境
- Jenkins 2.157
- CircleCI 2.0 
- Chef 12.5.1 
- Ansible 2.7.9
- Mackerel
```

#### 2018/12 ~ 2019/2
##### 自社保有のElasticsearchサーバをAWS Elaticseachへ切り替え 
- ユーザ増加に伴い負荷軽減、運用効率向上を目的としてElasticsearchをAWSへ切り替え
```
使用言語/環境
- Elasticsearch 5.6.1
- AWS Elasticsearch
- Fluentd
- CentOS 6.9
```

#### 2018/10 ~ 2018/11
##### 管理画面サーバ開発
- 自社サーバ内に保存されているデータを外部に公開するサーバ開発
```
使用言語/環境
- Ruby on Rails 5.2.1
- Ruby 2.5.1
- Ubuntu 16.04
```

#### 2018/7 ~ 2018/9
##### 位置情報を使用したポイント交換アプリ (iOS, Android)のサーバ開発
- APIサーバ開発、管理画面開発
- sidekiqを使用した非同期処理を実装
```
使用言語/環境
- Ruby on Rails 5.1.6 
- Ruby 2.5.1 
- Ubuntu 14.04
- Redis
```

#### 2018/5 ~ 2018/6
##### GDPR対応
- 現サーバ環境をすべてAWSのEUリージョンに構築 
```
使用言語/環境
- AWS EC2
- Chef
- capistrano 
```

#### 2017/12 ~ 2018/4
##### 自社データを参照するDevelopment Kit(Python) を使用したAPI開発
- 自社データを外部から参照できるAPIを開発 
```
使用言語/環境
- Django 2.0
- Python 3.5.1 
- CentOS7.2
```

#### 2017/12 ~ 2018/4
##### 位置情報を使用した健康アプリのサーバ開発
- Gaurunによるプッシュ通知サーバ構築・開発。sidekiqによる非同期処理サーバ構築・開発。
```
使用言語/環境
- Ruby on Rails 4.2.3
- Ruby 2.2.2
- sidekiq 5.0.4
- Gaurun
- Ubuntu 14.04 
```

#### 2017/4 ~ 2018/6
##### Elasticsearch バージョンアップ対応
- バージョンアップに伴うサーバ修正作業 
```
使用言語/環境
- Elasticsearch1.7.3
- Elasticsearch5.5.2 
```

---

### 2015/09 ~ 2016/12 某通信会社(正社員）
  システムエンジニアとして開発に従事

#### 2016/03~2016/09
##### SNS連携認証開発
- Wifi認証サーバにおけるSNS連携を利用した認証機能の開発
```
使用言語/環境
- Java
- MySQL
- RedHatLinux
```

#### 2015/11~2016/02
##### サーバ機能拡張・開発
- サーバ開発における他サーバとの通信機能の開発
```
使用言語/環境
- Java
- HTML
- JavaScript
```

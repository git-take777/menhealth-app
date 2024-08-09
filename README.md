# menhealth-app

- 作成背景

  - 1 年前から健康意識が高くなり、ジムに通い 筋肉量や体重、BMI などを管理したい気持ちがあり作成。また、LINE Keep にメモとしてデータを管理していたが、Keep サービスが終了するためにこの際に運用するために作成

- 技術選定
- バックエンド: Laravel v10 (スピーディーな開発のため)
- フロントエンド: React v18
- データベース: MySQL (Laravel との親和性が高い)
  - 現状: DBサービスはFirebaseを検討中 (初期段階 8/7)
- デプロイ: AWS Elastic Beanstalk (迅速なデプロイ)

- いずれしたいこと

  - LINE Keep で管理している内容を Python でスクレイピングして過去のデータを管理したい。

- 技術ポイント
- docker
- docker/node/に default.conf をコマンドで作成する
  - 内容は参照してほしい
- .dockerignore を作成して同様に内容を確認して書き加える

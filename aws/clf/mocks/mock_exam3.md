# udemy 模擬テスト(基本レベル①)

## 2.
- AWS CloudTrail: AWSサービス全体のアカウントログやAPIコールを記録。

## 3.
- セキュリティグループ
    - サーバー単位のトラフィック制御機能
    - ステートフル: インバウンドのみ設定すればアウトバウンドも許可される
    - 許可のみをIn/Outで指定
    - デフォルトでは同じセキュリティグループ内通信のみ許可
    - 全てのルールを適用
- ネットワークACL
    - VPC/サブネット単位向けのトラフィック制御機能
    - ステートレス: インバウンド設定だけではアウトバウンドは許可されない
    - 許可と拒否をIn/Outで指定
    - デフォルトでは全ての通信を許可する設定
    - 番号の順序通りに適用
- ルートテーブル: サブネットをルートテーブルに関連づけるために利用するルート設定テーブル。

## 10.
- Amazon SNS: Managed型のpub/subメッセージングサービス。コンポーネント間のメッセージ通知や  
&nbsp;&nbsp;アラート通知に利用する。
- Amazon SES: Eメールの送受信機能を提供するサービス。
- Amazon SQS: ポーリング方式のキューイングサービス。

## 13.
- インターネットゲートウェイ
    - インターネットでルーティング可能なトラフィックの送信先をVPCのルートテーブルに追加すること。VPCに配置。
    - public IPv4アドレスが割り当てられているインスタンスに対してネットワークアドレス変換(NAT)を行うこと。
- NATゲートウェイ: プライベートアドレスをインターネット用のパブリックIPアドレスに変換することでプライベートネットワークからインターネットへの通信を可能にしてくれるゲートウェイ。

## 16.
- EFS: インターネットからアクセスできず、かつ複数のEC2インスタンスからアクセスすることができるストレージ。  
&nbsp;&nbsp;EC2インスタンスを立ててアクセスする。

## 18.
- S3: ユーザーの設定なしにAWSでストレージリソースを自動的にスケールアップ/ダウンして変動する需要に対応する。

## 19.
- IAMユーザーグループ: 複数のユーザー権限を指定できる。
- IAMロール: AWSリソースに対してアクセス権限を付与する方法。
- AWS Organizations: 複数アカウントを統合管理する機能、権限設定は直接はできない。SCPというポリシーで管理。

## 21.
- Amazon Aurora: DBインスタンスは起動すると常に自動バックアップが有効になっている。

## 22.
- Route53: ヘルスチェックによるフェールオーバーの実行が可能となり、正常なインスタンスのみを利用して  
&nbsp;&nbsp;障害を回避することが可能。

## 25.
- S3 Glacier: 1年に1~2回アクセスされ、非同期で取り出されるアーカイブデータ向け。  
&nbsp;&nbsp;通常のデータ検索で3~5時間を要する。

## 28.
- カーブアウト: 企業が事業の一部を切り取って新しく新企業を独立させること。

## 35.
- IaaS: クラウド事業者がハードウェア提供。自社でミドルウェア、OSを購入し、アプリケーションを開発。
- PaaS: クラウド事業者がミドルウェアまで提供。自社はアプリケーション開発に専念。

## 38.
- S3 Transfer Acceleration: CloudFrontのエッジロケーションを利用してユーザーに近いエッジロケーションを介した  
&nbsp;&nbsp;S3へのファイル転送を可能にするサービス。

## 42.
- Amazon RDSのリードレプリカ: リードレプリカを追加することで読み取り処理に対するデータ冗長化を実現して、  
&nbsp;&nbsp;その可用性と耐久性を向上させる。

## 43.
- Amazon EMR: Apache HadoopやApache Sparkなどのビッグデータフレームワークとして、大量のデータを処理  
&nbsp;&nbsp;および分析するManaged型クラスタープラットフォーム。
- Amazon Kinesis: ストリーミングデータをリアルタイムで収集するサービス。
- Amazon Athena: Amazon S3内のデータを標準SQLを使用して簡単に分析できる。

## 44.
- AWS Systems Manager: EC2インスタンスの設定と管理を簡単にできる運用管理サービス。

## 45.
- Amazon Inspector: 事前に定義されたテンプレートに基づいてEC2インスタンスを分析し、脆弱性をチェックするサービス。
- Amazon GuardDuty: AWSアカウントとワークロードを継続的にモニタリングし、悪意のあるアクティビティや不正なアクティビティを保護する。
- AWS Config: AWSリソースの管理ツール。AWSリソースの設定変更を継続的にモニタリングする。

## 48.
- ELBの種類
    - ALB: HTTP通信を利用するwebアプリケーション使用。
    - CLB: 古いタイプにELB。廃止予定。
    - NLB: 超低遅延で高いスループットを維持して、秒間何百万リクエストを捌くように設計

## 50.
- インスタンスストア: EC2インスタンスの一時的なデータを保持する際に使用するストレージ。  
&nbsp;&nbsp;停止、終了と共にデータ削除される。

## 51.
- AWS Config: ユーザーが構成したAWSリソース設定を継続的にモニタリングおよび記録しており、  
&nbsp;&nbsp設定が適切にされているかの評価を自動的に実行できる。
- Amazon CloudWatch: AWSリソースのモニタリングサービスであり、メトリクスのレポジトリー。  
&nbsp;&nbsp;Amazon EC2などのAWS サービス は、メトリクスをレポジトリーに置き、  
&nbsp;&nbsp;これらのメトリクスを基に統計が取得される。
- メトリクス: リソースやアプリケーションに対して測定できる変数。

## 53. 
- ECS: EC2インスタンスのクラスターでDockerコンテナを実行できるサービス。
- AWS Fargate: コンテナ向けサーバーレスコンピューティングエンジン。

## 62.
- Amazon Cognito: ウェブアプリケーションおよびモバイルアプリに素早く簡単に  
&nbsp;&nbsp;ユーザーのサインアップ/サインインおよびアクセスコントロールの機能を追加できる。

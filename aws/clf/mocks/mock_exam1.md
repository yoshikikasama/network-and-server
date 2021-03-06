# udemy 模擬テスト1

## 1.

- ペネトレーションテスト: システム全体の観点でサイバー攻撃体制がどのくらいあるかを試すために、  
&nbsp;ホワイトハッカーがシステムに侵入するテスト。
- 責任共有モデルにおいてEC2インスタンスに対するセキュリティなどは顧客側の責任範囲とされており、  
&nbsp;顧客側が自由に実施することができる。

## 2.

- AWS CLI: コンピューターに対する指示をコマンド(文字)で行う操作体系のこと。

## 3.

- AWS Organizations: 登録された複数AWSアカウントの支払いを統合でき、一部AWSサービスのボリューム価格階層を  
&nbsp;利用できるのでコストを削減できる。

## 4.

- EBSボリュームのデータバックアップ方式: EBSボリュームのスナップショットを作成することでバックアップを確保できる。

## 5.

- ElasticCache: RDSのクエリをキャッシュに保持して高速アクセスする連携を構築することができる。

## 6.

- SQS: メッセージキューを作成、管理するフルマネージド型サービス。
- SES: アプリケーションなどにEメール機能を実装可能にするEメールサービス。
- API Gateway: 簡単にAPIの作成、配布、保守、監視、保護が行えるフルマネージド型サービス。

## 7.

- リージョン: 個別の地理的なエリア。AZで構成される。
- AZ: 複数の分離されたロケーション。

## 8.

- 複数のユーザーにAWSリソースへのアクセス権限を設定する場合は、IAMを利用する。  
&nbsp;部署ごとに適切なアクセス権限を有したIAMグループを設定する。
- IAMロール: AWSリソースに対してアクセス権限を付与する機能。

## 9.

- Cost Explore: コストと使用状況を表示および分析するために使用できるツール。
- Cost Categories: コストを任意のPJや組織ごとに分割して管理する。

## 10.

- DynamoDB: JSON形式のデータを保存・処理するドキュメント型DB。
- EFS: ファイルストレージ。

## 11.

- コンシェルジュサポート: 請求書やアカウントへの質問に対する迅速な対応が提供されるサポートサービス。
- AWS Trusted Advisor: AWSのベストプラクティスに従ってAWSリソースが利用されているかを評価し、  
&nbsp;リアルタイムのガイダンスを提供するオンラインツール。

## 12.

- AWS Well-Aechitected
    - Reliability・・・回復性の高いアーキテクチャを設計する。  
    - Performance Efficiency・・・パフォーマンスに優れたアーキテクチャを定義する。  
    - Security・・・セキュアなアプリケーション及びアーキテクチャを規定する。  
    - Cost Optimization・・・コスト最適化アーキテクチャを設計する。  
    - Operational Excellence・・・運用上の優秀性を備えたアーキテクチャを定義する。  
    - Sustainability・・・持続可能性が高いアプリケーション運用を実施する。

## 13.

- リザーブドインスタンス(スタンダード): AZ、VPC、インスタンスサイズの変更範囲に限定され、割引率が高い。
- リザーブドインスタンス(compatible): スタンダードの条件、インスタンスファミリー、OSなど柔軟性が高いので割引率が低い。

## 14.

- Snowball Edge: データ移行とエッジコンピューティングのデバイス。機械学習を実行してデータ処理や分析ができる。
- Snowballmobile: トレーラーによる大量データ移行。

## 15.

- AWSリソースが不正な行動に使用されている場合、AWS不正使用対策チームに連絡する。

## 16.

- TAM(Technical Account Manager): ユーザーに対して様々な提言およびガイダンスを提供し、ベストプラクティスに沿ったソリューションの  
&nbsp;計画と構築およびユーザーのAWS運用環境を正常に保つようサポートしてくれる。

## 17.

- S3は仮想ホスト形式のURLとパス形式のURLの両方でバケットにアクセスできる。

## 19.

- CloudWatch: 利用料金が設定した閾値を超えた場合には、通知がトリガーされる請求アラームを設定できる。

## 20.

- 数ヶ月間利用しないアプリケーションのEC2インスタンスへの課金を最小限にするためには、AMIを使用して再び利用する際に、  
&nbsp;利用できるようにする。

## 21.

- AWS Config: AWSリソースのプロビジョニングや設定のルールを定義して、その逸脱を監視できるサービス。
- プロビジョニング: 必要に応じてネットワークやコンピューターの設備などのリソース提供をできるよう予測し、準備しておくこと。
- Amazon Inspector: アプリケーションのデプロイ前と実稼働環境での運用中に、アプリケーションの脆弱性とベストプラクティスからの  
&nbsp;逸脱を特定する。
- AWS System Manager: AWSで利用中のインフラを可視化し、制御するためのサービス。
- CloudWatch: アプリケーション監視とインサイト提供。

## 22.

- S3のデータ保護: 保存データの暗号化とデータのupload前の暗号化。

## 23.

- AWSはグローバルに展開されており、どの国のどのリージョンに対しても即時にインフラを展開することができる。

## 24.

- AZ: 1つまたは複数のデータセンターで構成されている。

## 25.

- CloudWatch: アプリケーションを監視し、システム全体のパフォーマンスの変化に対応して、リソース使用率の最適化を行い、  
&nbsp;運用上の健全性を統括的に把握するためのデータと実用的なインサイトが提供される。
- Amazon GuardDuty: AWSのアカウント、ワークロード、およびS3に保存されたデータを保護するために悪意のあるアクティビティや  
&nbsp;不正な動作を継続的にモニタリングする脅威検出サービス。

## 26.

AWSにデータを保存するメリット: ユーザーは自身のデータを完全に制御することができる。

## 28.

- オンデマンドインスタンス: 秒単位または一時間単位の利用時間に対して課金。
- リザーブドインスタンス: 1年または3年の期間予約して利用することで前払いが可能となる。
- スケジュールドリザーブドインスタンス: 利用時間を周期的に設定できる。

## 29.

- Direct Connect ゲートウェイ: 異なるリージョン間を接続するために利用する機能。
- VPCエンドポイント: VPC内からVPC外のサービスに接続する際に利用するエンドポイント。

## 30.

- AWSのコストと使用状況レポート: アカウントとそのIAMユーザーが使用した各サービスの使用状況が時間単位または日単位の  
&nbsp;明細項目として一覧表示され、コスト配分のためのアクティブ化されたタグも表示される。

## 33.

- リザーブド形式の購入方法が可能なサービス
    - EC2
    - RDS
    - ElasticCache
    - DynamoDB
    - Redshift

## 34.

- Snowball Edge: 1つのアプライアンス(装置)で80TBのデータ容量を移動することができる。　　
&nbsp;現在「Snowball」は推奨されていない。

## 35.

- EC2インスタンス内部の詳細情報を取得するためのCloudWatchの設定方法:  
    - CloudWatchエージェントをEC2インスタンスにインストールする。
    - 適切なIAMロールによってEC2インスタンスのメトリクスが取得できる設定を行う。

- メトリクス: システムのパフォーマンスに関するデータ。
- CloudWatch: アプリケーションを監視し、システム全体のパフォーマンスの変化に対応して、リソース使用率の最適化を行い、  
&nbsp;運用上の健全性を統括的に把握するためのデータと実用的なインサイトが提供される。
- CloudWatch Logs: CloudWatchの機能の一つ。EC2インスタンスへの通信トラフィックデータの取得。メール通知が可能。
- CloudTrail: ユーザーとAPIのアクセスログを取得する機能。CloudWatch Logsを統合的に管理できる。  
&nbsp;CloudTrailにCloudWatch Logsを設定して、証跡ログをモニタリングすることで、特定のアクティビティ発生時に通知を受けることができる。


## 37.

- スポットインスタンス: 一時的にユーザーに貸し出される特別なインスタンスで最大90%の割引がある。

## 38.

- エッジロケーションで利用できるサービス
    - CloudFront
    - Route53
    - AWS WAF
    - AWS Sheild
    - Lambda

## 42.

- TCO計算ツール: ストレージなどのデータ量、仮想サーバー数、サーバー数など計算値として利用する。

## 47. 

- AWS Systems Manager: 
    - EC2などのリソースグループごとに運用データを確認できる。
    - EC2のバッチ、更新、設定変更、削除、停止およびデプロイなどを自動化する。
    - オンプレミス環境のデータを確認できる。

## 49.

- ELBのスティッキーセッション機能: 同じユーザーからきたリクエストを全て、同じEC2インスタンスに送信する機能。
- レイテンシー: データ転送における指標の一つで、転送要求を出してから実際にデータが送られてくるまでに生じる通信の遅延時間のこと。


## 51.

- 共有統制: インフラストラクチャーレイヤーとユーザーレイヤーの両方に適用される統制のこと。  
&nbsp;AWSはインフラストラクチャーの要件を提供し、ユーザーはAWSサービスの使用に対して独自の統制を実装する。
- バッチ管理: AWSがインフラストラクチャーの不具合に対するバッチ適用および修復に責任を負うが、ユーザーはゲストOSおよびアプリケーションの  
&nbsp;バッチ適用に責任を負う。
- 構成管理: AWSがインフラストラクチャーデバイスの構成を保守するがユーザーは独自のゲストOS、DB、アプリ構成に責任を負う。
- ユーザー固有の統制: AWSサービスにデプロイするアプリに基づいて、ユーザーが全ての責任を負う統制。

## 52.

- AWS Config: AWSリソースの設定を評価、監査、審査できるサービス。
- AWS Billing and Cost Management: AWSの請求書の支払い、資料料のモニタリング、コストの分析と管理に使用するサービス。

## 53.

- 従来のサーバーの代わりにEC2インスタンスを使用する利点: フォールトトレランスが容易になる。

## 54.

- Amazon Lightsail: 小規模なwebサイトを構築するために簡易なサーバーセットを提供するサービス。

## 56.

AWS Storage Gatewayの保管型ボリュームゲートウェイ: オンプレミス環境にあるストレージをプライマリーとしてS3に拡張したハイブリッドを構成するために実施するサービス。

## 57.

- Amazon GuardDuty: 悪意のある操作や不正な動作を継続的にモニタリングする脅威検出サービス。主にVPCのフローログやネットワーク情報を分析して脅威判定する。
- Amazon Inspector: AWSにホストされたアプリを評価し、露出、脆弱性、ベストプラクティスに沿っているかなどを判定する。
- CloudTrail: AWSアカウントアクティビティ履歴を記録する。


## 58.

- AWS Managed Microsoft AD: AWS上でMicrosoft ADがマネージドサービスとして提供されているもの。既存のADのAWSクラウドへの拡張を容易にする。

## 59.

- AWS Service Catalog: AWSでの使用が承認されたITサービスのカタログを作成および管理できる。IAMアクセス許可で製品とポートフォリオを表示および  
&nbsp;変更できるユーザーを制御できる。

## 62.

- AWS Databse Migration Service(DMS): オンプレミス環境のDB, RDS, RedshiftなどのAWS DBサービス, EC2にインストールされたDB→  
&nbsp;RDS,DWH, NoSQLDBへ移行するサービス。

## 64.

- リザーブドインスタンス: 「1年間」「3年間」と期間を決めてEC2インスタンスを予約することで通常のEC2インスタンスよりも格安で使うことができる。
- Savings Plans: 1年または3年の期間で一貫したコンピューティング使用量を利用するという契約をすることで割引価格が適用される料金モデル。
- スケジュールドリザーブドインスタンス: 日次、週次、月次と月一回だけのようなバッチ処理などで利用できる。


## 65. 

- リードレプリカ: DBの負荷分散のために作成される参照専用の複製。あるDBの内容を複製したもので、データの追加や更新はできず検索や読み込みのみを行うことができる。
- Aurora: リードレプリカを最大15個設定可能で、複数のAZに跨って展開することができる。


# udemy 模擬テスト(応用レベル①)

## 1.
- セキュリティ対応: 自身が構築したアプリサービスに応じたセキュリティ対応をする必要がある。

## 2.
- AWS re:Post: AWSユーザーが技術的な障害を取り除いて、イノベーションを加速するためのコミュニティ型の質問応答サービス。
- AWS IQ: AWS上のプロジェクトにおけるAWS認定サードパーティーエキスパートの利用を支援するサービス。

## 3.
- タグエディタ: AWSリソースに一度にタグを追加したり、タグを編集または削除する。
- タグ: AWS リソースを特定し、整理するのに使用できるメタデータ。

## 5.
- AWS Direct Connect: オンプレミスからAWSへの専用ネットワーク接続の構築をシンプルにするクラウドサービスソリューション。

## 6.
- AWS インフラストラクチャイベント管理: ビジネスを左右する重要な時期にガイダンスやリアルタイムのサポートを受けることができ、AWS エキスパートがイベントの計画に関わり、アーキテクチャや運用に関するガイダンスやアプローチを教えてくれたり、リアルタイムのサポートを提供してくれるサービス。

## 7.
- Aurora マルチマスター: マスターデータベースを複数構築してWrite性能もスケーラブルに構築可能。

## 8.
- ペネトレーションテスト: ネットワーク、PC・サーバーやシステムの脆弱性を検証するテスト手法の一つ。

## 9.
- クラウドセキュリティの7つの設計原則
    - 強力なアイデンティティ基盤の実装: 最小権限の原則を実装し、役割分担を徹底させ、各 AWS リソースとの通信において適切な認証を実行
    - トレーサビリティの実現: ご使用の環境に対して、リアルタイムで監視、アラート、監査のアクションと変更を行うこと。
    - 全レイヤーでセキュリティを適用する: 複数のセキュリティコントロールを使用して深層防御アプローチを適用。
    - セキュリティのベストプラクティスを自動化する: 自動化されたソフトウェアベースのセキュリティメカニズムにより、スケール機能を改善して、安全に、より速く、より費用対効果の高いスケールが可能。
    - 伝送中および保管中のデータの保護: データを機密性レベルに分類し、暗号化、トークン分割、アクセスコントロールなどのメカニズムを適宜使用。
    - データに人の手を入れない: データに直接アクセスしたりデータを手動で処理したりする必要を減らしたり、排除したりするメカニズムとツール使用
    - セキュリティイベントに備える: 組織の要件に合わせたインシデント管理および調査のポリシーとプロセスを導入し、インシデントに備える。

## 12.
- Amazon S3 Intelligent Tiering: 予測不能なアクセスパターンをもつデータを保存するのに最適なS3ストレージクラス。

## 13.
- AWS Config: AWSリソースの設定を評価、監査、審査できる構成管理のサービス。
- Amazon Inspector: 自動化されたセキュリティ評価サービス。

## 14.
- DynamoDB: 複雑なトランザクション処理が発生する業務システムには利用すべきではない。JOIN/TRANSACTION/COMMIT/ROLLBACKが必要な複雑な処理はできない。

## 15.
- AWSの責任共有モデル
    - AWS: 物理的なインフラストラクチャのパッチ管理、構成管理。
    - ユーザー: AWSサービスの使用内で独自のコントロールを実施。cloudformationを使用したリソースやアプリケーションのプロビジョニング
- プロビジョニング: 必要に応じてネットワークやコンピュータ設備などのリソースを提供できるように予測し、準備しておくこと。

## 16.
- AWS Service Catalog: AWS での使用が承認された IT サービスのカタログを作成および管理してガバナンスを強化するサービス。

## 17.
- Gateway Load Balancer: ファイアウォール、侵入検知と防止システム、分析、可視化などのサードパーティの仮想アプライアンスのフリートを展開および管理する。
- Application Load Balancer: OSIモデルの第7層(http, httpsなどのアプリケーション層)のレイヤーで、一般的なwebアプリケーション向けのロードバランサー。
- Network Load Balancer: OSIモデルの第4層(tcp, udpなどのネットワーク層)のレイヤーで、毎秒数百万のリクエストを処理。

## 20.
- AWS Artifact: AWSアカウントの契約やAWS側のコンプライアンスレポートなどの重要なコンプライアンス関連情報にかかる一元管理型のリソース

## 21.
- AWS Control Tower: AWS Organizationsと連携して複数アカウントに対してランディングゾーン（事前設定された安全な環境）の設定を自動化するサービス。
- AWS Managed Microsoft Active Directory (AD) :  AWS リソースがAWS 内のマネージド型ADを使用することを可能にする。

## 24.
- AWS Storage Gateway: オンプレミス環境から、AWS上への実質無制限のクラウドストレージへのアクセスを提供するハイブリッドクラウドストレージサービス。

## 26.
- DynamoDB Streams: Dynamo tableに保存された項目の追加・変更・削除の発生時の履歴をキャプチャできる機能。

## 27.
- 垂直スケーリング: サーバー自体のパフォーマンスを向上させることで処理性能をスケールさせること。
- 水平スケーリング: 処理するサーバー台数を増やすこと。

## 29.
- AWS Budgets
    - 予算を設定に対してコストまたは使用量が予算額や予算量を超えた際などにアラートを通知
    - リザーブドインスタンス (RI) または Savings Plans の集計使用率とカバレッジメトリクスをモニタリング

## 30.
- AWS Cloud HSM
    - クラウドベースのハードウェアセキュリティモジュール (HSM)。
    - AWSクラウドで暗号化キーを簡単に生成して使用できる
    - CloudHSMは暗号化キーのコンプライアンス対応として利用するもの

## 31.
- AWS Audit Manager: AWSリソースの使用状況を継続的に監査して、リスクとコンプライアンスの評価を自動化するサービス。

## 32.
- Amazon QLDB(Quantum Ledger Database)
    - フルマネージドな台帳データベース。
    - データの変更履歴はイミュータブルに保持され、履歴が正当であることを暗号的に検証できる。
    - クレジットやデビットの取引など、すべての金融取引の完全で正確なレコードを作成することができる。

## 33.
- Well Architected Framework
    - Reliability: 期待通りの機能を実行するワークロードと、要求に応えられなかった場合に迅速に回復すること。
    - Performance Efficiency:IT およびコンピューティングリソースの構造化および合理化された割り当て。
    - Security:データの機密性と整合性、ユーザー許可の管理、セキュリティイベントを検出するための制御。
    - Cost Optimization:不要なコストの回避。
    - Operational Excellence:システムの実行とモニタリング、およびプロセスと手順の継続的な改善。
    - Sustainability:実行中のクラウドワークロードによる環境への影響を最小限に抑えること。

## 35.
- エンタープライズプラン: コンシェルジュサポートあり。
- TAM(Technical Account Manager): AWS 環境の健全な運用をプロアクティブに維持する指定技術的責任者。

## 36.
- AWSを利用したデータ転送
    - インターネットから全てのAWSリージョンへのインバウンドデータ転送は無料。
    - 同じリージョン内のその他のサービス間でのデータ転送は無料。
    - アウトバウンドデータ転送は有料。

## 40.
- AWS Trust & Safetyチーム: AWS リソースが不正処理に使用されている場合に連絡する。

## 41.
- AWSコンサルティングパートナー: AWSパートナーネットワーク内でAWSのユーザーが意向を実施する際のコンサルティングまたはマネージドサービスを提供するプロフェッショナル資格。
- AWSプロフェッショナルサービス: AWSクラウドを使用して期待するビジネス上の成果を実現するようにユーザーをサポートする専門家からなるグローバルチーム。

## 42.
- サポートプラン
    - ベーシック: Trusted Advisorはベーシックチェックのみ。技術サポートは問い合わせのみ。
    - Developer: Trusted Advisorはベーシックチェックのみ。メール対応。
    - ビジネス: Trusted Advisorはフルチェック。電話/チャット/メール問い合わせ。
    - エンタープライズ on Ramp: Trusted Advisorはフルチェック。ガイダンス提供、well-architected対応支援
    - エンタープライズ: Trusted Advisorはフルチェック。TAMが環境を事前に監視して支援、well-architected対応支援

## 44.
- アプリケーションのクライアントサイドのパフォーマンス監視
    - Amazon CloudWatch RUM: デバイス間でアプリケーションのパフォーマンスをほぼリアルタイムで確認して、アプリケーションのクライアントサイドのパフォーマンスを監視
    - Amazon CloudWatch ServiceLens: アプリケーションの正常性、パフォーマンス、可用性を 1 か所で視覚化および分析できるようにする機能
    - Amazon Cloudwatch synthetics: RESTAPI、URL、ウェブサイトコンテンツを、毎分、24時間年中無休で監視し、アプリケーションエンドポイントが想定通りに動作しなかった場合にアラートを出す。

## 47.
- AWS Compute Optimizer: 機械学習を利用してEC2、Auto Scalingグループ、EBSおよびLambda関数の最適化することができるサービス。
- Amazon SageMaker: MLモデルを迅速に構築、トレーニング、デプロイできるようにする完全マネージド型サービス。

## 49.
- CloudFrontのコスト: データ転送アウトとユーザーからのリクエストとトラフィック分散に基づく。
    - リクエスト: リクエストが行われた地域と数。
    - データ転送アウト: エッジロケーションから転送されたデータ量。

## 50.
- AWS Cloud WAN
    - クラウド環境とオンプレミス環境のリソース間でWANを構築し、管理することができるWANサービス。
    - 複数の拠点やネットワークにまたがるグローバルネットワークを構築することができる。
- WAN: Wide Area Network。Internetのこと。
- VPC Peering: VPC間を接続するサービス。

## 53.
- Amazon Connect: クラウドベースのコンタクトセンターソリューションを構築することができるサービス。

## 57.
- Amazon AppStream2.0: フルマネージドで非永続的なデスクトップおよびアプリケーションサービスであり、リモートで業務にアクセスすることができる。

## 58.
- AWSリソースグループ
    - リソースの管理やタスクの自動化をするための管理サービス
    - 各フェーズに応じたカスタムコンソールを作成するには、各フェーズや領域のすべてのリソースをグループとして管理する

## 59.
- Amazon DynamoDB Accelerator(DAX)
    - フルマネージド型高可用性インメモリキャッシュで、DynamoDB用に特化。
    - 1秒あたりのリクエスト数が数百万件になる場合でも、milli secondからmicro secondへと最大 10 倍のパフォーマンス向上を実現

## 61.
- AWS Local Zone: レイテンシーの影響を受けやすいアプリケーションをエンドユーザーにより近い場所で実行することができる特別なゾーン。
- WaveLengthゾーン: 5G ネットワークを利用したアプリケーションを構築する際に利用。

## 63.
- Amazon Keyspaces: キーと値や表形式を含む大量の構造化データを保存、取得、管理することができる。Apache Cassandra互換のデータベースサービス。

## 64.
- AWS Shield: マネージド型の分散サービス妨害 (DDoS) に対する保護サービス。

## 65.
- AWS X-Ray: アプリケーションやその基盤となるサービスの実行状況を把握し、パフォーマンスの問題やエラーの根本原因を特定して、トラブルシューティングを行える。
# AWS　core service 4

■責任共有モデル

ユーザー側の責任
- IAMによるアカウント管理/パスワードルールの設定
- セキュリティグループの設定など適切なネットワーク設定やトラフィック保護
- 構築したアプリケーションのセキュリティ対応
- ネットワーク/インスタンスオペレーションシステム(バッチ)などの設定
- OSやミドルウェアの脆弱性対応
- 通信トラフィックの暗号化/保有しているデータの暗号化

責任共有モデルの統制範囲
- 継承される統制・・・ユーザー側が完全に継承する統制。物理統制(インフラなどの物理的な統制)と環境統制(network構成やtraffic制御などの環境設定)。
- 共有統制
    - パッチ管理・・・AWSがインフラの不具合に対するパッチ適用、ユーザーはゲストOSおよびアプリのパッチ適用責任。
    - 構成管理・・・AWSがインフラデバイスの構成を管理、ユーザーは独自のゲストOS、db、アプリの構成に責任。
    - 意識とトレーニング・・・AWSがAWS従業員のトレーニングを実施、ユーザーは自社は自社でトレーニングを実施。
- ユーザー固有の統制・・・AWSサービスにデプロイするアプリに基づいて、ユーザーがすべての責任を負う統制。

■IAM

IAM(AWS Identity and Access Management)・・・安全にAWS操作を実施するための認証・認可の仕組み。  
IAMポリシー・・・ユーザーなどへのアクセス権限を付与するための設定ドキュメント。  
IAMユーザー・・・IAMポリシー内でAWSサービスを利用できるユーザー。基本操作はIAMユーザーで実施する。  
IAMグループ・・・グループとして権限をまとめて設定された単位のこと。  

・アカウントの種類
- ルートアカウント・・・AWSアカウント作成時に作られるIDアカウント。すべてのAWSサービスとリソースを使用できる権限を有する。日常的なタスクは使用しないことを推奨。
- 管理者権限・・・管理者権限の許可が付与されたIAMユーザー。
- パワーユーザー・・・IAM以外のすべてのAWSサービスにフルアクセス権限を有するIAMユーザー。

・IAM権限のベストプラクティス
- AWSアカウントのルートユーザーへのアクセスキーをロックして通常はルートアカウントを使用しない。
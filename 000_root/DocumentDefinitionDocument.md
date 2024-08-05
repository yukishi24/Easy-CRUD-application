# ドキュメント定義書

## 目次
- <strong>[ドキュメント概要](#ドキュメント概要)</strong></br>
- <strong>[ドキュメント一覧/定義](#ドキュメント一覧/定義)</strong></br>
- <strong>[改版履歴](#改版履歴)</strong></br>


## ドキュメント概要
- [要件定義書](RequirementsStatement.md)で、定義したチーム別に作成していくドキュメントを一覧表示し記述内容等を定義していく。
<br><br><br>


## ドキュメント一覧/定義
|No|種別|工程|ドキュメント名(和名)|ドキュメント名(英名)|記述内容|
|:---:|:---|:---|:---|:---|:---|
|1|root|プロジェクト定義|DocumentDefinitionDocument.md|ドキュメント定義書|作成するドキュメントの一覧/定義|
|2|root|プロジェクト定義|RequirementsStatement.md|要件定義書|開発するWebアプリケーションの要件を定義する。|
|3|root|プロジェクト定義|WBS.md|WBS|WBS|
|4|api|要件定義|RequirementsStatement.md|要件定義書|Apiで実装する要件を定義する。|
|5|api|要件定義|WBS.md|WBS|WBS|
|6|api|基本設計|FunctionalDesignDocument.md|機能設計書|Apiで実装する機能の設計書|
|7|api|基本設計|InterfaceDesignDocument.md|インターフェース設計書|Apiで使用するデータインターフェースの設計書|
|8|api|基本設計|ListOfFunctions.md|機能一覧|Apiで実装するApi一覧表|
|9|api|詳細設計|ControllerDesignDocument.md|コントローラー設計書|Apiのコントローラ設計書|
|10|api|詳細設計|DetailedFunctionalDesignSpecification.md|詳細機能設計仕様書|実装するApi詳細設計書|
|11|api|詳細設計|EntityDesignDocument.md|エンティティ設計書|実装するApiエンティティ設計書|
|12|api|詳細設計|QueryDesignDocument.md|クエリ設計書|Apiで実祖するクエリの設計書|
|13|api|詳細設計|ServiceDesignSpecifications.md|サービス仕様設計書|Apiで実祖するサービス設計書|
|14|api|単位テスト|IntegrationTestSpecificationDocument.md|単位テスト仕様書|実装したApiの単位テスト仕様書|
|15|api|結合テスト|SystemTestSpecificationDocument.md|結合テスト仕様書|実装したApiの結合テスト仕様書|
|16|api|システムテスト|UnitTestSpecificationDocument.md|システムテスト仕様書|実装したApiのシステムテスト仕様書|
|17|client|要件定義|RequirementsStatement.md|要件定義書|実装する画面の要件を定義する。|
|18|client|要件定義|WBS.md|WBS|WBS|
|19|client|基本設計|ScreenDesignDocument.md|画面設計図|画面の設計図|
|20|client|基本設計|ScreenTransitionDiagram.md|画面遷移図|画面遷移を表した図|
|21|client|詳細設計|ComponentControlDesignDocument.md|コンポーネント制御設計書|画面に搭載するコンポーネント一覧バリテーション実装する機能との紐付け|
|22|client|詳細設計|InterfaceDesignDocument.md|インターフェイス設計書|画面とApitのやり取りで使用するインターフェース設計書|
|23|client|詳細設計|FormDesignSpecifications.md|帳票設計書|出力する帳票の設計書|
|24|client|単体テスト|UnitTestSpecificationDocument.md|単体テスト仕様書|実装した画面の単位テスト仕様書|
|25|client|結合テスト|IntegrationTestSpecificationDocument.md|統合テスト仕様書|実装した画面の結合テスト仕様書|
|26|client|システムテスト|SystemTestSpecificationDocument.md|システムテスト仕様書|実装した画面のシステムテスト仕様書|
|27|infra|要件定義|RequirementsStatement.md|要件定義書|構築する環境の要件を定義する。|
|28|infra|基本設計|DataDesignSpecifications.md|データ仕様設計|システムで使用するデータの設計書|
|29|infra|基本設計|ListOfInstallationPackages.md|インストール・パッケージ一覧|各サーバにインストールするパッケージの一覧表|
|30|infra|基本設計|ServerPerformanceDesignDocument.md|サーバー性能設計書|構築する各サーバの性能を設計する|
|31|infra|詳細設計|DBDesignDocument.md|DBD設計書|DBD設計書|
|32|infra|詳細設計|ERDiagram.md|ER図|ER図|
|33|infra|詳細設計|TableDesignDocument.md|テーブル設計書|テーブル設計書|

## 改版履歴
|Ver|修正者|日付|
|:---|:---|:---|
|1.00|2024/08/05|yukishi24|
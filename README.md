# DORA Capabilities 成熟度評価プロジェクト

## プロジェクト概要

このプロジェクトは、DORA（DevOps Research and Assessment）が定義する組織能力（Capabilities）に対して、成熟度モデルを適用し、組織のソフトウェアデリバリーとオペレーションのパフォーマンスを評価・改善するためのフレームワークです。

## DORAとは

DORAは、Google Cloudが運営する長期研究プログラムで、ソフトウェアデリバリーとオペレーションのパフォーマンスを向上させる能力を特定し、理解することを目的としています。DORAの研究は、以下の4つの主要メトリクス（Four Keys）で知られています：

- **デプロイ頻度（Deployment Frequency）**: 本番環境へのデプロイ頻度
- **変更のリードタイム（Lead Time for Changes）**: コミットから本番環境へのデプロイまでの時間
- **変更失敗率（Change Failure Rate）**: デプロイが失敗または修正が必要となる割合
- **サービス復旧時間（Time to Restore Service）**: インシデント発生から復旧までの時間

## 対象ケイパビリティ

本プロジェクトでは、以下の27のケイパビリティをカバーしています：

### 学習のための風土（Climate for Learning）
- コード保守性（Code Maintainability）
- ドキュメント品質（Documentation Quality）
- ツール選択の権限委譲（Empowering Teams to Choose Tools）
- 創造的組織文化（Generative Organizational Culture）
- 職務満足度（Job Satisfaction）
- 学習文化（Learning Culture）
- チーム実験（Team Experimentation）
- 変革的リーダーシップ（Transformational Leadership）
- ウェルビーイング（Well-being）

### 高速フロー（Fast Flow）
- 継続的デリバリー（Continuous Delivery）
- データベース変更管理（Database Change Management）
- デプロイ自動化（Deployment Automation）
- 柔軟なインフラストラクチャ（Flexible Infrastructure）
- 疎結合チーム（Loosely Coupled Teams）
- 変更承認の合理化（Streamlining Change Approval）
- トランクベース開発（Trunk-based Development）
- バージョン管理（Version Control）
- 視覚的管理（Visual Management）

### 高速フィードバック（Fast Feedback）
- 継続的インテグレーション（Continuous Integration）
- 顧客フィードバック（Customer Feedback）
- モニタリングと可観測性（Monitoring and Observability）
- ビジネス意思決定のためのモニタリング（Monitoring Systems to Inform Business Decisions）
- 浸透的セキュリティ（Pervasive Security）
- プロアクティブ障害通知（Proactive Failure Notification）
- テスト自動化（Test Automation）
- テストデータ管理（Test Data Management）
- バリューストリームにおける作業の可視性（Visibility of Work in the Value Stream）

## 成熟度モデル

各ケイパビリティに対して、以下の5段階の成熟度レベルを定義します：

### レベル1: 初期段階（Initial）
- **特徴**: アドホックで予測不可能なプロセス
- **状態**: プラクティスが文書化されておらず、個人の知識に依存
- **成果**: 不安定で予測困難

### レベル2: 管理段階（Managed）
- **特徴**: プロジェクトレベルでの基本的な管理
- **状態**: 一部のプラクティスが定義され、実行されている
- **成果**: プロジェクトレベルでの再現性

### レベル3: 定義段階（Defined）
- **特徴**: 組織標準として確立されたプロセス
- **状態**: プラクティスが組織全体で文書化され、標準化されている
- **成果**: 組織レベルでの一貫性

### レベル4: 定量管理段階（Quantitatively Managed）
- **特徴**: 測定とデータに基づく管理
- **状態**: プロセスが測定され、定量的に理解されている
- **成果**: プロセスの予測可能性が高い

### レベル5: 最適化段階（Optimizing）
- **特徴**: 継続的な改善と革新
- **状態**: プロセスが継続的に改善され、革新が促進されている
- **成果**: 業界をリードするパフォーマンス

## 評価方法

各ケイパビリティの成熟度を評価するには：

1. **現状分析**: 現在の組織の状態を各ケイパビリティの視点から評価
2. **レベル判定**: 上記の成熟度レベルに照らし合わせて現在のレベルを特定
3. **ギャップ分析**: 目標レベルと現在レベルの差を特定
4. **改善計画**: 次のレベルに到達するための具体的なアクションを計画
5. **実行と測定**: 改善施策を実行し、定期的に再評価

## プロジェクト構造

```
dora-capabilities/
├── README.md                    # このファイル
├── CLAUDE.md                    # Claude用の指示ファイル
├── capabilities/                # DORAケイパビリティのHTMLファイル
│   ├── DORA _ Capabilities_ Continuous Integration.html
│   ├── DORA _ Capabilities_ Continuous Delivery.html
│   └── ...（全27ファイル）
└── maturity-models/            # 各ケイパビリティの成熟度モデル定義（予定）
    └── ...
```

## 使用方法

1. 評価したいケイパビリティを選択
2. 対応するHTMLファイルで詳細な説明を確認
3. 成熟度モデルに基づいて現状を評価
4. 改善計画を策定し実行

## 参考リンク

- [DORA公式サイト](https://dora.dev)
- [DORA Quick Check](https://dora.dev/quickcheck/)
- [State of DevOps Report](https://dora.dev/publications/)
- [Google Cloud DevOps](https://cloud.google.com/devops)

## ライセンス

DORAのコンテンツは、Google LLCによって[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)の下でライセンスされています。

---

*このプロジェクトは、組織のDevOpsの成熟度を体系的に評価し、継続的な改善を促進するためのツールです。*

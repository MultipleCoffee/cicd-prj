# cicd-prj

このリポジトリは、CI/CDまわりの計画・進行管理用。  
個人プロジェクト全体のタスク整理や検証ログもここにまとめていく。

## ✅ このリポジトリの目的

- Jenkinsを使ったCI/CDパイプラインの検証・構築
- Webアプリ（Go）との連携確認
- 複数リポジトリにまたがる作業をここでまとめて管理する

## 📚 関連リポジトリ

| リポジトリ | 用途 |
|------------|------|
| [test-go-webapp-repo](https://github.com/MultipleCoffee/cicd-practice) | パイプライン動作確認用のGoアプリ |
| [pipeline-scripts-repo](https://github.com/MultipleCoffee/jenkins-pipeline-scripts) | JenkinsfileなどCI/CD用スクリプト群 |

### 🔍 リポジトリごとの役割とIssue管理方針

| リポジトリ名 | 役割 | Issue管理方針 |
|-------------|------|----------------|
| `test-go-webapp-repo` | アプリの実装・テスト | 技術的なIssueやPR単位のタスク管理 |
| `jenkins-pipeline-scripts` | Jenkinsfileなどのスクリプト管理 | パイプラインの構築・修正タスク |
| `cicd-prj`（このリポジトリ） | 計画・設計・進捗全体の管理 | 上位タスク・プロジェクトテーマ・横断的なタスクの整理 |

## 🗂 主な使い方

- **Issue**: 作業タスクや検討メモをチケット化
- **Projects**: カンバンやWBSで進捗管理
- **ドキュメント**: 設計方針や検証ログをまとめる場所（必要があれば）

## 🔧 メモ

- ここはコード置き場ではない。コードは↑の各リポジトリに書く。
- プロジェクト計画のハブとして使う。

---

> ※完全に自分用。必要に応じて自由に更新・拡張していく。

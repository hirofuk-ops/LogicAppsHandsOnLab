# 前提条件

## 必要な Azure リソース
- Azure サブスクリプション
- リソースグループ: （例: `rg-logicapp-demo`）
- Storage Account: （例: `stlogicappdemo`）
- Application Insights: （例: `appi-logicapp-demo`）
- Logic Apps Standard: （例: `logicapp-http-to-blob`）
- Log Analytics ワークスペース（Application Insights 用）

## RBAC 権限
- Logic Apps 作成: **Contributor** または **Logic App Contributor**
- Storage Account へのアクセス: **Storage Blob Data Contributor**
- Application Insights 作成: **Contributor**
- 監視データ閲覧: **Monitoring Reader**
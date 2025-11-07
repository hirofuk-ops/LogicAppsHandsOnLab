# 前提条件
- Azure サブスクリプションが有効であること
- Azure Portal にアクセス可能であること
- 既存の Logic Apps Standard ワークフローが HTTP トリガーで公開済みであること
- API Management インスタンスを新規作成するために、以下の権限が必要:
  - **Contributor** または **Owner** ロールが対象のリソースグループに付与されていること
  - または、API Management リソース作成に必要なカスタム RBAC 権限（`Microsoft.ApiManagement/service/write`）を持っていること

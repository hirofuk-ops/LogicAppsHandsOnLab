# API Management に Logic Apps API を追加する手順
このセクションでは、API Management に Logic Apps Standard の HTTP トリガーを API として追加する手順を説明します。

1. 作成した API Management インスタンスを開く

2. 「API」 → 「+ API の追加」 → 「HTTP」を選択

3. 設定
- **表示名**: LogicAppAPI
- **名前**: logicapp-api
- **Web サービス URL**: Logic Apps の HTTP トリガー URL
- **API URL サフィックス**: ceh

4. 「作成」をクリック

# 操作の追加
- 「操作の追加」を選択し、以下を設定:
  - **名前**: InvokeWorkflow
  - **表示名**: Invoke Workflow
  - **URL**: /
  - **メソッド**: POST
  - **バックエンド URL**: Logic Apps の HTTP トリガー URL
- 「保存」をクリック
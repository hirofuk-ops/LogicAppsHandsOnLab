# Step 2. Logic Apps Standard の HTTP トリガー URL を取得する方法
このセクションでは、Logic Apps Standard の HTTP トリガー URL を取得する手順を説明します。

1. Azure Portal で既存の Logic Apps Standard を開く

2. ワークフロー一覧から対象ワークフローを選択

3. トリガー (HTTP) を開き、HTTP POST URL をコピー
    - URL 例:
    ```
    https://prod-00.japaneast.logic.azure.com:443/workflows/{workflow-id}/triggers/manual/paths/invoke?api-version=2016-10-01&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig={signature}
    ```
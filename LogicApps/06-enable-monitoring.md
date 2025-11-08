# Step 5: Application Insights による監視設定 (オプション)
このステップでは、Logic App Standard のワークフローで Application Insights を有効化し、監視データを収集および分析する方法を説明します。

1. ロジック アプリ の **「監視」** → **「Application Insights」** を確認
2. 有効化済みであれば、トレースや依存関係が自動的に送信される
3. **Application Insights** で確認:
   - 「ライブメトリック」: 実行状況をリアルタイムで確認
   <img src="images/ai-live-metrics.png" alt="ライブメトリック" style="display:block; border: 3px solid black; border-radius: 10px; width: 500px;">
   - 「トランザクションの検索」: HTTP リクエストや Blob 書き込みのログを確認
   <img src="images/ai-transactions.png" alt="トランザクションの検索" style="display:block; border: 3px solid black; border-radius: 10px; width: 500px;">
   - 「失敗した要求」: エラーの詳細を確認
   <img src="images/ai-failures.png" alt="失敗した要求" style="display:block; border: 3px solid black; border-radius: 10px; width: 500px;">

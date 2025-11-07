# Step 6: 作成したリソースのクリーンアップ

ハンズオンで作成したリソースを削除して、不要な課金を防ぎます。

---

## 1. リソースグループの削除
最も簡単な方法は、リソースグループごと削除することです。

1. Azure Portal にログイン。
2. **「リソースグループ」** → `rg-logicapp-demo` を選択。
3. **「削除」** をクリック。
4. 確認のため、リソースグループ名 `rg-logicapp-demo` を入力。
5. **「削除」** を実行。

---

## 2. 個別に削除する場合
以下のリソースを順に削除します。

- Logic App Standard: `logicapp-http-to-blob`
- Storage Account: `stlogicappdemo`
- Application Insights: `appi-logicapp-demo`

---

## 3. PowerShell で削除する場合
```powershell
# Azure にログイン
Connect-AzAccount

# リソースグループを削除
Remove-AzResourceGroup -Name "rg-logicapp-demo" -Force
``
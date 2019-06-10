Folder's golden rule
------------
-	Store secrets
-	File containing password are ignored by any git pushing


Secret file
------------
-	Content sample of a json secret file used by the script "Create-AzContainer.ps1".
```
{
    "arm_tenant_id":"xxxxx", ("appOwnerTenantId": "",)
    "arm_subscription_id":"xxxxx",(Azure Subscription ID)
    "arm_client_id":"xxxxx",  ("appId": "",)
    "arm_client_secret":"xxxxx"
}
```

# How to deployment the application

1. Authentication in Azure
```sh
$ az login --tenat [TENANT_ID or SUBSCRIPTION_ID]
```
2. Deploy the application with a zip resource
```sh
$ az webapp deployment source config-zip --resource-group ManagedPlatform --src api.zip --name az204-imgstor-api
```
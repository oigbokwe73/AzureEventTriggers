# Azure Event Triggers


## Appplication Setting 

|Key|Value | Comment|
|:----|:----|:----|
|AzureWebJobsStorage|[CONNECTION STRING]|RECOMMENDATION :  store in AzureKey Vault.|
|ConfigurationPath| [CONFIGURATION FOLDER PATH] |Folder is optional
|ApiKeyName|[API KEY NAME]|Will be passed in the header  :  the file name of the config.
|AppName| [APPLICATION NAME]| This is the name of the Function App. Used in log analytics|
|StorageAcctName|[STORAGE ACCOUNT NAME]|Example  "AzureWebJobsStorage"|


> **Note:**  Look at the configuration file in the **Config** Folder and created a Table to record information.

## Function App  Configuration 

> **Note:** The **Configuration** is located in the  FunctionApp  in a **Config** Folder.

|FileName|Description|
|:----|:----|
|43EFE991E8614CFB9EDECF1B0FDED37A.json| **Upload File and create batches **|
|43EFE991E8614CFB9EDECF1B0FDED37B.json| **Upload Files and Store in Azure  Table**|
|43EFE991E8614CFB9EDECF1B0FDED37C.json| **Process the batched files and store in Azure Table**|
|43EFE991E8614CFB9EDECF1B0FDED37D.json| **Search** NoSQL DB for ingested records|
|43EFE991E8614CFB9EDECF1B0FDED37E.json| **Copy Files from FileShare to Pickup Blob Container**|

## Upload Configuration to Storage
Go to created storage Account.. Click On "Blob Service" 
![image](https://user-images.githubusercontent.com/15838780/147958072-4a6058d2-d320-44a0-9d11-58449d527cd3.png)

Click on **"Container"**
![image](https://user-images.githubusercontent.com/15838780/147958201-71df0f21-e4e8-46c0-93be-728f1dbc2a43.png)
![image](https://user-images.githubusercontent.com/15838780/147963170-1a2f2a64-7ba2-44ce-9f5d-30d490529711.png)


  ## Products

|products|links|Comments|
|:----|:----|:----|
|Azure Getting Started |https://azure.microsoft.com/en-us/free/| Create free account + $200 in Credit|
|Sample Data Sets|https://www.kaggle.com/datasets| Useful site for pulling sample payload|
|Azure Storage Explorer|https://azure.microsoft.com/en-us/features/storage-explorer/#features|useful view and query data in azure table storage|
|Postman|https://www.postman.com/downloads/|Postman supports the Web or Desktop Version|
|VsCode| https://visualstudio.microsoft.com/downloads/ |  Required extensions. Azure Functions, Azure Account
|VS Studio Community Edition |https://visualstudio.microsoft.com/downloads/| Recommended. Nice intergration with Azure. software is free.

  
  
  ## Contact
  
For questions related to this project, can be reached via email :- support@xenhey.com

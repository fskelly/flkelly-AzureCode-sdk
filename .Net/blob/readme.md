# About

Based on https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet

<br>

## Additional Notes
1. For base folder
```powershell
dotnet.exe new console -n "Blob Basics - v12 SDK"
cd "Blob Basics - v12 SDK"
```

2. For Data Folder
```powershell
mkdir data
```

3. For dependencies
```powershell
dotnet add package Azure.Storage.Blobs
```

4. Please remember to **"restart"** VSCode or **"reopen"** command line windows after using **setx** or **export**

### Changes

Made some changes with regards to Container names and the like
1. Prompt for container prefix
1. Added "-" to Downloaded file name
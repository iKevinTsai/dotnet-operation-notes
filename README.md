# dotnet-operation-notes
```Bash
#新增解決方案
dotnet new sln --name 解決方案名稱
#專案.csproj加入解決方案
dotnet sln 解決方案名稱.sln add .\專案\專案.csproj
#建立gitignore
dotnet new gitignore
#檔案監看員(偵測到變更會reload)
dotnet watch --project ./專案
#清除專案(obj & bin)
dotnet clean
```


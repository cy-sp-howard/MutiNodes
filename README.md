### powershell變更環境變數(僅當下)
```ps1
$Env:Path = $Env:Path.replace("C:\Program Files\nodejs\","C:\Users\howard.ye\Desktop\node\node12\")
```

### powershell變更環境變數(修改使用者變數)
```ps1
setx PATH "C:\Users\howard.ye\AppData\Local\Microsoft\WindowsApps;C:\Users\howard.ye\AppData\Local\Programs\Microsoft VS Code\bin;C:\Users\howard.ye\AppData\Local\GitHubDesktop\bin;C:\Users\howard.ye\AppData\Local\Programs\Git\cmd;C:\Users\howard.ye\Desktop\node"
```

### cmd變更環境變數(僅當下)
```cmd
$Env:Path = $Env:Path.replace("C:\Program Files\nodejs\","C:\Users\howard.ye\Desktop\node\node12\")
```

### cmd使用所有參數(%1,%2...)
```cmd
%*
```

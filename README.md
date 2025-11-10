### powershell change env path (current session)
```ps1
$Env:Path = $Env:Path.replace("C:\Program Files\nodejs\","C:\Users\howard.ye\Desktop\node\node12\")
```
### cmd change user env path (current session)
```ps1
set PATH "C:\Users\howard.ye\AppData\Local\Microsoft\WindowsApps;C:\Users\howard.ye\AppData\Local\Programs\Microsoft VS Code\bin;C:\Users\howard.ye\AppData\Local\GitHubDesktop\bin;C:\Users\howard.ye\AppData\Local\Programs\Git\cmd;C:\Users\howard.ye\Desktop\node"
``` 
### cmd change user env path (permanent)
```ps1
setx PATH "C:\Users\howard.ye\AppData\Local\Microsoft\WindowsApps;C:\Users\howard.ye\AppData\Local\Programs\Microsoft VS Code\bin;C:\Users\howard.ye\AppData\Local\GitHubDesktop\bin;C:\Users\howard.ye\AppData\Local\Programs\Git\cmd;C:\Users\howard.ye\Desktop\node"
```

### cmd use all arguments (%1,%2...)
```cmd
%*
```

### linux set executable
```sh
chmod +x n14.sh
```

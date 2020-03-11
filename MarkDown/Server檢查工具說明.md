# Server檢查工具說明

## 快速使用

> 1. 使用powershell找到腳本所在目錄
> 2. 在該目錄下使用命令 `./checkserver.ps1 ap` ，如此便可以查ap主機  
>    共有三種命令格式：  
>                  `./checkserver.ps1 ap`   ap主機檢查  
>                  `./checkserver.ps1 db`   db主機檢查  
>                  `./checkserver.ps1 all`  db和ap主機在一起的檢查  
> 3. 如果執行命令出現錯誤：***未經數位簽署，您無法在當前系統上執行該腳本，請參考about_Execution_Policies ...*** ;  
> 這是因為系統默認不支持運行未簽名的腳本，請使用命令： `set-executionpolicy Bypass`  ，運行後選擇 `Y`即可執行未簽名腳本.  
> 如果用完後想恢復的話可以再執行一遍該命令，選擇默認的 `N`  

***

## Log記錄的說明

> * Log的位置默認是當前目錄下，新建CheckLog文件夾後，在裡面記錄子文件  
>* CheckResult.txt記錄的是完整的判斷結果  
>* SystemInfo.txt裡面記錄的是詳細的系統信息（可不看）
>* Log格式如下:
>
> >1. CheckServer  檢查內容標題  
> >Server的咨詢
> >-----------------------------------(內容與結果的分隔線)
> >{CheckServer Reuslt}:{Pass} 檢查的結果
> >=========================================(檢查項目的分隔線)
> >2. CheckXXX .....

***

## 代碼判斷標準（可不看）

> * Server的判斷標準  
>
> >Server的OS Name含有Server，並且Version大於6.2  
> >Disk得分出 C和D，並且如果ap或者db單獨的主機，D盤總大小需>=350G，ap和db在一起的則 D盤總大小>=700G
>
> * SqlServer判斷標準
>
> > Sqlserver實例版本>=2016
>
> * NetFrameWork判斷標準
>
> >NetFreameWork的版本>=4.5, 如果有Release文件，則是4.5版本以上  
>  
> * IIS的判斷標準  
>  
> > IIS的版本>=8.0
>  
> * PowerShell的判斷標準
>
> >PowerShell的版本>=5.0  
>
> * 客戶是否能連平台判斷標準  
>
> >使用tnc 平台IP -Port XXX來判斷

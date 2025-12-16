# Windows


## Sudden shutdown cheks

#### Last shutdowns, why and whos:

```
Get-WinEvent -FilterHashtable @{LogName='System'; ID=1074} | Format-List TimeCreated, Message
```

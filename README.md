<div align="center">

## Easy Web Site File Download


</div>

### Description

Download any file off the internet. With this 2 line code snippet. This can download HTML File all the way to zip files. Easy And Quick
 
### More Info
 
Easy to use, just one declaration and one call function


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Joe Healey](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joe-healey.md)
**Level**          |Intermediate
**User Rating**    |4.6 (23 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joe-healey-easy-web-site-file-download__1-36211/archive/master.zip)

### API Declarations

```
Declare Function URLDownloadToFile Lib "urlmon" Alias "URLDownloadToFileA" (ByVal pCaller As Long, ByVal szURL As String, ByVal szFileName As String, ByVal dwReserved As Long, ByVal lpfnCB As Long) As Long
```


### Source Code

```
call URLDownloadToFile(0 ,"http://www.download.com/file.zip" ,"C:\downloads\file.zip",0,0)
'Just replace http://www.download.com/file.zip with whatever file you want to DL
'Just Replace C:\downloads\file.zip with where and What File Name you want to save to
```


<div align="center">

## GetDir


</div>

### Description

GetDir will return the current directory for a specified drive.
 
### More Info
 
0=default, 1=a, 2=b, 3=c


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[N/A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Delphi 5, Delphi 4, Pre Delphi 4
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__7-3.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/getdir__7-21/archive/master.zip)





### Source Code

```
procedure TForm1.Button1Click(Sender: TObject);
var S : String;
begin
  GetDir(0, S);
  Label1.Caption := 'The current drive and directory are: ' + S;
end;
```


# ILC-Link
AOT编译器ILC的rsp脚本和连接器link.exe的脚本

可以通过修改ConsoleApp.ilc.rsp和Link.rsp文件里面的版本号进行编译成AOT exe文件。

比如nuget的8.0.1的ilc.exe目录:C:\Users\Administrator\.nuget\packages\runtime.win-x64.microsoft.dotnet.ilcompiler\8.0.1\tools
然后:ilc.exe @ConsoleApp.ilc.rsp 
链接:link.exe rsp

这里需要两个注意，其一rsp文件里面的路径，其二版本号修改。

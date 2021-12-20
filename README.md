in this directory run

`dotnet publish -c Release`

Afterwards you should see the warning 

`resource BlazorTable.xml in BlazorTable, Version=1.17.0.0, Culture=neutral, PublicKeyToken=null(13,6): warning IL2008: Could not resolve type 'System.Threading.WasmRuntime'`

see https://github.com/IvanJosipovic/BlazorTable/issues/375 for details

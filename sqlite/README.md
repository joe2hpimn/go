libsqlite3.dll.a can create by `dlltool -D sqlite3.dll -d sqlite3.def -l libsqlite3.dll.a`

cp `libsqlite.dll.a` to `C:\MinGW64\lib`
cp `sqlite3.c` to `C:\MinGW64\include`
cp `sqlite3.dll` to your app directory 


config `pkg-config` file(sqlite3.pc) if need

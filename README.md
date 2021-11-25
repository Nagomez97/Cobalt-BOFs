# How to compile
```
# Visual Studio
cl.exe /c /GS- beacon.c /Fobeacon.o

# x86 MinGW
i686-w64-mingw32-gcc -c beacon.c -o beacon.o

# x64 MinGW 
x86_64-w64-mingw32-gcc -c beacon.c -o beacon.o
```

# Unhook
BOF to unhook NTDLL.DLL. It reads NTDLL.DLL from disk at runtime and patches the hooked NTDLL.DLL.

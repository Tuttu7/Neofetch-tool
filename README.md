> The neofetch command like utility written in a bash shell. The main purpose of neofetch is to be used in screenshots to display other users what operating system or Linux distro you are using including theme, icons, hardware config and more.

>  Add the repo by executing the below

```
add-apt-repository ppa:dawidd0811/neofetch

Then

apt-get update
apt-get install neofetch
```

```
# neofetch
            .-/+oossssoo+/-.               root@tuttu-Inspiron 
        `:+ssssssssssssssssss+:`           ------------------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 16.04.3 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Inspiron 3542 
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 4.10.0-28-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 27 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 2195 (dpkg), 3 (snap) 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 4.3.48 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1366x768 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: KDE5 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: KWin 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Theme: Ambiance [GTK3] 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Icons: ubuntu-mono-dark [GTK3] 
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Terminal: konsole 
  +sssssssssdmydMMMMMMMMddddyssssssss+     CPU: Intel i5-4210U (4) @ 2.700GHz 
   /ssssssssssshdmNNNNmyNMMMMhssssss/      GPU: Intel Haswell-ULT 
    .ossssssssssssssssssdMMMNysssso.       Memory: 1921MiB / 3854MiB 
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`                                   
            .-/+oossssoo+/-.                                       
```

> To Display cpu core information

```
# neofetch  --cpu_cores on

            .-/+oossssoo+/-.               root@tuttu-Inspiron 
        `:+ssssssssssssssssss+:`           ------------------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 16.04.3 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Inspiron 3542 
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 4.10.0-28-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 46 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 2195 (dpkg), 3 (snap) 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 4.3.48 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1366x768 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: KDE5 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: KWin 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Theme: Ambiance [GTK3] 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Icons: ubuntu-mono-dark [GTK3] 
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Terminal: konsole 
  +sssssssssdmydMMMMMMMMddddyssssssss+     CPU: Intel i5-4210U (4) @ 2.700GHz 
   /ssssssssssshdmNNNNmyNMMMMhssssss/      GPU: Intel Haswell-ULT 
    .ossssssssssssssssssdMMMNysssso.       Memory: 1857MiB / 3854MiB 
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`                                
```

> To Display CPU speed info :
```
# neofetch  --cpu_speed on
            .-/+oossssoo+/-.               root@tuttu-Inspiron 
        `:+ssssssssssssssssss+:`           ------------------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 16.04.3 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Inspiron 3542 
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 4.10.0-28-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 47 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 2195 (dpkg), 3 (snap) 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 4.3.48 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1366x768 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: KDE5 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: KWin 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Theme: Ambiance [GTK3] 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Icons: ubuntu-mono-dark [GTK3] 
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Terminal: konsole 
  +sssssssssdmydMMMMMMMMddddyssssssss+     CPU: Intel i5-4210U (4) @ 2.700GHz 
   /ssssssssssshdmNNNNmyNMMMMhssssss/      GPU: Intel Haswell-ULT 
    .ossssssssssssssssssdMMMNysssso.       Memory: 1850MiB / 3854MiB 
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`                                   
            .-/+oossssoo+/-.                                     
```

> To Display cpu temprature 

```
# neofetch  --cpu_temp
            .-/+oossssoo+/-.               root@tuttu-Inspiron 
        `:+ssssssssssssssssss+:`           ------------------- 
      -+ssssssssssssssssssyyssss+-         OS: Ubuntu 16.04.3 LTS x86_64 
    .ossssssssssssssssssdMMMNysssso.       Host: Inspiron 3542 
   /ssssssssssshdmmNNmmyNMMMMhssssss/      Kernel: 4.10.0-28-generic 
  +ssssssssshmydMMMMMMMNddddyssssssss+     Uptime: 1 hour, 47 mins 
 /sssssssshNMMMyhhyyyyhmNMMMNhssssssss/    Packages: 2195 (dpkg), 3 (snap) 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Shell: bash 4.3.48 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Resolution: 1366x768 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   DE: KDE5 
ossyNMMMNyMMhsssssssssssssshmmmhssssssso   WM: KWin 
+sssshhhyNMMNyssssssssssssyNMMMysssssss+   Theme: Ambiance [GTK3] 
.ssssssssdMMMNhsssssssssshNMMMdssssssss.   Icons: ubuntu-mono-dark [GTK3] 
 /sssssssshNMMMyhhyyyyhdNMMMNhssssssss/    Terminal: konsole 
  +sssssssssdmydMMMMMMMMddddyssssssss+     CPU: Intel i5-4210U (4) @ 2.700GHz [54.0°C] 
   /ssssssssssshdmNNNNmyNMMMMhssssss/      GPU: Intel Haswell-ULT 
    .ossssssssssssssssssdMMMNysssso.       Memory: 1852MiB / 3854MiB 
      -+sssssssssssssssssyyyssss+-
        `:+ssssssssssssssssss+:`                                   
            .-/+oossssoo+/-.                      
```






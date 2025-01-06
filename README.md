# Modem-extras-apk
Compiled packages for modems (apk version).

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/Modem-extras-apk?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/Modem-extras-apk?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/Modem-extras-apk?style=flat-square)

<!--
### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> To install packages from my github:
- Execute following commands on your OpenWrt router:
  ```
  wget https://github.com/4IceG/Modem-extras/raw/main/Modem-extras-apk/*.apk -O /tmp/*.apk
  apk add --allow-untrusted /tmp/*.apk
  ```
-->

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> To install packages from my repository:
- Execute following commands on your OpenWrt router:
  ```
  echo 'https://github.com/4IceG/Modem-extras-apk/raw/refs/heads/main/myapk/packages.adb' >> /etc/apk/repositories.d/customfeeds.list
  wget https://github.com/4IceG/Modem-extras-apk/raw/refs/heads/main/myapk/IceG-apkpub.pem -O /etc/apk/keys/IceG-apkpub.pem
  apk update

  # If you want to install a package
  apk add luci-app-3ginfo-lite
  ```


### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Aby móc instalować pakiety z mojego repozytorium należy: 
#### Metoda 1. 
- Wykonaj te polecenia na routerze z OpenWrt:
  ```
  echo 'https://github.com/4IceG/Modem-extras-apk/raw/refs/heads/main/myapk/packages.adb' >> /etc/apk/repositories.d/customfeeds.list
  wget https://github.com/4IceG/Modem-extras-apk/raw/refs/heads/main/myapk/IceG-apkpub.pem -O /etc/apk/keys/IceG-apkpub.pem
  apk update

  # Chcąc zainstalować pakiet
  apk add luci-app-3ginfo-lite
  ```

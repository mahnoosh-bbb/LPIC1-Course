in Debian:
```console
    cat /etc/apt/sources.list
```

- for download packages :
```console
    apt update
```

- list for upgradable package :
```console
    apt list --upgradable
```

- install upgrade package :
```console
    apt upgrade
```

- install package with `yes` commands
```console
    apt install [PackageName][mariadb-server] -y
```

- install one more packages with `yes` commands:
```console
    apt install [PackageNames]mariadb-server aria2 nload curl -y
```

or
```console
    pt -y install [PackageNames]mariadb-server aria2 nload curl
```

- Delete Package:
```console
    apt remove [PackageName][aria2]
```

- Delete Dependecies Package:
```console
    apt autoremove
```

- Delete Purge package with configuration
```console
    apt purge [packageName][aria2]
```

- Delete Downloaded Debian filePackage
```console
    apt clean
```

- Search for Package Install
```console
    apt-cache search [PackageName]nload
```

- Details for Package Installed
```console
    apt-cache show [PackageName]curl
```

- Dependensies for Package 
```console
    apt-cache depends [PackageName]curl
```

- updates packages and their dependencies, installing new packages or removing old ones as needed.---> برزورسانی بسته‌ها و وابستگی‌ها، نصب و یا حذف بسته جدید و قدیمی
```console
    apt dist-upgrade
```

- updates packages for Available packages without installing new packages or removing old ones. ---> فقط بسته‌های موجود رو به‌روزرسانی می‌کنه
```console
    apt upgrade
```

- upgrade Ubuntu to new version (In Ubuntu)
```console
    do-release-upgrade
```

in Ubuntu:

`cat /etc/apt/sources.list.d/ubuntu.sources`

in Debian:

`cat /etc/apt/sources.list`

- for download packages :

(https://pkgs.org)

- list for installed package
```console
    :dpkg -l
```
#### with `wget [address]` we can download the package
#### with `dpkg -i [name for package]` install the package 

- Where are the packages we have installed copied to:
```console
    dpkg -L [packageName][aria2]
```

- When we have a path and want to search to see which package it belongs to, we use the following command:
```console
    dpkg -S [Address][/usr/share/locale/nn/LC_MESSAGES]
```

- content for package:
```console
    dpkg -c [Name for Downloded Package]
```

- Delete Package:
```console
    dpkg -r [PackageName][aria2]
```

- Delete Purge package with configuration
```console
    dpkg -P [packageName][aria2]
```

- Status Package
```console
    dpkg -s [packageName]
```
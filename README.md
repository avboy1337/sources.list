# sources.list
The ubuntu sources list collection.

## Ubuntu 23.04
```txt
# deb cdrom:[Xubuntu 23.04 _Lunar Lobster_ - Alpha amd64 (20230115)]/ lunar main multiverse restricted universe
 
# See http://help.ubuntu.com/community/UpgradeNotes for how to upgrade to
# newer versions of the distribution.
deb http://cn.archive.ubuntu.com/ubuntu/ lunar main restricted
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar main restricted
 
## Major bug fix updates produced after the final release of the
## distribution.
deb http://cn.archive.ubuntu.com/ubuntu/ lunar-updates main restricted
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar-updates main restricted
 
## N.B. software from this repository is ENTIRELY UNSUPPORTED by the Ubuntu
## team. Also, please note that software in universe WILL NOT receive any
## review or updates from the Ubuntu security team.
deb http://cn.archive.ubuntu.com/ubuntu/ lunar universe
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar universe
deb http://cn.archive.ubuntu.com/ubuntu/ lunar-updates universe
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar-updates universe
 
## N.B. software from this repository is ENTIRELY UNSUPPORTED by the Ubuntu 
## team, and may not be under a free licence. Please satisfy yourself as to 
## your rights to use the software. Also, please note that software in 
## multiverse WILL NOT receive any review or updates from the Ubuntu
## security team.
deb http://cn.archive.ubuntu.com/ubuntu/ lunar multiverse
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar multiverse
deb http://cn.archive.ubuntu.com/ubuntu/ lunar-updates multiverse
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar-updates multiverse
 
## N.B. software from this repository may not have been tested as
## extensively as that contained in the main release, although it includes
## newer versions of some applications which may provide useful features.
## Also, please note that software in backports WILL NOT receive any review
## or updates from the Ubuntu security team.
deb http://cn.archive.ubuntu.com/ubuntu/ lunar-backports main restricted universe multiverse
# deb-src http://cn.archive.ubuntu.com/ubuntu/ lunar-backports main restricted universe multiverse
 
deb http://security.ubuntu.com/ubuntu lunar-security main restricted
# deb-src http://security.ubuntu.com/ubuntu lunar-security main restricted
deb http://security.ubuntu.com/ubuntu lunar-security universe
# deb-src http://security.ubuntu.com/ubuntu lunar-security universe
deb http://security.ubuntu.com/ubuntu lunar-security multiverse
# deb-src http://security.ubuntu.com/ubuntu lunar-security multiverse
 
# This system was installed using small removable media
# (e.g. netinst, live or single CD). The matching "deb cdrom"
# entries were disabled at the end of the installation process.
# For information about how to configure apt package sources,
# see the sources.list(5) manual.
```


## Ubuntu 22.04

```txt
deb http://archive.ubuntu.com/ubuntu/ jammy main restricted universe multiverse
# deb-src http://archive.ubuntu.com/ubuntu/ jammy main restricted universe multiverse

deb http://archive.ubuntu.com/ubuntu/ jammy-updates main restricted universe multiverse
# deb-src http://archive.ubuntu.com/ubuntu/ jammy-updates main restricted universe multiverse

deb http://archive.ubuntu.com/ubuntu/ jammy-security main restricted universe multiverse
# deb-src http://archive.ubuntu.com/ubuntu/ jammy-security main restricted universe multiverse

deb http://archive.ubuntu.com/ubuntu/ jammy-backports main restricted universe multiverse
# deb-src http://archive.ubuntu.com/ubuntu/ jammy-backports main restricted universe multiverse

deb http://archive.canonical.com/ubuntu/ jammy partner
# deb-src http://archive.canonical.com/ubuntu/ jammy partner
```

## Ubuntu 21.10
```txt
deb http://old-releases.ubuntu.com/ubuntu/ impish main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ impish main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu/ impish-security main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ impish-security main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu/ impish-updates main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ impish-updates main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu/ impish-proposed main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ impish-proposed main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu/ impish-backports main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ impish-backports main restricted universe multiverse
```

## Ubuntu 21.04
```txt
deb http://old-releases.ubuntu.com/ubuntu/ hirsute main restricted universe multiverse
deb http://old-releases.ubuntu.com/ubuntu/ hirsute-security main restricted universe multiverse
deb http://old-releases.ubuntu.com/ubuntu/ hirsute-updates main restricted universe multiverse
deb http://old-releases.ubuntu.com/ubuntu/ hirsute-proposed main restricted universe multiverse
deb http://old-releases.ubuntu.com/ubuntu/ hirsute-backports main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ hirsute main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ hirsute-security main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ hirsute-updates main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ hirsute-proposed main restricted universe multiverse
deb-src http://old-releases.ubuntu.com/ubuntu/ hirsute-backports main restricted universe multiverse
```

## Ubuntu 20.04
```sh
sudo apt-get install vim
sudo vim /etc/apt/sources.list
```

```txt
deb https://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse

deb https://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse

deb https://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse

deb https://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse

deb https://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
```

## Update cache & upgrade source list
```sh
sudo apt-get update
sudo apt-get upgrade
```

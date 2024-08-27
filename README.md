# Debian / Ubuntu

## Find out architecture
* ``` dpkg --print-architecture ```
* ``` uname -a ```

## Find out distribution

*  ``` cat /etc/issue ```
*  ``` lsb_release -a ```



## Find out why a package is there

```
apt-cache rdepends --installed $package
```

## Cleanup Packages

* apt --fix-broken install
* apt-get -f install
* dpkg --force-all --configure -a
* dpkg --purge --force-depends  xxxxxxxxxx
*

## Cronjob/Crontab

Execute a script as if it is called from crontab:   
```/usr/bin/env --ignore-environment  <your-command>```

## bash

Find the Script-Path (see also [stack overflow](https://stackoverflow.com/questions/59895/how-do-i-get-the-directory-where-a-bash-script-is-located-from-within-the-script)  :

```SCRIPT_DIR=$( cd -- "$( dirname -- "${BASH_SOURCE[0]}" )" &> /dev/null && pwd )```


# Media

## Movies / Videos
* renaming videos properly with year etc : ```mnamer```   

# Android
## Old Menu

* get back old menu on old Apps with adb : ```adb shell input keyevent 82```


# eBooks 
 
* great ebook-reader on Linux : foliate , much better than e.g. fbreader

# Markdown

* great markdown-editor on Linux : apostrophe

# Docker

## List Containers

### The running ones

```docker ps```

### All

```docker ps --all```

## List images


## Delete Container

```docker rm <container-id>```

## Delete Image 

```docker image rm <image-id>```


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

# Media

## Movies / Videos
* renaming properly with year etc : ```mnamer```   

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


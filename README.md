# ethos-termux-repo
This is a repo for pkg of termux holding all the prebuilt deb files for ethos and its components for easy installation. Termux is supported from  v0.5.0 beta in ethos-lang and forge.

How to setup repo?
Run
```
echo "deb [trusted=yes] https://amancode22.github.io/ethos-termux-repo/repo termux extras" >> $PREFIX/etc/apt/sources.list.d/ethos-local.list
pkg update
pkg install ethos-lang-termux ethos-forge-termux
```

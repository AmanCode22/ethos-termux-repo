# ethos-termux-repo
This is a repo for pkg of termux holding all the prebuilt deb files for ethos and its components for easy installation. Termux is supported from  v0.5.0 beta in ethos-lang and forge.

How to setup repo?
Run
```
mkdir -p $PREFIX/etc/apt/sources.list.d/
echo "deb [trusted=yes] https://amancode22.github.io/ethos-termux-repo/repo termux extras" >> $PREFIX/etc/apt/sources.list.d/ethos-repo.list
pkg update
pkg install ethos-lang ethos-forge
```

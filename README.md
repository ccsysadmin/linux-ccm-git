# linux-cc-git
Mainline Kernel for Arch Linux based on repository sources

## building
```
makepkg
```

### tips
edit ```/etc/makepkg.conf``` and uncomment ```MAKEFLAGS="-j#"``` to use multithread compiling, change ```#``` according to number of CPU cores.
for example, 4 cores cpu ```4+1```. then change ```#``` to ```5```.

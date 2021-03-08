# debmakeinstall

Runs `make install` in the current directory within a namespaced chroot jail and builds a *.deb package from the installation. 

Tested On: Linux Mint 19.3 (Ubuntu Bionic 18.04)

Requires Packages: build-essential fakeroot

For a quick test:
```sh
cd demo/hello
make
../../debmakeinstall --root=. --prefix=/usr/local
```

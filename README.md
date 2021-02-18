# gfortran for macOS

The goal of this repository is to host GNU Fortran packages for macOS. These are simple installers, that will install the GCC compilers (including gfortran) in `/usr/local/gfortran`.

**[Follow this link to download!](https://github.com/fxcoudert/gfortran-for-macOS/releases)**

----

### How to uninstall?

```
sudo rm -rf /usr/local/gfortran /usr/local/bin/gfortran
sudo pkgutil --forget com.gnu.gfortran
```

----

*If you are interested in how these installers are built, the documentation is [here](build_package.md).*

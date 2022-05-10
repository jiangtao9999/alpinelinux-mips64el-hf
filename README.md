# AlpineLinux port for MIPS64EL and HardFloat

### New pkgs:

- additional/libcroco:

- additional/librsvg:

  Non-Rust version of librsvg.

- additional/openssl1.1-compat:

  Some pkg depend on this name.

- openssl1.1-compat/polkit:

  replace mozjs to duktape. Patch from gentoo-musl.

### Gcc configure:

_arch_configure="--with-arch=mips3 --with-tune=mips64 --with-mips-plt --with-float=hard --with-abi=64";;

### Binary pkg Download:

https://pan.baidu.com/s/1c1xs7I5xKN46I2tqsHunoQ?pwd=uhds

sha512sum:

692870615b9150bf0183c7841cc75f4b045b82edf0cd019280c2f86d481f3e3a3ad216982e397a57924e3f1dc23de0bc6b56c84618a28d060f327530e838387a  alpinelinux-3.15.0-mips64el-sha5122sum.txt


### Next is origin readme.

Alpine Linux aports repository
==============================

This repository contains the APKBUILD files for each and every
Alpine Linux package, along with the required patches and scripts,
if any.

It also contains some extra files and directories related to testing
(and therefore, building) those packages on GitLab (via GitLab CI).

If you want to contribute, please read the
[contributor guide](https://wiki.alpinelinux.org/wiki/Alpine_Linux:Contribute)
and feel free to either submit a git patch on the Alpine aports
mailing list (~alpine/aports@lists.alpinelinux.org), or to submit a
merge request on [GitLab](https://gitlab.alpinelinux.org/alpine/aports).


Git Hooks
---------

You can find some useful git hooks in the `.githooks` directory.
To use them, run the following command after cloning this repository:

```sh
git config --local core.hooksPath .githooks
```

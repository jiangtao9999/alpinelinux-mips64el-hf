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

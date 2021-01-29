# NetBSD patch

patch - A program to apply diffs to original files

This is a straight port of the `patch` command from NetBSD to Linux. It depends on [libbsd](https://libbsd.freedesktop.org/), and a libc with `asprintf(3)`.

## Build and Install

Meson and ninja are required to build.

```bash
meson build
ninja -C build
```

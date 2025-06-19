# Linux prebuilds

This is a project that provides Linux kernel builds from GitHub Actions (using `make defconfig`). Check the releases page for the modules and `bzImage`.

## Decompressing `modules.cpio.gz`

```bash
gzip -ckd modules.cpio.gz | cpio -id
```

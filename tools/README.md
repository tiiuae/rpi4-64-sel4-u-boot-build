
## NOTE! So that others can avoid wasting their time on checking the Linaro GCC archives. 

As you may assume on first glance that the `*.asc` files would
contain GPG signatures distributed by Linaro with their GCC
toolchains, then congratulations, you have mistaken!

Because for reasons only known to God himself, the `*.asc`
do not contain GPG signatures nor any GPG data at all, but
**MD5 checksums!**

So, the correct way to check for their authenticity is to use
`md5sum`. I have verified them and included SHA-256 checksums
of the files also. Why does someone even use MD5 these days?


### Toolchains

 - `aarch64-elf*` Bare-metal 64-bit ARMv8 Cortex-A little-endian.
 - `aarch64-linux-gnu*` Linux-targeted 64-bit ARMv8 Cortex-A little-endian.

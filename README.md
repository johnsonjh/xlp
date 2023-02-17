# IBM XL PASCAL/6000 V2.1.4 for AIX

This is IBM XL PASCAL/6000 V2.1.4 for AIX.

IBM XL PASCAL is no longer supported (or even available) from IBM, but still works on current AIX 7.3 systems.

Since licenses for this product are no longer available, the following command may be used to patch the compiler to bypass the license manager:

```sh
/usr/bin/echo -ne '\x60\x00\x00\x00' | /usr/bin/dd of=/usr/lpp/xlp/lib/xlpentry bs=1 count=4 seek=2703800 conv=notrunc
```

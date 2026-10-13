## sptm.t8112.release.im4p

> `Firmware/sptm.t8112.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

-820.40.23.0.0
+820.40.24.0.0
   __TEXT.__cstring: 0x15230
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7b00
   __LATE_CONST.__late_const: 0x8c840
-  __TEXT_EXEC.__text: 0x5b8ec
+  __TEXT_EXEC.__text: 0x5bb80
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf
Functions:
~ sub_fffffff0270d480c : 996 -> 1648
~ sub_fffffff0270d91bc -> sub_fffffff0270d9448 : 248 -> 256
~ sub_fffffff02710f8a8 -> sub_fffffff02710fb3c : 72 -> 68
CStrings:
+ "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
- "SPTM-820.40.23|2026-09-27:20:05:06.102161|"
```

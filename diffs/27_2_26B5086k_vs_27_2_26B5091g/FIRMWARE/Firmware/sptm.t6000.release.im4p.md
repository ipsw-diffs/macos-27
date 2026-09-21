## sptm.t6000.release.im4p

> `Firmware/sptm.t6000.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x16975
+820.40.20.0.1
+  __TEXT.__cstring: 0x1699f
   __TEXT.__const: 0xa84
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x8300
-  __LATE_CONST.__late_const: 0x7c9c0
-  __TEXT_EXEC.__text: 0x64814
+  __DATA_CONST.__const: 0x8308
+  __LATE_CONST.__late_const: 0x8c9c0
+  __TEXT_EXEC.__text: 0x647e8
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 423
   Symbols:   1
-  CStrings:  2629
+  CStrings:  2630
 
Functions:
~ sub_fffffff0270f6330 -> sub_fffffff027106330 : 1092 -> 1068
~ sub_fffffff027105960 -> sub_fffffff027115948 : 1296 -> 1276
~ sub_fffffff02710c7d0 -> sub_fffffff02711c7a4 : 80 -> 76
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

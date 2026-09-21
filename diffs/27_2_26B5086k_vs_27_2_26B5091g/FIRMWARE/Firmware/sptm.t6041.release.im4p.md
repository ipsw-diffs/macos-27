## sptm.t6041.release.im4p

> `Firmware/sptm.t6041.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x158cc
+820.40.20.0.1
+  __TEXT.__cstring: 0x158f6
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x7bf8
-  __LATE_CONST.__late_const: 0x7c9b0
-  __TEXT_EXEC.__text: 0x5f0a4
+  __DATA_CONST.__const: 0x7c00
+  __LATE_CONST.__late_const: 0x8c9b0
+  __TEXT_EXEC.__text: 0x5f078
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 399
   Symbols:   1
-  CStrings:  2536
+  CStrings:  2537
 
Functions:
~ sub_fffffff0270ebc64 -> sub_fffffff0270fbc64 : 1104 -> 1080
~ sub_fffffff0270fbf9c -> sub_fffffff02710bf84 : 1300 -> 1280
~ sub_fffffff027103060 -> sub_fffffff027113034 : 80 -> 76
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

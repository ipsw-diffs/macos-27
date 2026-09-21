## sptm.t8122.release.im4p

> `Firmware/sptm.t8122.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x14f96
+820.40.20.0.1
+  __TEXT.__cstring: 0x14fc0
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x7b60
-  __LATE_CONST.__late_const: 0x7c840
-  __TEXT_EXEC.__text: 0x5c018
+  __DATA_CONST.__const: 0x7b68
+  __LATE_CONST.__late_const: 0x8c840
+  __TEXT_EXEC.__text: 0x5bfec
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 389
   Symbols:   1
-  CStrings:  2461
+  CStrings:  2462
 
Functions:
~ sub_fffffff0270e9a14 -> sub_fffffff0270f9a14 : 1092 -> 1068
~ sub_fffffff0270f9038 -> sub_fffffff027109020 : 1296 -> 1276
~ sub_fffffff0270fffd4 -> sub_fffffff02710ffa8 : 76 -> 72
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

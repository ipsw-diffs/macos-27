## sptm.t6031.release.im4p

> `Firmware/sptm.t6031.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x14f97
+820.40.20.0.1
+  __TEXT.__cstring: 0x14fc1
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x7b60
-  __LATE_CONST.__late_const: 0x7cb40
-  __TEXT_EXEC.__text: 0x5be94
+  __DATA_CONST.__const: 0x7b68
+  __LATE_CONST.__late_const: 0x8cb40
+  __TEXT_EXEC.__text: 0x5be68
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 389
   Symbols:   1
-  CStrings:  2461
+  CStrings:  2462
 
Functions:
~ sub_fffffff0270e9890 -> sub_fffffff0270f9890 : 1092 -> 1068
~ sub_fffffff0270f8eb4 -> sub_fffffff027108e9c : 1296 -> 1276
~ sub_fffffff0270ffe50 -> sub_fffffff02710fe24 : 80 -> 76
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

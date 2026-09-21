## sptm.t6050.release.im4p

> `Firmware/sptm.t6050.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x15e01
+820.40.20.0.1
+  __TEXT.__cstring: 0x15e2b
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x7bf8
-  __LATE_CONST.__late_const: 0x7cc40
-  __TEXT_EXEC.__text: 0x60664
+  __DATA_CONST.__const: 0x7c00
+  __LATE_CONST.__late_const: 0x8cc50
+  __TEXT_EXEC.__text: 0x60638
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 406
   Symbols:   1
-  CStrings:  2568
+  CStrings:  2569
 
Functions:
~ sub_fffffff0270ec3bc -> sub_fffffff0270fc3bc : 1088 -> 1064
~ sub_fffffff0270fca5c -> sub_fffffff02710ca44 : 1292 -> 1272
~ sub_fffffff027104620 -> sub_fffffff0271145f4 : 80 -> 76
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

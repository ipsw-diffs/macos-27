## sptm.t8103.release.im4p

> `Firmware/sptm.t8103.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA_CONST.__const`
- `__DATA.__auth_ptr`

```diff

-820.40.18.0.0
-  __TEXT.__cstring: 0x12f82
+820.40.20.0.1
+  __TEXT.__cstring: 0x12f86
   __TEXT.__const: 0xa2c
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7498
-  __LATE_CONST.__late_const: 0x7c840
-  __TEXT_EXEC.__text: 0x55ce0
+  __LATE_CONST.__late_const: 0x8c840
+  __TEXT_EXEC.__text: 0x55cb4
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf
Functions:
~ sub_fffffff0270d9080 -> sub_fffffff0270e9080 : 1092 -> 1068
~ sub_fffffff0270f2e2c -> sub_fffffff027102e14 : 1296 -> 1276
~ sub_fffffff0270f9c9c -> sub_fffffff027109c70 : 68 -> 80
CStrings:
+ "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
- "SPTM-820.40.18|2026-09-04:20:00:32.449636|"
```

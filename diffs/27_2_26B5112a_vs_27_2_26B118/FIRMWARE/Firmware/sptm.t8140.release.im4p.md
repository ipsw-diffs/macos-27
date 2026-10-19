## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x15bab
+  __TEXT.__cstring: 0x15c63
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7c00
   __LATE_CONST.__late_const: 0x8c870
-  __TEXT_EXEC.__text: 0x5ff64
+  __TEXT_EXEC.__text: 0x602d0
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 401
   Symbols:   1
-  CStrings:  2550
+  CStrings:  2553
 
Functions:
~ sub_fffffff0270e2da0 : 6544 -> 6968
~ sub_fffffff0270e4cac -> sub_fffffff0270e4e54 : 2920 -> 3356
~ sub_fffffff0270e9908 -> sub_fffffff0270e9c64 : 3764 -> 3772
~ sub_fffffff0270ea7bc -> sub_fffffff0270eab20 : 13504 -> 13512
~ sub_fffffff027113f20 -> sub_fffffff02711428c : 80 -> 68
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```

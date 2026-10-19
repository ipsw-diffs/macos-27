## sptm.t6000.release.im4p

> `Firmware/sptm.t6000.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`
- `__DATA.__auth_ptr`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x16c5c
+  __TEXT.__cstring: 0x16d14
   __TEXT.__const: 0xa84
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x8308
   __LATE_CONST.__late_const: 0x8c9c0
-  __TEXT_EXEC.__text: 0x6569c
+  __TEXT_EXEC.__text: 0x65a68
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 425
   Symbols:   1
-  CStrings:  2644
+  CStrings:  2647
 
Functions:
~ sub_fffffff0270ce14c -> sub_fffffff0270d214c : 2336 -> 2412
~ sub_fffffff0270ced08 -> sub_fffffff0270d2d54 : 3604 -> 3628
~ sub_fffffff0270cfb1c -> sub_fffffff0270d3b80 : 2148 -> 2188
~ sub_fffffff0270ee868 -> sub_fffffff0270f28f4 : 5644 -> 6016
~ sub_fffffff0270f0160 -> sub_fffffff0270f4360 : 2724 -> 3168
~ sub_fffffff0270f4a4c -> sub_fffffff0270f8e08 : 3764 -> 3772
~ sub_fffffff0270f5900 -> sub_fffffff0270f9cc4 : 13504 -> 13512
~ sub_fffffff02711d658 -> sub_fffffff027121a24 : 72 -> 76
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-07:22:22:16.682501|"
```

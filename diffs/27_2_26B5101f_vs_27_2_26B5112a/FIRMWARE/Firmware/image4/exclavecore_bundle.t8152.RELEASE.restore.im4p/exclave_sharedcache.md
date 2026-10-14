## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8152.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`

```diff

-1777.40.34.0.0
-  __TEXT.__text: 0x543a78
+1777.40.37.0.0
+  __TEXT.__text: 0x543ee4
   __TEXT.__lcxx_override: 0xd0
-  __TEXT.__cstring: 0x498a1
+  __TEXT.__cstring: 0x499a1
   __TEXT.__const: 0x1176d4
   __TEXT.__swift5_typeref: 0x10940
-  __TEXT.__swift5_reflstr: 0xd548
+  __TEXT.__swift5_reflstr: 0xd568
   __TEXT.__swift5_assocty: 0x7388
-  __TEXT.__swift5_fieldmd: 0x158d4
-  __TEXT.__constg_swiftt: 0x210a0
+  __TEXT.__swift5_fieldmd: 0x158ec
+  __TEXT.__constg_swiftt: 0x21100
   __TEXT.__swift5_protos: 0x774
   __TEXT.__swift5_proto: 0x3274
   __TEXT.__swift5_types: 0x1d48

   __TEXT.__eh_frame: 0x2ecd8
   __DATA.__TIGHTBEAM_VT: 0x6f0
   __DATA.__TIGHTBEAM: 0x1c8
-  __DATA.__const: 0x32d30
-  __DATA.__data: 0x12b18
+  __DATA.__const: 0x32d40
+  __DATA.__data: 0x12b68
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1a84b
   __DATA.__auth_ptr: 0x1a58

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xd8e0
+  __DATA.__bss: 0xd8f0
   __DATA.__common: 0x57a
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810

   __DATA_CONST.__mod_term_func: 0x0
   Functions: 652
   Symbols:   1
-  CStrings:  6670
+  CStrings:  6676
 
Functions:
~ sub_81f9adc : 598564 -> 599612
~ sub_84f80b8 -> sub_84f84d0 : 294876 -> 294960
~ sub_8540094 -> sub_8540500 : 4004 -> 4008
CStrings:
+ "Start not allowed: camera disabled by EDT policy"
+ "Status not allowed: camera disabled by EDT policy"
+ "fpwm-frequency-hz"
+ "policy-sil-disable"
+ "sil-disable-config"
+ "sil-disable-offset"
```

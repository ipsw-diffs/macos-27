## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`

```diff

-1777.40.34.0.0
-  __TEXT.__text: 0x5d8b54
+1777.40.37.0.0
+  __TEXT.__text: 0x5da24c
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x4f7f1
-  __TEXT.__const: 0x120e94
-  __TEXT.__swift5_typeref: 0x132f8
-  __TEXT.__swift5_reflstr: 0x12308
+  __TEXT.__cstring: 0x4f9d1
+  __TEXT.__const: 0x120ed4
+  __TEXT.__swift5_typeref: 0x13308
+  __TEXT.__swift5_reflstr: 0x12348
   __TEXT.__swift5_assocty: 0x7ba8
-  __TEXT.__swift5_fieldmd: 0x1b0e4
-  __TEXT.__constg_swiftt: 0x26230
+  __TEXT.__swift5_fieldmd: 0x1b13c
+  __TEXT.__constg_swiftt: 0x262b4
   __TEXT.__swift5_protos: 0x8c0
   __TEXT.__swift5_proto: 0x3ad8
-  __TEXT.__swift5_types: 0x2284
+  __TEXT.__swift5_types: 0x2288
   __TEXT.__swift5_types2: 0x60
   __TEXT.__swift5_builtin: 0x1590
   __TEXT.__swift5_capture: 0xfec

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xb0
-  __TEXT.__eh_frame: 0x339c4
+  __TEXT.__eh_frame: 0x33a84
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3b9e0
-  __DATA.__data: 0x16d60
+  __DATA.__const: 0x3ba78
+  __DATA.__data: 0x16dc8
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1a84b
-  __DATA.__auth_ptr: 0x2080
+  __DATA.__auth_ptr: 0x2088
   __DATA.__DEVICETREE: 0x18
   __DATA.__shared_cache: 0x380
   __DATA.__MMIOREGS: 0x795

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xe550
-  __DATA.__common: 0x6ba
+  __DATA.__bss: 0xe570
+  __DATA.__common: 0x6da
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22649
+  Functions: 22660
   Symbols:   1
-  CStrings:  7246
+  CStrings:  7257
 
CStrings:
+ "Start not allowed: camera disabled by EDT policy"
+ "Status not allowed: camera disabled by EDT policy"
+ "[StrictMode] .rampUp -> .steady"
+ "[StrictMode] Can't use pre-wake MIB. Reporting failure."
+ "[StrictMode] Disabling (enabledTs="
+ "[StrictMode] Enabling (ts="
+ "[StrictMode] Healthy. Disabling. MIB="
+ "fpwm-frequency-hz"
+ "policy-sil-disable"
+ "sil-disable-config"
+ "sil-disable-offset"
```

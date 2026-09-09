## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8142.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`

```diff

 1777.0.27.0.0
-  __TEXT.__text: 0x5ca87c
+  __TEXT.__text: 0x5cce94
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x4e371
-  __TEXT.__const: 0x11f984
-  __TEXT.__swift5_typeref: 0x1302e
-  __TEXT.__swift5_reflstr: 0x11358
+  __TEXT.__cstring: 0x4e9f1
+  __TEXT.__const: 0x11fb14
+  __TEXT.__swift5_typeref: 0x13162
+  __TEXT.__swift5_reflstr: 0x114a8
   __TEXT.__swift5_assocty: 0x7a10
-  __TEXT.__swift5_fieldmd: 0x1a790
-  __TEXT.__constg_swiftt: 0x25a10
-  __TEXT.__swift5_protos: 0x8ac
-  __TEXT.__swift5_proto: 0x3a14
-  __TEXT.__swift5_types: 0x2220
+  __TEXT.__swift5_fieldmd: 0x1a910
+  __TEXT.__constg_swiftt: 0x25d5c
+  __TEXT.__swift5_protos: 0x8b0
+  __TEXT.__swift5_proto: 0x3a1c
+  __TEXT.__swift5_types: 0x2234
   __TEXT.__swift5_types2: 0x60
-  __TEXT.__swift5_builtin: 0x1590
+  __TEXT.__swift5_builtin: 0x15a4
   __TEXT.__swift5_capture: 0xf9c
   __TEXT.__objc_methtype: 0xe1
-  __TEXT.__swift5_mpenum: 0x3b4
+  __TEXT.__swift5_mpenum: 0x3d4
   __TEXT.__swift_as_entry: 0x998
   __TEXT.__swift_as_ret: 0xb08
   __TEXT.__swift_as_cont: 0x11f8

   __TEXT.__eh_frame: 0x32fa4
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3ac98
-  __DATA.__data: 0x166e0
+  __DATA.__const: 0x3ae60
+  __DATA.__data: 0x16a30
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1a328
-  __DATA.__auth_ptr: 0x2008
+  __DATA.__auth_ptr: 0x2010
   __DATA.__DEVICETREE: 0x18
   __DATA.__shared_cache: 0x380
   __DATA.__DARTS: 0x93f

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22491
+  Functions: 22510
   Symbols:   1
-  CStrings:  7141
+  CStrings:  7177
 
CStrings:
+ "  Device state = "
+ " not allowed while strobe alternative indicator is active"
+ "Alternative Indicator Triggered = "
+ "Display POST Failed = "
+ "Display issue detected: continuing to use health checks until microphone is turned on"
+ "Display issue detected: switching to strobe alternative indicator"
+ "Failed to end strobe"
+ "Failed to end strobe after MOT met"
+ "Failed to notify corerepaird of strobe start"
+ "Failed to prepare strobe"
+ "Failed to prepare strobe before MOT was met"
+ "Failed to update strobe before MOT was met"
+ "Failed to update strobe power state"
+ "Failed to update strobe power state to "
+ "Force TCON Threshold Exceeded = "
+ "INDICATOR: STROBE ALT -> OFF"
+ "INDICATOR: STROBE ALT -> ON"
+ "INDICATOR: STROBE ALT -> PENDING STOP"
+ "INDICATOR: STROBE ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE ALT -> PREPARE"
+ "INDICATOR: STROBE FLASH ALT -> DONE"
+ "INDICATOR: STROBE FLASH ALT -> OFF"
+ "INDICATOR: STROBE FLASH ALT -> ON"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP"
+ "INDICATOR: STROBE FLASH ALT -> PENDING STOP CANCELED"
+ "INDICATOR: STROBE FLASH ALT -> PREPARE"
+ "Invalid start state for strobe flash machine (pending: "
+ "Notified corerepaird of strobe start"
+ "display-post-failed"
+ "display-post-failed-1"
+ "octopus_fang_alt_indicator"
+ "octopus_force_alt_indicator"
+ "octopus_force_display_POST_failed"
+ "octopus_force_tcon_threshold_exceeded"
+ "octopus_no_fang_alt_indicator"
+ "policy-alt-indicator"
```

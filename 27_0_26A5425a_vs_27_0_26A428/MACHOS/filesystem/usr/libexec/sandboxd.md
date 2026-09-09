## sandboxd

> `/usr/libexec/sandboxd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__dof_sandboxd`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 3051.0.52.0.0
-  __TEXT.__text: 0x33ee0
+  __TEXT.__text: 0x3336c
   __TEXT.__auth_stubs: 0x15f0
   __TEXT.__objc_stubs: 0x27a0
   __TEXT.__objc_methlist: 0x10c4
   __TEXT.__const: 0x83b0
-  __TEXT.__cstring: 0x200eb
+  __TEXT.__cstring: 0x20255
   __TEXT.__oslogstring: 0x2512
   __TEXT.__objc_classname: 0x233
   __TEXT.__objc_methname: 0x2b60

   __TEXT.__swift5_types: 0x1c
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__dof_sandboxd: 0x2f5
-  __TEXT.__unwind_info: 0xaa0
+  __TEXT.__unwind_info: 0xde8
   __TEXT.__eh_frame: 0x370
   __DATA_CONST.__const: 0x27f0
   __DATA_CONST.__cfstring: 0x84c0

   __DATA.__objc_selrefs: 0xc10
   __DATA.__objc_ivar: 0x144
   __DATA.__objc_data: 0x7d8
-  __DATA.__data: 0xe3f8
+  __DATA.__data: 0xe488
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xb10
   __DATA.__common: 0x30

   - /usr/lib/swift/libswiftos.dylib
   Functions: 992
   Symbols:   522
-  CStrings:  6026
+  CStrings:  6035
 
CStrings:
+ "CISP_CMD_APPLE_CH_AF_SMART_TAP_FOCUS_TRACKING_CONTROL"
+ "CISP_CMD_APPLE_CH_AF_SMART_TAP_FOCUS_TRACKING_ENABLE"
+ "CISP_CMD_APPLE_CH_MLVNR_TIMEWARP_CONFIG_SET"
+ "CISP_CMD_CH_AE_APERTURE_BEHAVIOR_SET"
+ "CISP_CMD_CH_AE_APERTURE_REQUEST"
+ "CISP_CMD_CH_AE_APERTURE_STEP_LUMA_RATIO_SET"
+ "CISP_CMD_CH_TIMEWARP_FORCE_FPS"
+ "CISP_CMD_CH_TIMEWARP_PARAMS_SET"
+ "CISP_CMD_CH_TIMEWARP_RECORDING_SET"
```

## t602xdcp.im4p

> `Firmware/dcp/t602xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x2fb738
-  __TEXT.__const: 0x3aa2f0
+  __TEXT.__text: 0x2fba28
+  __TEXT.__const: 0x3aa2e0
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x3898f
+  __TEXT.__cstring: 0x38afd
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x37e90
+  __DATA.__const: 0x37f58
   __DATA.__data: 0x118468
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xee0
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xba0
+  __DATA._afk_sys_objt: 0xbb0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x34108
+  __DATA.__zerofill: 0x34110
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x448
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x23881
-  Functions: 7233
+  Functions: 7236
   Symbols:   0
-  CStrings:  8819
+  CStrings:  8832
 
CStrings:
+ "EnableHingeAngleOverride"
+ "FALSE"
+ "HingeAngleOverrideValue"
+ "IOMFBHingeServiceEPIClient"
+ "IOMFBParameter_external_sync set to %s\n"
+ "TRUE"
+ "enableGenLock"
+ "genLockFrequency"
+ "iomfb_RuntimeProperty_enableGenLock"
+ "iomfb_RuntimeProperty_enableHingeAngleOverride"
+ "iomfb_RuntimeProperty_genLockFrequency"
+ "iomfb_RuntimeProperty_hingeAngleOverrideValue"
+ "set_external_sync_gated sync_clock: %d\n"
```

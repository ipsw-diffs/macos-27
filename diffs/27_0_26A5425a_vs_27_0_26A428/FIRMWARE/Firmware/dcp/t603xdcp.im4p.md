## t603xdcp.im4p

> `Firmware/dcp/t603xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x2ec490
-  __TEXT.__const: 0x3ac464
+  __TEXT.__text: 0x2ec794
+  __TEXT.__const: 0x3ac474
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x38763
+  __TEXT.__cstring: 0x388d1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x37f48
+  __DATA.__const: 0x38010
   __DATA.__data: 0x11f558
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xea0
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xbc0
+  __DATA._afk_sys_objt: 0xbd0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x31950
+  __DATA.__zerofill: 0x31958
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x580
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x23f8e
-  Functions: 7224
+  Functions: 7227
   Symbols:   0
-  CStrings:  8860
+  CStrings:  8873
 
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

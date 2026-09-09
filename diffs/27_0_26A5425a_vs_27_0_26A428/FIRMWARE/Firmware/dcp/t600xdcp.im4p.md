## t600xdcp.im4p

> `Firmware/dcp/t600xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x326730
-  __TEXT.__const: 0x3cbd68
+  __TEXT.__text: 0x326a44
+  __TEXT.__const: 0x3cbd58
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x37cf0
+  __TEXT.__cstring: 0x37e5e
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x37d80
+  __DATA.__const: 0x37e48
   __DATA.__data: 0x129688
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xe40
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xba0
+  __DATA._afk_sys_objt: 0xbb0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x33598
+  __DATA.__zerofill: 0x335a0
   __DATA.__afk_obj_num: 0x210
   __DATA.__padding1: 0x1
   __DATA.__padding2: 0x1

   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x227f9
-  Functions: 7310
+  Functions: 7313
   Symbols:   0
-  CStrings:  8655
+  CStrings:  8668
 
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

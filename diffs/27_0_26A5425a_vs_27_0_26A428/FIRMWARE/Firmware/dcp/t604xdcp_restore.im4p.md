## t604xdcp_restore.im4p

> `Firmware/dcp/t604xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x307af4
+  __TEXT.__text: 0x307dfc
   __TEXT.__const: 0x3b3b18
   __TEXT.__chain_starts: 0x34
-  __TEXT.__cstring: 0x39df6
+  __TEXT.__cstring: 0x39f64
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3aeb0
+  __DATA.__const: 0x3af78
   __DATA.__data: 0x11f4c0
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x6a0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xc00
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xbe0
+  __DATA._afk_sys_objt: 0xbf0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x5c620
+  __DATA.__zerofill: 0x5c628
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x5a0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x24180
-  Functions: 7428
+  Functions: 7431
   Symbols:   0
-  CStrings:  9004
+  CStrings:  9017
 
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

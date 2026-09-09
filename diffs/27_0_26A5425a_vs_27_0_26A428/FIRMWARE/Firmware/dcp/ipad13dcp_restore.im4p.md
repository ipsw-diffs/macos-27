## ipad13dcp_restore.im4p

> `Firmware/dcp/ipad13dcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x2e8b6c
-  __TEXT.__const: 0x3ca750
+  __TEXT.__text: 0x2e8e88
+  __TEXT.__const: 0x3ca760
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x37b33
+  __TEXT.__cstring: 0x37ca1
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38080
+  __DATA.__const: 0x38148
   __DATA.__data: 0x135754
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xa40
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xc20
+  __DATA._afk_sys_objt: 0xc30
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x2d820
+  __DATA.__zerofill: 0x2d828
   __DATA.__afk_obj_num: 0x1f0
   __DATA.__padding1: 0x1
   __DATA.__padding2: 0x1

   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x23464
-  Functions: 7251
+  Functions: 7254
   Symbols:   0
-  CStrings:  8693
+  CStrings:  8706
 
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

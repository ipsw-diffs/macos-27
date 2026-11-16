## t604xdcp.im4p

> `Firmware/dcp/t604xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x30d8c0
-  __TEXT.__const: 0x3b3c30
+  __TEXT.__text: 0x30e620
+  __TEXT.__const: 0x3b3c10
   __TEXT.__chain_starts: 0x34
-  __TEXT.__cstring: 0x3a6c0
+  __TEXT.__cstring: 0x3a721
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3b250
+  __DATA.__const: 0x3b368
   __DATA.__data: 0x11f4c0
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x6a0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xc20
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xc10
+  __DATA._afk_sys_objt: 0xc00
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x5d668
+  __DATA.__zerofill: 0x5d678
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x5a0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x2447a
-  Functions: 7454
+  Functions: 7461
   Symbols:   0
-  CStrings:  9064
+  CStrings:  9065
 
CStrings:
+ "DBCL: No KSF factory table loaded, status %d"
+ "DBCL: No KSF handler to read the factory table from"
+ "DBCL: Retrieved KSF factory table with %d entries"
+ "Error in setting up table for DBCl backlight compensation"
+ "KSF factory table has %u rows, exporting the first %u"
- "CBTelemetry"
- "DBCL: KSFCompHandler::apply_brightness_comp called with DBCl data"
- "DBCL: No DBCL data available"
- "DBCL: Successfully retrieved DBCL data with %d entries"
```

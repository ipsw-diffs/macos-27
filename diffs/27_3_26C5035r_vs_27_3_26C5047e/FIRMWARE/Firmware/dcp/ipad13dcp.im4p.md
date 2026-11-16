## ipad13dcp.im4p

> `Firmware/dcp/ipad13dcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`
- `__DATA.__constructor`

```diff

-  __TEXT.__text: 0x2ee5f4
-  __TEXT.__const: 0x3ca760
+  __TEXT.__text: 0x2ef3b8
+  __TEXT.__const: 0x3ca7d0
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x38355
+  __TEXT.__cstring: 0x383b6
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38420
+  __DATA.__const: 0x38530
   __DATA.__data: 0x135754
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xa60
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xc50
+  __DATA._afk_sys_objt: 0xc40
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x2e888
+  __DATA.__zerofill: 0x2e8a8
   __DATA.__afk_obj_num: 0x1f0
   __DATA.__padding1: 0x1
   __DATA.__padding2: 0x1

   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x2375e
-  Functions: 7276
+  Functions: 7283
   Symbols:   0
-  CStrings:  8751
+  CStrings:  8752
 
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

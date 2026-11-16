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

-  __TEXT.__text: 0x2fdc18
-  __TEXT.__const: 0x3aa2c0
+  __TEXT.__text: 0x2fe97c
+  __TEXT.__const: 0x3aa370
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x391b1
+  __TEXT.__cstring: 0x39212
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38230
+  __DATA.__const: 0x38340
   __DATA.__data: 0x118468
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xf00
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xbd0
+  __DATA._afk_sys_objt: 0xbc0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x34170
+  __DATA.__zerofill: 0x34180
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x448
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x23b7b
-  Functions: 7259
+  Functions: 7266
   Symbols:   0
-  CStrings:  8877
+  CStrings:  8878
 
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

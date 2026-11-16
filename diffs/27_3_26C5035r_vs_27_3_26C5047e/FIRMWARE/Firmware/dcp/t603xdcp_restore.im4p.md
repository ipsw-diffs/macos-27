## t603xdcp_restore.im4p

> `Firmware/dcp/t603xdcp_restore.im4p`

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

-  __TEXT.__text: 0x2eb4a0
-  __TEXT.__const: 0x3ac514
+  __TEXT.__text: 0x2ec21c
+  __TEXT.__const: 0x3ac574
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x38f85
+  __TEXT.__cstring: 0x38fe6
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x382e8
+  __DATA.__const: 0x383f8
   __DATA.__data: 0x11f558
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_exc_stack: 0x1000
   __DATA._afk_sys_drv: 0xec0
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xbf0
+  __DATA._afk_sys_objt: 0xbe0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x309c0
+  __DATA.__zerofill: 0x309d0
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x580
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
   __OS_LOG.__string: 0x24288
-  Functions: 7254
+  Functions: 7261
   Symbols:   0
-  CStrings:  8918
+  CStrings:  8919
 
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

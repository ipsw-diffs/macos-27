## ipad14dcp.im4p

> `Firmware/dcp/ipad14dcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x3041c8
-  __TEXT.__const: 0x3cb788
+  __TEXT.__text: 0x3044fc
+  __TEXT.__const: 0x3cb7a0
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x385e1
+  __TEXT.__cstring: 0x3866f
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x381a0
+  __DATA.__const: 0x381b8
   __DATA.__data: 0x14c8d4
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._afk_sys_objt: 0xc60
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x2d108
+  __DATA.__zerofill: 0x2d118
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x6c0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x23694
-  Functions: 7306
+  __OS_LOG.__string: 0x236f2
+  Functions: 7308
   Symbols:   0
-  CStrings:  8781
+  CStrings:  8785
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s TCON state capture on unexpected unplug %s"
+ "%s: startThread failed 0x%x"
+ "TCON state capture on unexpected unplug %s"
+ "mode filtered, no valid TSQ point: frame %u us < PIODMA+ISR reserve %u us + %u%% content window"
+ "update_hdcp_encryption_status"
- "update_hdcp_encryption_status: startThread failed 0x%x"
```

## t602xdcp_restore.im4p

> `Firmware/dcp/t602xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2f7d68
-  __TEXT.__const: 0x3aa320
+  __TEXT.__text: 0x2f8088
+  __TEXT.__const: 0x3aa350
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x38bc3
+  __TEXT.__cstring: 0x38c51
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x37f80
-  __DATA.__data: 0x118468
+  __DATA.__const: 0x37f88
+  __DATA.__data: 0x118470
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0
   __DATA._rtk_boot: 0x9000

   __DATA._afk_sys_objt: 0xbc0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x33118
+  __DATA.__zerofill: 0x33128
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x448
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x23881
-  Functions: 7241
+  __OS_LOG.__string: 0x238df
+  Functions: 7242
   Symbols:   0
-  CStrings:  8836
+  CStrings:  8840
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s TCON state capture on unexpected unplug %s"
+ "%s: startThread failed 0x%x"
+ "TCON state capture on unexpected unplug %s"
+ "mode filtered, no valid TSQ point: frame %u us < PIODMA+ISR reserve %u us + %u%% content window"
+ "update_hdcp_encryption_status"
- "update_hdcp_encryption_status: startThread failed 0x%x"
```

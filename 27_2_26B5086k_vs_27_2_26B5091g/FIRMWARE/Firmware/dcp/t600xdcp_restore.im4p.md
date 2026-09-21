## t600xdcp_restore.im4p

> `Firmware/dcp/t600xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x322dc0
-  __TEXT.__const: 0x3cbd98
+  __TEXT.__text: 0x323104
+  __TEXT.__const: 0x3cbdb8
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x37f24
+  __TEXT.__cstring: 0x37fb2
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x37e70
+  __DATA.__const: 0x37e98
   __DATA.__data: 0x129690
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._afk_sys_objt: 0xbc0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x325b0
+  __DATA.__zerofill: 0x325c0
   __DATA.__afk_obj_num: 0x210
   __DATA.__padding1: 0x1
   __DATA.__padding2: 0x1

   __DATA._rtk_mtab: 0x430
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x227f9
-  Functions: 7318
+  __OS_LOG.__string: 0x22857
+  Functions: 7320
   Symbols:   0
-  CStrings:  8672
+  CStrings:  8676
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s TCON state capture on unexpected unplug %s"
+ "%s: startThread failed 0x%x"
+ "TCON state capture on unexpected unplug %s"
+ "mode filtered, no valid TSQ point: frame %u us < PIODMA+ISR reserve %u us + %u%% content window"
+ "update_hdcp_encryption_status"
- "update_hdcp_encryption_status: startThread failed 0x%x"
```

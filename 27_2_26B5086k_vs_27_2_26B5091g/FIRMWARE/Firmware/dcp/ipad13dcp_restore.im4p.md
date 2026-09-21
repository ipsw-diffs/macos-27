## ipad13dcp_restore.im4p

> `Firmware/dcp/ipad13dcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2e882c
-  __TEXT.__const: 0x3ca798
+  __TEXT.__text: 0x2e8b70
+  __TEXT.__const: 0x3ca7c0
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x37d67
+  __TEXT.__cstring: 0x37df5
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38170
+  __DATA.__const: 0x38188
   __DATA.__data: 0x135764
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._afk_sys_objt: 0xc40
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x2d828
+  __DATA.__zerofill: 0x2d838
   __DATA.__afk_obj_num: 0x1f0
   __DATA.__padding1: 0x1
   __DATA.__padding2: 0x1

   __DATA._rtk_mtab: 0x570
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x23464
-  Functions: 7256
+  __OS_LOG.__string: 0x234c2
+  Functions: 7258
   Symbols:   0
-  CStrings:  8710
+  CStrings:  8714
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s TCON state capture on unexpected unplug %s"
+ "%s: startThread failed 0x%x"
+ "TCON state capture on unexpected unplug %s"
+ "mode filtered, no valid TSQ point: frame %u us < PIODMA+ISR reserve %u us + %u%% content window"
+ "update_hdcp_encryption_status"
- "update_hdcp_encryption_status: startThread failed 0x%x"
```

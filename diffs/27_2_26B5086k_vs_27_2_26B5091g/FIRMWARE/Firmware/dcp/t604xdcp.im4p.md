## t604xdcp.im4p

> `Firmware/dcp/t604xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x30af54
-  __TEXT.__const: 0x3b3bb8
+  __TEXT.__text: 0x30b3d4
+  __TEXT.__const: 0x3b3bf0
   __TEXT.__chain_starts: 0x34
-  __TEXT.__cstring: 0x3a02a
+  __TEXT.__cstring: 0x3a160
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3af88
-  __DATA.__data: 0x11f4c0
+  __DATA.__const: 0x3afa8
+  __DATA.__data: 0x11f4c8
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x6a0
   __DATA._rtk_boot: 0x9000

   __DATA._afk_sys_objt: 0xc00
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x5d628
+  __DATA.__zerofill: 0x5d638
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x5a0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x24180
-  Functions: 7430
+  __OS_LOG.__string: 0x241de
+  Functions: 7434
   Symbols:   0
-  CStrings:  9021
+  CStrings:  9027
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s TCON state capture on unexpected unplug %s"
+ "%s: startThread failed 0x%x"
+ "CommonTwoDTempGrid_v2: programmed default TempGrid with 0x%x (25 degC) on boot/powerOn"
+ "CommonTwoDTempGrid_v2: skipping default TempGrid vals programming, external pipe"
+ "TCON state capture on unexpected unplug %s"
+ "mode filtered, no valid TSQ point: frame %u us < PIODMA+ISR reserve %u us + %u%% content window"
+ "update_hdcp_encryption_status"
- "update_hdcp_encryption_status: startThread failed 0x%x"
```

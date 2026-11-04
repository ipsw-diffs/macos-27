## t603xdcp.im4p

> `Firmware/dcp/t603xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2ed3ec
-  __TEXT.__const: 0x3ac564
+  __TEXT.__text: 0x2ee94c
+  __TEXT.__const: 0x3ac50c
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x38e1c
+  __TEXT.__cstring: 0x38f85
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x381d0
+  __DATA.__const: 0x382e8
   __DATA.__data: 0x11f558
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_mtab: 0x580
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x24164
-  Functions: 7241
+  __OS_LOG.__string: 0x24288
+  Functions: 7251
   Symbols:   0
-  CStrings:  8906
+  CStrings:  8918
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s ALPM disable IRQ not received within %u ms -- IRQ path suspect"
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s ALPM disable not acked within %u ms"
+ " [DCPDPVirtualDevice.cpp::%d] DCPAV[%d] %s::%s Error waiting for dummy virtual service %x\n"
+ "ALPM disable IRQ not received within %u ms -- IRQ path suspect"
+ "ALPM disable not acked within %u ms"
+ "Error waiting for dummy virtual service %x\n"
+ "IOMFB: verify_swap: PBL layers enabled but no SCL block\n"
+ "IOMFBSupportsVerificationOnlyKey"
+ "PBL fence callback error: swapID=%u pblLayer=%u\n"
+ "handleUpdateLinkRate"
+ "iomfb_RuntimeProperty_supportsVerificationOnly"
+ "setUpdated"
```

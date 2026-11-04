## t604xdcp_restore.im4p

> `Firmware/dcp/t604xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x308bcc
-  __TEXT.__const: 0x3b3c18
+  __TEXT.__text: 0x30a158
+  __TEXT.__const: 0x3b3c38
   __TEXT.__chain_starts: 0x34
-  __TEXT.__cstring: 0x3a557
+  __TEXT.__cstring: 0x3a6c0
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3b128
+  __DATA.__const: 0x3b250
   __DATA.__data: 0x11f4c0
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x6a0

   __DATA._rtk_mtab: 0x5a0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x24356
-  Functions: 7447
+  __OS_LOG.__string: 0x2447a
+  Functions: 7457
   Symbols:   0
-  CStrings:  9052
+  CStrings:  9064
 
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

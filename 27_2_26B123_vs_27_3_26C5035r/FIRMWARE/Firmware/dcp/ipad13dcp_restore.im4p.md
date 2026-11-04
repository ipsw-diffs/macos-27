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

-  __TEXT.__text: 0x2e9b20
-  __TEXT.__const: 0x3ca7e8
+  __TEXT.__text: 0x2eb07c
+  __TEXT.__const: 0x3ca768
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x381ec
+  __TEXT.__cstring: 0x38355
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38308
+  __DATA.__const: 0x38420
   __DATA.__data: 0x135754
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x1e8

   __DATA._rtk_mtab: 0x570
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x2363a
-  Functions: 7269
+  __OS_LOG.__string: 0x2375e
+  Functions: 7279
   Symbols:   0
-  CStrings:  8739
+  CStrings:  8751
 
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

## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/Versions/A/WPDaemon`

```diff

-2701.7.1.0.0
-  __TEXT.__text: 0x5cba0
+2702.3.1.0.0
+  __TEXT.__text: 0x5cdb0
   __TEXT.__objc_methlist: 0x43a4
-  __TEXT.__cstring: 0x4816
+  __TEXT.__cstring: 0x489c
   __TEXT.__const: 0x238
-  __TEXT.__oslogstring: 0x9e35
+  __TEXT.__oslogstring: 0x9e86
   __TEXT.__gcc_except_tab: 0x115c
   __TEXT.__unwind_info: 0x25b8
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2830
+  __DATA_CONST.__objc_selrefs: 0x2838
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x2d8
-  __DATA_CONST.__got: 0x488
-  __AUTH_CONST.__const: 0x7730
-  __AUTH_CONST.__cfstring: 0x3860
+  __DATA_CONST.__got: 0x490
+  __AUTH_CONST.__const: 0x7750
+  __AUTH_CONST.__cfstring: 0x38a0
   __AUTH_CONST.__objc_const: 0x8700
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x168

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3403
+  Functions: 3404
   Symbols:   3880
-  CStrings:  1463
+  CStrings:  1467
 
Symbols:
+ GCC_except_table121
+ _NSCocoaErrorDomain
+ _objc_msgSend$failWithError:
- GCC_except_table132
- GCC_except_table152
- GCC_except_table63
Functions:
~ -[WPScanRequest initWithCoder:] : 1056 -> 1312
~ -[WPScanRequest convertUseCaseToString:] : 3648 -> 3700
~ ___50-[WPDZoneManager centralManager:didLoseZone:mask:]_block_invoke.208 : 956 -> 1020
~ ___31-[WPDZoneManager updateScanner]_block_invoke.241 : 104 -> 80
~ -[WPDScanManager addScanRequest:forClient:] : 1552 -> 1544
~ -[WPDAdvertisingManager refreshHeySiriAuthTagInActiveRequests] : 768 -> 1060
+ ___62-[WPDAdvertisingManager refreshHeySiriAuthTagInActiveRequests]_block_invoke.240
~ -[WPDAdvertisingManager refreshHeySiriAuthTagInActiveRequests].cold.4 : 144 -> 36
CStrings:
+ "ProximityServiceThirdPartyHomeSetup"
+ "RPIdentity: skipping refresh, HeySiri adv missing auth tag flag"
+ "RPIdentity: skipping refresh, unexpected HeySiri adv length %lu (expected %lu)"
+ "WPDaemon macOS 27.3 (26C5035p) (WirelessProximity-2702.3.1) (Release) built on 2026-10-30 01:24:59"
+ "WPScanRequest blob value exceeds maximum length"
+ "WPScanRequest mask value exceeds maximum length"
- "RPIdentity: skipping refresh, unexpected HeySiri adv length %lu"
- "WPDaemon macOS 27.2 (26B106) (WirelessProximity-2701.7.1) (Release) built on 2026-10-03 16:48:48"
```

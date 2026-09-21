## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/Versions/A/CascadeEngine`

```diff

-255.0.2.0.0
-  __TEXT.__text: 0x67f88
+256.0.1.0.0
+  __TEXT.__text: 0x67fd0
   __TEXT.__objc_methlist: 0x1f2c
   __TEXT.__const: 0x1280
   __TEXT.__gcc_except_tab: 0x6f4

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1a70
+  __DATA_CONST.__objc_selrefs: 0x1a78
   __DATA_CONST.__objc_protorefs: 0x60
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x50

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2386
-  Symbols:   2885
+  Functions: 2387
+  Symbols:   2887
   CStrings:  834
 
Symbols:
+ GCC_except_table39
+ _CCRapportSyncArmTimeout
+ _objc_msgSend$requestAccessToResource:withMode:useCase:callerConnection:error:
- GCC_except_table38
Functions:
~ ___122-[CCDonationServiceConnection remoteUpdateFromDeviceUUID:options:mergeableDeltas:peerDeviceSite:relayedDeviceSites:reply:]_block_invoke : 396 -> 400
~ -[CCDonationServiceConnection _resolveSetAccessForResourceSpecifier:accessMode:error:] : 972 -> 976
~ -[CCRapportSyncInteraction setTimeoutForRapportRequest:] : 272 -> 252
+ _CCRapportSyncArmTimeout
~ -[CCRapportSyncSession _setNextInteractionTimeout:] : 412 -> 392
```

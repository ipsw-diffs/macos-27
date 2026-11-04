## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/Versions/A/KeychainCircle`

```diff

-62460.40.78.0.0
-  __TEXT.__text: 0x2bbd8
+62460.60.42.501.1
+  __TEXT.__text: 0x2bff4
   __TEXT.__lazy_helpers: 0x1a4
   __TEXT.__objc_methlist: 0x1ebc
   __TEXT.__const: 0x110

   __TEXT.__cstring: 0x38bb
   __TEXT.__oslogstring: 0x3aa9
   __TEXT.__ustring: 0x32
-  __TEXT.__unwind_info: 0xa58
+  __TEXT.__unwind_info: 0xa60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1080
+  __DATA_CONST.__objc_selrefs: 0x1098
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x98
   __DATA_CONST.__got: 0x2c8

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 829
-  Symbols:   2295
+  Symbols:   2298
   CStrings:  814
 
Symbols:
+ -[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:flowID:deviceSessionID:]
+ ___120-[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:flowID:deviceSessionID:]_block_invoke
+ _initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:flowID:deviceSessionID:.onceToken
+ _objc_msgSend$contextID
+ _objc_msgSend$initWithContainerName:contextID:altDSID:flowID:deviceSessionID:
+ _objc_msgSend$initWithContainerName:contextID:altDSID:flowID:deviceSessionID:canSendMetrics:stableTrustedDeviceIDStatus:
+ _objc_msgSend$initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:flowID:deviceSessionID:
+ _objc_msgSend$stableTrustedDeviceIDStatus
- -[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:]
- ___97-[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:]_block_invoke
- _initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:.onceToken
- _objc_msgSend$initWithContainerName:contextID:altDSID:
- _objc_msgSend$initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:
Functions:
~ -[KCJoiningRequestSecretSession setupSession:] : 336 -> 448
~ -[KCAESGCMDuplexSession encodeWithCoder:] : 304 -> 392
~ -[KCAESGCMDuplexSession initWithCoder:] : 352 -> 444
~ -[KCAESGCMDuplexSession initWithSecret:context:as:] : 52 -> 56
~ -[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:] -> -[KCAESGCMDuplexSession initWithSecret:context:as:altDSID:pairingUUID:piggybackingVersion:epoch:flowID:deviceSessionID:] : 572 -> 652
~ -[KCJoiningRequestCircleSession setContextIDForSession:] : 228 -> 340
~ -[KCJoiningRequestCircleSession initWithCircleDelegate:session:altDSID:flowID:deviceSessionID:error:] : 188 -> 268
~ -[KCJoiningRequestCircleSession initWithCircleDelegate:session:otcontrol:altDSID:flowID:deviceSessionID:error:] : 680 -> 764
~ -[KCJoiningAcceptSession initWithSecretDelegate:circleDelegate:dsid:altDSID:flowID:deviceSessionID:rng:error:] : 788 -> 812
~ -[KCJoiningAcceptSession setSessionControlArguments:] : 4 -> 380
```

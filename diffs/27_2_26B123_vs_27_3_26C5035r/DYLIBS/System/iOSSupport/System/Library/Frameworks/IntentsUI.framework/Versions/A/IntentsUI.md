## IntentsUI

> `/System/iOSSupport/System/Library/Frameworks/IntentsUI.framework/Versions/A/IntentsUI`

```diff

-4016.1.16.0.0
-  __TEXT.__text: 0xebb4
-  __TEXT.__objc_methlist: 0x16ac
+4016.2.7.0.0
+  __TEXT.__text: 0xf54c
+  __TEXT.__objc_methlist: 0x16bc
   __TEXT.__const: 0x138
   __TEXT.__dlopen_cstrs: 0x64
-  __TEXT.__gcc_except_tab: 0x1bc
-  __TEXT.__cstring: 0x16aa
-  __TEXT.__oslogstring: 0x9ab
+  __TEXT.__gcc_except_tab: 0x238
+  __TEXT.__cstring: 0x179d
+  __TEXT.__oslogstring: 0xaa1
   __TEXT.__ustring: 0xa
-  __TEXT.__unwind_info: 0x5e0
+  __TEXT.__unwind_info: 0x610
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6a0
+  __DATA_CONST.__const: 0x6f0
   __DATA_CONST.__objc_classlist: 0xb8
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1220
+  __DATA_CONST.__objc_selrefs: 0x1268
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x88
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x3b8
+  __DATA_CONST.__got: 0x3e0
   __AUTH_CONST.__const: 0x120
-  __AUTH_CONST.__cfstring: 0xc40
+  __AUTH_CONST.__cfstring: 0xc80
   __AUTH_CONST.__objc_const: 0x26d0
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /System/Library/Frameworks/Intents.framework/Versions/A/Intents
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
+  - /System/Library/PrivateFrameworks/BaseBoard.framework/Versions/A/BaseBoard
   - /System/Library/PrivateFrameworks/SearchFoundation.framework/Versions/A/SearchFoundation
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /System/iOSSupport/System/Library/Frameworks/UIKit.framework/Versions/A/UIKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 403
-  Symbols:   1550
-  CStrings:  197
+  Functions: 410
+  Symbols:   1577
+  CStrings:  204
 
Symbols:
+ -[INUIAppIntentForwardingActionExecutor _executeForwardingAction:verifiedPeerAuditToken:completionHandler:]
+ GCC_except_table244
+ GCC_except_table255
+ GCC_except_table282
+ GCC_except_table379
+ GCC_except_table52
+ GCC_except_table58
+ _INIntentDeliveryEntitlement
+ _INIntentDeliveryGetMode
+ _INIntentDeliveryProcessDescription
+ _INIntentDeliveryRequestInActionInfo
+ _OBJC_CLASS_$_BSMutableSettings
+ _OBJC_CLASS_$_INIntentDeliveryListener
+ _OBJC_CLASS_$_INIntentForwardingActionResponse
+ ___107-[INUIAppIntentForwardingActionExecutor _executeForwardingAction:verifiedPeerAuditToken:completionHandler:]_block_invoke
+ ___107-[INUIAppIntentForwardingActionExecutor _executeForwardingAction:verifiedPeerAuditToken:completionHandler:]_block_invoke_2
+ ___107-[INUIAppIntentForwardingActionExecutor _executeForwardingAction:verifiedPeerAuditToken:completionHandler:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e88_v56?0"INIntentForwardingAction"8{?=[8I]}16?<v?"INIntentForwardingActionResponse">48ls32l8
+ ___block_descriptor_88_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ _getWFOnScreenContentExtractorClass
+ _objc_msgSend$_executeForwardingAction:verifiedPeerAuditToken:completionHandler:
+ _objc_msgSend$dispatchIntentForwardingAction:verifiedPeerAuditToken:completionHandler:
+ _objc_msgSend$envelope
+ _objc_msgSend$hostProcessAuditToken
+ _objc_msgSend$info
+ _objc_msgSend$initWithApplication:
+ _objc_msgSend$initWithInfo:error:
+ _objc_msgSend$setExecutionHandler:
+ _objc_msgSend$setObject:forSetting:
+ _objc_msgSend$sharedListener
+ _objc_retain_x9
- GCC_except_table237
- GCC_except_table248
- GCC_except_table275
- GCC_except_table372
CStrings:
+ "%s Refusing intent delivery handshake: verified delivery is off"
+ "%s Refusing intent forwarding action delivered without the handshake"
+ "%s Would refuse intent delivery without the handshake from %{public}@ (claimed): missing %{public}@ (audit mode)"
+ "-[INUIAppIntentForwardingActionExecutor executeAction:completionHandler:]"
+ "Intent delivery requires the verified handshake"
+ "Verified intent delivery is off"
+ "v56@?0@\"INIntentForwardingAction\"8{?=[8I]}16@?<v@?@\"INIntentForwardingActionResponse\">48"
```

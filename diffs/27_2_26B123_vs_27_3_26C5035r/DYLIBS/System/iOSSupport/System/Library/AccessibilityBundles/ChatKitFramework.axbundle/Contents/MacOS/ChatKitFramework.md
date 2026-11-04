## ChatKitFramework

> `/System/iOSSupport/System/Library/AccessibilityBundles/ChatKitFramework.axbundle/Contents/MacOS/ChatKitFramework`

```diff

-3050.3.6.0.0
-  __TEXT.__text: 0x2c730
+3050.3.12.0.0
+  __TEXT.__text: 0x2ca04
   __TEXT.__objc_methlist: 0x4f98
-  __TEXT.__const: 0x30
-  __TEXT.__gcc_except_tab: 0x810
-  __TEXT.__cstring: 0x91d3
-  __TEXT.__oslogstring: 0x98
+  __TEXT.__const: 0x38
+  __TEXT.__gcc_except_tab: 0x818
+  __TEXT.__cstring: 0x91ef
+  __TEXT.__oslogstring: 0x1b9
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x1390
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0xbf0
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18a0
+  __DATA_CONST.__objc_selrefs: 0x18a8
   __DATA_CONST.__objc_superrefs: 0x410
-  __DATA_CONST.__got: 0x428
+  __DATA_CONST.__got: 0x430
   __AUTH_CONST.__const: 0x640
-  __AUTH_CONST.__cfstring: 0xad80
+  __AUTH_CONST.__cfstring: 0xada0
   __AUTH_CONST.__objc_const: 0xd9a8
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1522
-  Symbols:   4431
-  CStrings:  1459
+  Symbols:   4433
+  CStrings:  1463
 
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ _IMChatValueKey
+ _objc_msgSend$userInfo
- ___40+[AXChatKitGlue _handleMessageReceived:]_block_invoke_2
Functions:
~ ___46+[AXChatKitGlue accessibilityInitializeBundle]_block_invoke : 948 -> 1008
~ ___46+[AXChatKitGlue accessibilityInitializeBundle]_block_invoke_6 : 76 -> 12
~ +[AXChatKitGlue _handleMessageReceived:] : 1160 -> 1728
~ -[AppCardContainerViewControllerAccessibility viewDidLayoutSubviews] : 656 -> 732
~ ___68-[AppCardContainerViewControllerAccessibility viewDidLayoutSubviews]_block_invoke_4 : 8 -> 92
CStrings:
+ "lastIncomingFinishedMessage"
+ "rdar://178159279 _handleMessageReceived announcing bodySummaryEmpty=%d"
+ "rdar://178159279 _handleMessageReceived fromNotification=%d resolved=%d resolvedIsTyping=%d legacyLastIncomingIsTyping=%d"
+ "rdar://178159279 _handleMessageReceived suppressed announcement, no sender resolved resolved=%d"
```

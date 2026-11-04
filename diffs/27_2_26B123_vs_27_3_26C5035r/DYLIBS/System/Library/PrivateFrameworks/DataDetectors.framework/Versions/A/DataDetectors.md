## DataDetectors

> `/System/Library/PrivateFrameworks/DataDetectors.framework/Versions/A/DataDetectors`

```diff

-481.0.0.0.0
-  __TEXT.__text: 0x23c78
+486.0.0.0.0
+  __TEXT.__text: 0x23c50
   __TEXT.__delay_helper: 0x2d0
-  __TEXT.__objc_methlist: 0x286c
-  __TEXT.__const: 0x120
-  __TEXT.__cstring: 0x211b
-  __TEXT.__oslogstring: 0x1053
+  __TEXT.__objc_methlist: 0x289c
+  __TEXT.__const: 0x100
+  __TEXT.__cstring: 0x212f
+  __TEXT.__oslogstring: 0xff1
   __TEXT.__gcc_except_tab: 0x110
-  __TEXT.__unwind_info: 0xb80
+  __TEXT.__unwind_info: 0xb78
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x158
+  __DATA_CONST.__const: 0xf8
   __DATA_CONST.__objc_classlist: 0x190
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1f50
+  __DATA_CONST.__objc_selrefs: 0x1f80
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xe8
-  __DATA_CONST.__got: 0x620
+  __DATA_CONST.__got: 0x618
   __AUTH_CONST.__const: 0x370
-  __AUTH_CONST.__cfstring: 0x2b00
-  __AUTH_CONST.__objc_const: 0x4560
+  __AUTH_CONST.__cfstring: 0x2b20
+  __AUTH_CONST.__objc_const: 0x45c0
   __AUTH_CONST.__auth_got: 0x6d0
   __AUTH.__objc_data: 0xf00
-  __DATA.__objc_ivar: 0x304
+  __DATA.__objc_ivar: 0x30c
   __DATA.__data: 0x5a0
   __DATA.__bss: 0xf0
   __DATA_DIRTY.__objc_data: 0xa0

   - /System/Library/PrivateFrameworks/PhoneNumbers.framework/Versions/A/PhoneNumbers
   - /System/Library/PrivateFrameworks/RTTUtilities.framework/Versions/A/RTTUtilities
   - /System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities
+  - /System/Library/PrivateFrameworks/TextInput.framework/Versions/A/TextInput
   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 890
-  Symbols:   2674
-  CStrings:  484
+  Functions: 892
+  Symbols:   2671
+  CStrings:  483
 
Symbols:
+ -[DDActionContext hostBundleIdentifier]
+ -[DDActionContext inputContextHistory]
+ -[DDActionContext setHostBundleIdentifier:]
+ -[DDActionContext setInputContextHistory:]
+ _OBJC_CLASS_$_TIInputContextHistory
+ _OBJC_IVAR_$_DDActionContext._hostBundleIdentifier
+ _OBJC_IVAR_$_DDActionContext._inputContextHistory
+ _SecTaskCopySigningIdentifier
+ _audit_token_to_pid
+ _getpid
+ _objc_msgSend$inputContextHistory
+ _objc_msgSend$normalizedHandleWithDestinationID:
+ _objc_msgSend$performSelector:
+ _objc_msgSend$setHostBundleIdentifier:
+ _objc_msgSend$setInputContextHistory:
- _CFDictionaryContainsKey
- _SecCodeCopySigningInformation
- _SecCodeCreateWithAuditToken
- _kCFBundleIdentifierKey
- _kDataDetectorsABPersonAuthorKey
- _kDataDetectorsAllResultsKey
- _kDataDetectorsAuthorAsEmailAddressKey
- _kDataDetectorsAuthorNameComponentsKey
- _kDataDetectorsAuthorPictureKey
- _kDataDetectorsCNContactKey
- _kDataDetectorsCoreSpotlightUniqueIdentifier
- _kDataDetectorsHostUUIDKey
- _kDataDetectorsLeadingTextKey
- _kDataDetectorsMatchedStringKey
- _kDataDetectorsSelectionStringKey
- _kDataDetectorsTrailingTextKey
- _kSecCodeInfoPList
- _objc_msgSend$handleWithDestinationID:
CStrings:
+ "inputContextHistory"
+ "\xf0\xf0\xd1"
- "Could not copy signing information from secCode: %d"
- "Could not create secCode with audit token: %d"
- "\xf0\xf0\xc1"
```

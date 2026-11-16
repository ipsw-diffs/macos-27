## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth`

```diff

-2702.3.1.0.0
-  __TEXT.__text: 0xdd290
-  __TEXT.__objc_methlist: 0xd734
+2702.6.0.0.0
+  __TEXT.__text: 0xde8c8
+  __TEXT.__objc_methlist: 0xd76c
   __TEXT.__const: 0x2d55
   __TEXT.__oslogstring: 0x31cb
-  __TEXT.__cstring: 0x1b231
+  __TEXT.__cstring: 0x1b281
   __TEXT.__gcc_except_tab: 0x2658
   __TEXT.__ustring: 0x82
-  __TEXT.__unwind_info: 0x3af8
+  __TEXT.__unwind_info: 0x3b10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5c80
+  __DATA_CONST.__const: 0x5c98
   __DATA_CONST.__objc_classlist: 0x350
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5ce8
+  __DATA_CONST.__objc_selrefs: 0x5d10
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x140
   __DATA_CONST.__got: 0x400
   __AUTH_CONST.__const: 0x1630
-  __AUTH_CONST.__cfstring: 0x11080
-  __AUTH_CONST.__objc_const: 0x1c630
+  __AUTH_CONST.__cfstring: 0x110a0
+  __AUTH_CONST.__objc_const: 0x1c670
   __AUTH_CONST.__objc_intobj: 0x960
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0x978
   __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x138c
+  __DATA.__objc_ivar: 0x1390
   __DATA.__data: 0xcf8
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x20d0

   - /System/Library/PrivateFrameworks/TCC.framework/Versions/A/TCC
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5598
-  Symbols:   10159
-  CStrings:  5146
+  Functions: 5607
+  Symbols:   10170
+  CStrings:  5152
 
Symbols:
+ -[CBDevice _clearFindMyProxyServiceData]
+ -[CBDevice findMyProxyServiceData]
+ -[CBDevice setFindMyProxyServiceData:]
+ -[CBWPDaemonAdvertisingData advertisingUseCase]
+ -[CBWPDaemonAdvertisingData setAdvertisingUseCase:]
+ GCC_except_table539
+ GCC_except_table546
+ GCC_except_table561
+ GCC_except_table626
+ _OBJC_IVAR_$_CBWPDaemonAdvertisingData._advertisingUseCase
+ _objc_msgSend$_clearFindMyProxyServiceData
+ _objc_msgSend$advertisingUseCase
+ _objc_msgSend$findMyProxyServiceData
+ _objc_msgSend$setAdvertisingUseCase:
+ _objc_msgSend$setFindMyProxyServiceData:
- GCC_except_table536
- GCC_except_table543
- GCC_except_table558
- GCC_except_table623
CStrings:
+ ", fmpSD <%@>"
+ ", fmpSD <private>"
+ ", useCase: %s"
+ "FindMyProxy"
+ "FindMyProxyOptedIn"
+ "MobileBluetooth-2702.6"
+ "fmpSD"
- "MobileBluetooth-2702.3.1"
```

## FSKit

> `/System/Library/Frameworks/FSKit.framework/Versions/A/FSKit`

```diff

-974.40.12.0.0
-  __TEXT.__text: 0x57af0
-  __TEXT.__objc_methlist: 0x6378
+974.60.5.0.0
+  __TEXT.__text: 0x57c5c
+  __TEXT.__objc_methlist: 0x6390
   __TEXT.__const: 0x4a8
   __TEXT.__gcc_except_tab: 0xe84
-  __TEXT.__oslogstring: 0x4006
-  __TEXT.__cstring: 0x63df
+  __TEXT.__oslogstring: 0x4126
+  __TEXT.__cstring: 0x642f
   __TEXT.__swift5_typeref: 0x264
   __TEXT.__swift5_capture: 0xec
   __TEXT.__swift_as_entry: 0x1c

   __TEXT.__constg_swiftt: 0x210
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x22c8
+  __TEXT.__unwind_info: 0x22d8
   __TEXT.__eh_frame: 0x400
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2c40
+  __DATA_CONST.__objc_selrefs: 0x2c50
   __DATA_CONST.__objc_protorefs: 0x150
   __DATA_CONST.__objc_superrefs: 0x2e8
   __DATA_CONST.__objc_arraydata: 0x488
   __DATA_CONST.__got: 0x488
   __AUTH_CONST.__const: 0x1ec0
-  __AUTH_CONST.__cfstring: 0x2b40
-  __AUTH_CONST.__objc_const: 0xb2e8
+  __AUTH_CONST.__cfstring: 0x2b60
+  __AUTH_CONST.__objc_const: 0xb308
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x2a8
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__auth_got: 0x7e0
   __AUTH.__objc_data: 0x1fe0
   __AUTH.__data: 0x80
-  __DATA.__objc_ivar: 0x640
+  __DATA.__objc_ivar: 0x644
   __DATA.__data: 0x15c8
-  __DATA.__bss: 0x360
+  __DATA.__bss: 0x370
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x550
   __DATA_DIRTY.__data: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2754
-  Symbols:   5139
-  CStrings:  1094
+  Functions: 2757
+  Symbols:   5144
+  CStrings:  1098
 
Symbols:
+ -[FSItemAttributes validMask]
+ -[FSItemSetAttributesRequest reportedConsumedAttributes]
+ _OBJC_IVAR_$_FSItemSetAttributesRequest._consumedAttributesReported
+ _gWarnedUnreportedConsumedAttributes
+ _objc_msgSend$reportedConsumedAttributes
+ _objc_msgSend$validMask
- _objc_msgSend$consumedAttributes
CStrings:
+ "%s: module completed setAttributes without setting FSItemSetAttributesRequest.consumedAttributes. FSKit has to assume every requested attribute was applied. Explicitly set consumedAttributes to 0 if nothing was applied."
+ "%s: module did not consume attributes 0x%llx of requested 0x%llx"
+ "-[FSItemSetAttributesRequest reportedConsumedAttributes]"
+ "FSItemAttrConsumedSet"
```

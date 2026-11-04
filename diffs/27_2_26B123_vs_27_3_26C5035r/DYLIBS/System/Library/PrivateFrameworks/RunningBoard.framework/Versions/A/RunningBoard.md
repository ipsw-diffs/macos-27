## RunningBoard

> `/System/Library/PrivateFrameworks/RunningBoard.framework/Versions/A/RunningBoard`

```diff

-1084.40.7.0.0
-  __TEXT.__text: 0x7e3e0
+1084.60.3.0.0
+  __TEXT.__text: 0x7e6e0
   __TEXT.__objc_methlist: 0x63dc
   __TEXT.__const: 0x240
-  __TEXT.__cstring: 0x6d56
-  __TEXT.__oslogstring: 0xb69c
+  __TEXT.__cstring: 0x6d6c
+  __TEXT.__oslogstring: 0xb6e3
   __TEXT.__gcc_except_tab: 0xb4c
-  __TEXT.__unwind_info: 0x2400
+  __TEXT.__unwind_info: 0x2410
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x170
   __DATA_CONST.__objc_protolist: 0x198
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2e58
+  __DATA_CONST.__objc_selrefs: 0x2e68
   __DATA_CONST.__objc_superrefs: 0x2a0
   __DATA_CONST.__objc_arraydata: 0x750
-  __DATA_CONST.__got: 0x780
+  __DATA_CONST.__got: 0x788
   __AUTH_CONST.__const: 0x1d30
-  __AUTH_CONST.__cfstring: 0x5ce0
+  __AUTH_CONST.__cfstring: 0x5d00
   __AUTH_CONST.__objc_const: 0xdb58
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x460

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 2907
-  Symbols:   6199
-  CStrings:  1735
+  Functions: 2911
+  Symbols:   6202
+  CStrings:  1737
 
Symbols:
+ -[RBConnectionClient _rbs_clientTrustedForAssertionErrorDetail]
+ -[RBSLegacyAttribute _isOriginatorValidForContext:errorReason:redactForUntrustedClient:]
+ -[RBSLegacyAttribute _isTargetValidForContext:errorReason:redactForUntrustedClient:]
+ _RBSErrorRedactForUntrustedClientKey
+ _objc_msgSend$rbs_errorRedactedForUntrustedClient
- -[RBSLegacyAttribute _isOriginatorValidForContext:errorReason:]
- -[RBSLegacyAttribute _isTargetValidForContext:errorReason:]
CStrings:
+ "Assertion acquisition failed: target process %{public}@ does not exist"
+ "outRedact is required"
```

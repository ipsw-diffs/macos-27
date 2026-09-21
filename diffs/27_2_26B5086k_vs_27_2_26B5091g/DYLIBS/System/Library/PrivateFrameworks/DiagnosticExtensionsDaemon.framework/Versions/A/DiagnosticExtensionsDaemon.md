## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/Versions/A/DiagnosticExtensionsDaemon`

```diff

-223.0.0.0.0
-  __TEXT.__text: 0x7b6b0
-  __TEXT.__objc_methlist: 0x6fbc
+224.0.0.0.0
+  __TEXT.__text: 0x7b950
+  __TEXT.__objc_methlist: 0x7004
   __TEXT.__const: 0x372
-  __TEXT.__cstring: 0x5540
+  __TEXT.__cstring: 0x5530
   __TEXT.__gcc_except_tab: 0x1ad0
-  __TEXT.__oslogstring: 0x9718
+  __TEXT.__oslogstring: 0x9738
   __TEXT.__ustring: 0xc
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x48

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xad0
+  __DATA_CONST.__const: 0xad8
   __DATA_CONST.__objc_classlist: 0x278
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3b80
+  __DATA_CONST.__objc_selrefs: 0x3bb0
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0x48
   __DATA_CONST.__got: 0x6c8
   __AUTH_CONST.__const: 0x2270
   __AUTH_CONST.__cfstring: 0x4e00
-  __AUTH_CONST.__objc_const: 0x13a38
+  __AUTH_CONST.__objc_const: 0x13ac8
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x360
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x548
   __AUTH.__objc_data: 0x90
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x5e0
+  __DATA.__objc_ivar: 0x5ec
   __DATA.__data: 0xad0
   __DATA.__bss: 0x1c0
   __DATA_DIRTY.__objc_data: 0x18e0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2976
-  Symbols:   5939
-  CStrings:  1763
+  Functions: 2982
+  Symbols:   5951
+  CStrings:  1764
 
Symbols:
+ -[DEDBugSessionConfiguration seedingCookieName]
+ -[DEDBugSessionConfiguration seedingFilerURL]
+ -[DEDBugSessionConfiguration seedingUsesPinning]
+ -[DEDBugSessionConfiguration setSeedingCookieName:]
+ -[DEDBugSessionConfiguration setSeedingFilerURL:]
+ -[DEDBugSessionConfiguration setSeedingUsesPinning:]
+ OBJC_IVAR_$_DEDBugSessionConfiguration._seedingCookieName
+ OBJC_IVAR_$_DEDBugSessionConfiguration._seedingFilerURL
+ OBJC_IVAR_$_DEDBugSessionConfiguration._seedingUsesPinning
+ _DEDKeySeedingCookieName
+ _DEDKeySeedingFilerURL
+ _DEDKeySeedingUsesPinning
+ _objc_msgSend$seedingCookieName
+ _objc_msgSend$seedingFilerURL
+ _objc_msgSend$seedingUsesPinning
- _DEDKeySeedingEnvironment
- _DEDSeedingClientFilerURL
- _objc_msgSend$seedingEnvironment
CStrings:
+ "Discovery returned [%lu] extensions"
+ "No cached extensions; re-running discovery"
+ "Pinning disabled by config; skipping pinning check."
+ "seedingCookieName"
+ "seedingFilerURL"
+ "seedingUsesPinning"
- "FBAFilerURL"
- "Running in development mode; skipping pinning check."
- "Using user default value for filer URL"
- "_seedportal_session_uat"
- "seedingEnvironment"
```

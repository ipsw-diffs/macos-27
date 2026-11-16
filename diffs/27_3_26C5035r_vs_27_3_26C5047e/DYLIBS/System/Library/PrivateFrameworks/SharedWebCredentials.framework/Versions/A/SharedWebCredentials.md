## SharedWebCredentials

> `/System/Library/PrivateFrameworks/SharedWebCredentials.framework/Versions/A/SharedWebCredentials`

```diff

-1036.2.0.0.0
-  __TEXT.__text: 0x15c4c
+1040.2.0.0.0
+  __TEXT.__text: 0x15c68
   __TEXT.__objc_methlist: 0xf9c
   __TEXT.__const: 0xd0
-  __TEXT.__gcc_except_tab: 0x2510
+  __TEXT.__gcc_except_tab: 0x251c
   __TEXT.__cstring: 0x1598
   __TEXT.__oslogstring: 0x896
   __TEXT.__ustring: 0x4

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xab8
+  __DATA_CONST.__objc_selrefs: 0xac0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x68

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 409
-  Symbols:   1091
+  Symbols:   1092
   CStrings:  276
 
Symbols:
+ _objc_msgSend$isPlaceholder
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[_SWCChatterboxResolver resolveWithCompletionHandler:] : 948 -> 944
~ +[_SWCChatterboxResolver(Private) _session] : 268 -> 264
~ +[_SWCChatterboxResolver(Private) _resolverForTask:] : 160 -> 156
~ +[_SWCChatterboxResolver(Private) _setResolver:forTask:] : 232 -> 228
~ +[_SWCChatterboxResolver(Private) _invokeCompletionHandlerForTask:result:error:] : 716 -> 712
~ -[_SWCApplicationIdentifier(LSInterop) initForBundleRecord:] : 332 -> 380
```

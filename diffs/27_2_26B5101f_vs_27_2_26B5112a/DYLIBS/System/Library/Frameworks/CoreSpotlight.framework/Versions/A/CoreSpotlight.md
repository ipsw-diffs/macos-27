## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/Versions/A/CoreSpotlight`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2465.1.7.0.0
-  __TEXT.__text: 0x198f0c
+2465.1.9.0.0
+  __TEXT.__text: 0x1991d8
   __TEXT.__objc_methlist: 0x14ac0
   __TEXT.__const: 0xf60
   __TEXT.__cstring: 0x2c6f8
-  __TEXT.__oslogstring: 0xc033
+  __TEXT.__oslogstring: 0xc115
   __TEXT.__gcc_except_tab: 0x9af8
   __TEXT.__ustring: 0x218e
   __TEXT.__dlopen_cstrs: 0x438

   __TEXT.__swift_as_cont: 0xc
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x7558
+  __TEXT.__unwind_info: 0x7568
   __TEXT.__eh_frame: 0x1e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa738
+  __DATA_CONST.__objc_selrefs: 0xa740
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x750
   __DATA_CONST.__objc_arraydata: 0x11108
-  __DATA_CONST.__got: 0xed8
+  __DATA_CONST.__got: 0xee0
   __AUTH_CONST.__const: 0x5610
   __AUTH_CONST.__cfstring: 0x2e0e0
-  __AUTH_CONST.__objc_const: 0x208c0
+  __AUTH_CONST.__objc_const: 0x208e0
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x3a98
   __AUTH_CONST.__objc_dictobj: 0xaf78

   __AUTH.__data: 0x3a0
   __AUTH.__thread_vars: 0x60
   __AUTH.__thread_bss: 0x28
-  __DATA.__objc_ivar: 0x14d0
+  __DATA.__objc_ivar: 0x14d4
   __DATA.__data: 0x1c48
   __DATA.__bss: 0x19c0
   __DATA_DIRTY.__objc_data: 0x1428

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9201
-  Symbols:   18382
-  CStrings:  8119
+  Functions: 9204
+  Symbols:   18385
+  CStrings:  8122
 
Symbols:
+ OBJC_IVAR_$_CSFileProviderDomainMonitor._savedRemovedCount
+ _NSURLFileSizeKey
+ _objc_msgSend$removeItemAtURL:error:
CStrings:
+ "At the %lu removed FP domain ceiling; not tracking further removals"
+ "Discarding saved FP domain list: %llu bytes exceeds the %llu byte budget"
+ "Saved FP domain list holds %lu entries; tracking the first %lu and ignoring the rest"
```

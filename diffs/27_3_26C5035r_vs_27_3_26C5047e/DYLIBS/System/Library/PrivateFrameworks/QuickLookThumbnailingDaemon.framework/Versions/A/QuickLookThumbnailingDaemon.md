## QuickLookThumbnailingDaemon

> `/System/Library/PrivateFrameworks/QuickLookThumbnailingDaemon.framework/Versions/A/QuickLookThumbnailingDaemon`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-218.1.2.0.0
-  __TEXT.__text: 0x567b8
-  __TEXT.__objc_methlist: 0x319c
+218.3.2.0.0
+  __TEXT.__text: 0x5698c
+  __TEXT.__objc_methlist: 0x31bc
   __TEXT.__const: 0xfd4
   __TEXT.__gcc_except_tab: 0xb94
   __TEXT.__cstring: 0x4141
-  __TEXT.__oslogstring: 0x5505
+  __TEXT.__oslogstring: 0x5545
   __TEXT.__constg_swiftt: 0x400
   __TEXT.__swift5_typeref: 0xe48
   __TEXT.__swift5_builtin: 0x78

   __TEXT.__swift_as_ret: 0x28
   __TEXT.__swift_as_cont: 0x2c
   __TEXT.__dof_QuickLook: 0xb22
-  __TEXT.__unwind_info: 0x1c40
+  __TEXT.__unwind_info: 0x1c48
   __TEXT.__eh_frame: 0x710
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x24f0
+  __DATA_CONST.__objc_selrefs: 0x2508
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x790
   __AUTH_CONST.__const: 0x1f40
   __AUTH_CONST.__cfstring: 0x1ae0
-  __AUTH_CONST.__objc_const: 0x53e0
+  __AUTH_CONST.__objc_const: 0x5460
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0xf38
+  __AUTH_CONST.__auth_got: 0xf30
   __AUTH.__objc_data: 0x268
   __AUTH.__data: 0xc8
-  __DATA.__objc_ivar: 0x4a8
+  __DATA.__objc_ivar: 0x4b4
   __DATA.__data: 0x490
   __DATA.__bss: 0xba0
   __DATA.__common: 0x48

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2034
-  Symbols:   3680
-  CStrings:  856
+  Functions: 2038
+  Symbols:   3685
+  CStrings:  857
 
Symbols:
+ -[QLServerThread _saveLargeThumbnailToGenstoreWithData:url:writeAccessURL:]
+ -[QLServerThread locationCacheLock]
+ -[QLServerThread locationsToCaches]
+ -[QLServerThread setLocationsToCaches:]
+ _OBJC_IVAR_$_QLServerThread._locationCacheLock
+ _OBJC_IVAR_$_QLServerThread._locationsToCaches
+ _OBJC_IVAR_$__QLCacheThread._resetDeferred
+ _objc_msgSend$_saveLargeThumbnailToGenstoreWithData:url:writeAccessURL:
- -[QLServerThread _saveLargeThumbnailToGenstoreWithData:url:]
- _fcntl
- _objc_msgSend$_saveLargeThumbnailToGenstoreWithData:url:
CStrings:
+ "No explicit write access for the GenStore write to %@"
```

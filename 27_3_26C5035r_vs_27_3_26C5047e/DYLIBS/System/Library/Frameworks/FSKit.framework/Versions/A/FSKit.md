## FSKit

> `/System/Library/Frameworks/FSKit.framework/Versions/A/FSKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-974.60.5.0.0
-  __TEXT.__text: 0x57c5c
-  __TEXT.__objc_methlist: 0x6390
+974.60.6.0.0
+  __TEXT.__text: 0x57d30
+  __TEXT.__objc_methlist: 0x63c8
   __TEXT.__const: 0x4a8
   __TEXT.__gcc_except_tab: 0xe84
-  __TEXT.__oslogstring: 0x4126
+  __TEXT.__oslogstring: 0x4146
   __TEXT.__cstring: 0x642f
   __TEXT.__swift5_typeref: 0x264
   __TEXT.__swift5_capture: 0xec

   __TEXT.__constg_swiftt: 0x210
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x22d8
+  __TEXT.__unwind_info: 0x22d0
   __TEXT.__eh_frame: 0x400
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2c50
+  __DATA_CONST.__objc_selrefs: 0x2c68
   __DATA_CONST.__objc_protorefs: 0x150
   __DATA_CONST.__objc_superrefs: 0x2e8
   __DATA_CONST.__objc_arraydata: 0x488
   __DATA_CONST.__got: 0x488
   __AUTH_CONST.__const: 0x1ec0
   __AUTH_CONST.__cfstring: 0x2b60
-  __AUTH_CONST.__objc_const: 0xb308
+  __AUTH_CONST.__objc_const: 0xb388
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x2a8
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__auth_got: 0x7e0
   __AUTH.__objc_data: 0x1fe0
   __AUTH.__data: 0x80
-  __DATA.__objc_ivar: 0x644
+  __DATA.__objc_ivar: 0x64c
   __DATA.__data: 0x15c8
   __DATA.__bss: 0x370
   __DATA.__common: 0x18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2757
-  Symbols:   5144
-  CStrings:  1098
+  Functions: 2758
+  Symbols:   5151
+  CStrings:  1097
 
Symbols:
+ -[FSModuleVolume supportedRenameFlags]
+ -[FSModuleVolume supportsRenameWithFlags]
+ GCC_except_table119
+ GCC_except_table205
+ GCC_except_table266
+ GCC_except_table62
+ GCC_except_table66
+ _OBJC_IVAR_$_FSModuleVolume._supportedRenameFlags
+ _OBJC_IVAR_$_FSModuleVolume._supportsRenameWithFlags
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_FSVolumeHandler
+ _objc_msgSend$renameItem:inDirectory:named:toNewName:inDirectory:overItem:flags:context:replyHandler:
+ _objc_msgSend$supportedRenameFlags
+ _objc_msgSend$supportsRenameWithFlags
- GCC_except_table148
- GCC_except_table203
- GCC_except_table264
- GCC_except_table58
- GCC_except_table59
- GCC_except_table64
CStrings:
+ "%s: volume doesn't support rename flags 0x%lx (requested 0x%lx, supported 0x%lx). Error = %d."
- "%s: rename flags aren't supported (requested 0x%x). Error = %d."
- "Y"
```

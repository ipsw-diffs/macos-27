## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/Contents/MacOS/ANELargeModelCompilerService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-382.100.0.0.0
-  __TEXT.__text: 0x1bff8
-  __TEXT.__auth_stubs: 0x720
+382.101.0.0.0
+  __TEXT.__text: 0x1c2b4
+  __TEXT.__auth_stubs: 0x730
   __TEXT.__objc_stubs: 0x22c0
   __TEXT.__objc_methlist: 0x9b4
   __TEXT.__const: 0x128
   __TEXT.__cstring: 0x1383
-  __TEXT.__oslogstring: 0x267e
+  __TEXT.__oslogstring: 0x26ef
   __TEXT.__objc_classname: 0x19e
   __TEXT.__objc_methname: 0x264d
   __TEXT.__objc_methtype: 0x67b
-  __TEXT.__gcc_except_tab: 0x12d4
-  __TEXT.__unwind_info: 0x5d8
+  __TEXT.__gcc_except_tab: 0x12ec
+  __TEXT.__unwind_info: 0x5e0
   __DATA_CONST.__const: 0x3b0
   __DATA_CONST.__cfstring: 0x19a0
   __DATA_CONST.__objc_classlist: 0x80

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_intobj: 0x90
-  __DATA_CONST.__auth_got: 0x3a8
+  __DATA_CONST.__auth_got: 0x3b0
   __DATA_CONST.__got: 0x1c0
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0xd48
   __DATA.__objc_selrefs: 0xaa8
   __DATA.__objc_ivar: 0x24

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 343
-  Symbols:   969
-  CStrings:  898
+  Functions: 346
+  Symbols:   972
+  CStrings:  900
 
Symbols:
+ __ANEStorageProbeFileIsReadable
+ ___chkstk_darwin
+ _pread
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
```

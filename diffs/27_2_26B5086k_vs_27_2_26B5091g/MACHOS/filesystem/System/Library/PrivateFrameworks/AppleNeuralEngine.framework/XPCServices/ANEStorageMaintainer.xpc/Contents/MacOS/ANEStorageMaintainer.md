## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/Contents/MacOS/ANEStorageMaintainer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
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
-  __TEXT.__text: 0x8e94
-  __TEXT.__auth_stubs: 0x3f0
+382.101.0.0.0
+  __TEXT.__text: 0x9180
+  __TEXT.__auth_stubs: 0x400
   __TEXT.__objc_stubs: 0xfa0
   __TEXT.__objc_methlist: 0x3e4
-  __TEXT.__const: 0xd0
-  __TEXT.__oslogstring: 0x103c
+  __TEXT.__const: 0xd8
+  __TEXT.__oslogstring: 0x10ad
   __TEXT.__objc_classname: 0x86
   __TEXT.__objc_methname: 0x1094
   __TEXT.__objc_methtype: 0x276
-  __TEXT.__gcc_except_tab: 0x154
+  __TEXT.__gcc_except_tab: 0x16c
   __TEXT.__cstring: 0x1ee
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x228
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x20

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x208
+  __DATA_CONST.__auth_got: 0x210
   __DATA_CONST.__got: 0xd0
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x450
   __DATA.__objc_selrefs: 0x528
   __DATA.__objc_ivar: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 116
-  Symbols:   382
-  CStrings:  344
+  Functions: 121
+  Symbols:   385
+  CStrings:  346
 
Symbols:
+ GCC_except_table13
+ __ANEStorageProbeFileIsReadable
+ ___chkstk_darwin
+ _pread
- GCC_except_table12
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
```

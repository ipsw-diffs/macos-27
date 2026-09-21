## aneuserd

> `/usr/libexec/aneuserd`

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
-  __TEXT.__text: 0x7ec68
-  __TEXT.__auth_stubs: 0xe10
+382.101.0.0.0
+  __TEXT.__text: 0x7ef3c
+  __TEXT.__auth_stubs: 0xe20
   __TEXT.__objc_stubs: 0x3640
   __TEXT.__objc_methlist: 0x12c4
   __TEXT.__const: 0x6100
   __TEXT.__cstring: 0x6529
   __TEXT.__objc_methname: 0x412e
-  __TEXT.__oslogstring: 0x6dae
+  __TEXT.__oslogstring: 0x6e2a
   __TEXT.__objc_classname: 0x261
   __TEXT.__objc_methtype: 0xecd
-  __TEXT.__gcc_except_tab: 0x5f68
-  __TEXT.__unwind_info: 0x2bc8
+  __TEXT.__gcc_except_tab: 0x5f7c
+  __TEXT.__unwind_info: 0x2bd0
   __DATA_CONST.__const: 0x2ca0
   __DATA_CONST.__cfstring: 0x14c0
   __DATA_CONST.__objc_classlist: 0xa0

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x720
+  __DATA_CONST.__auth_got: 0x728
   __DATA_CONST.__got: 0x280
-  __DATA_CONST.__auth_ptr: 0x18
+  __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x1f88
   __DATA.__objc_selrefs: 0x1060
   __DATA.__objc_ivar: 0xf4

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2824
-  Symbols:   4241
-  CStrings:  1868
+  Functions: 2826
+  Symbols:   4243
+  CStrings:  1870
 
Symbols:
+ __ANEStorageProbeFileIsReadable
+ _pread
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: perTdStats Model patching is not enabled"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
- "%@: Model patching is not enabled"
```

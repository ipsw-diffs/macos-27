## aned

> `/usr/libexec/aned`

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
-  __TEXT.__text: 0x7dbfc
-  __TEXT.__auth_stubs: 0xe00
+382.101.0.0.0
+  __TEXT.__text: 0x7ded0
+  __TEXT.__auth_stubs: 0xe10
   __TEXT.__objc_stubs: 0x3460
   __TEXT.__objc_methlist: 0x1184
   __TEXT.__const: 0x60fc
-  __TEXT.__gcc_except_tab: 0x5f68
+  __TEXT.__gcc_except_tab: 0x5f7c
   __TEXT.__cstring: 0x5cf2
-  __TEXT.__oslogstring: 0x6d3c
+  __TEXT.__oslogstring: 0x6db8
   __TEXT.__objc_classname: 0x247
   __TEXT.__objc_methname: 0x3e92
   __TEXT.__objc_methtype: 0xeaf
-  __TEXT.__unwind_info: 0x2b78
+  __TEXT.__unwind_info: 0x2b80
   __DATA_CONST.__const: 0x2c38
   __DATA_CONST.__cfstring: 0xaa0
   __DATA_CONST.__objc_classlist: 0x90

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x718
+  __DATA_CONST.__auth_got: 0x720
   __DATA_CONST.__got: 0x3b8
-  __DATA_CONST.__auth_ptr: 0x18
+  __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x1c98
   __DATA.__objc_selrefs: 0xfc0
   __DATA.__objc_ivar: 0xe4

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2798
-  Symbols:   4143
-  CStrings:  1760
+  Functions: 2800
+  Symbols:   4145
+  CStrings:  1762
 
Symbols:
+ __ANEStorageProbeFileIsReadable
+ _pread
CStrings:
+ "%@: %@ failed readability probe. Returning nil"
+ "%@: perTdStats Model patching is not enabled"
+ "%@: pread(%@, offset=%zu, want=%zu) failed. got=%zd errno=%d : %s"
- "%@: Model patching is not enabled"
```

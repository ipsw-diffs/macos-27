## diskimagesiod

> `/usr/libexec/diskimagesiod`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-598.60.2.0.0
-  __TEXT.__text: 0x203c44
+598.60.3.0.0
+  __TEXT.__text: 0x203cbc
   __TEXT.__auth_stubs: 0x2580
-  __TEXT.__objc_stubs: 0x6ee0
-  __TEXT.__objc_methlist: 0x3d54
+  __TEXT.__objc_stubs: 0x6f00
+  __TEXT.__objc_methlist: 0x3d5c
   __TEXT.__const: 0x17e97
-  __TEXT.__gcc_except_tab: 0x1e23c
-  __TEXT.__objc_methname: 0x8114
+  __TEXT.__gcc_except_tab: 0x1e240
+  __TEXT.__objc_methname: 0x813e
   __TEXT.__oslogstring: 0x3c96
   __TEXT.__cstring: 0x15b6e
   __TEXT.__objc_classname: 0x6e0

   __DATA_CONST.__got: 0x718
   __DATA_CONST.__auth_ptr: 0x50
   __DATA.__objc_const: 0x5f20
-  __DATA.__objc_selrefs: 0x20a8
+  __DATA.__objc_selrefs: 0x20b0
   __DATA.__objc_ivar: 0x340
   __DATA.__objc_data: 0x1890
   __DATA.__data: 0xe40

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 12057
+  Functions: 12058
   Symbols:   850
-  CStrings:  4365
+  CStrings:  4366
 
CStrings:
+ "initWithPstackFileHandle:pstackURL:error:"
```

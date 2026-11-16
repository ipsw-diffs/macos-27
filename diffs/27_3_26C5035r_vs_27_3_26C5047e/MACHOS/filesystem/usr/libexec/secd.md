## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62460.60.42.501.1
-  __TEXT.__text: 0x28c3e4
+62460.60.60.0.1
+  __TEXT.__text: 0x28c7a4
   __TEXT.__auth_stubs: 0x4160
-  __TEXT.__objc_stubs: 0x1dda0
-  __TEXT.__objc_methlist: 0x16048
+  __TEXT.__objc_stubs: 0x1ddc0
+  __TEXT.__objc_methlist: 0x16050
   __TEXT.__const: 0x930
   __TEXT.__objc_classname: 0x2531
-  __TEXT.__objc_methname: 0x2ec77
+  __TEXT.__objc_methname: 0x2ec97
   __TEXT.__objc_methtype: 0xb156
   __TEXT.__constg_swiftt: 0x274
   __TEXT.__swift5_typeref: 0x35e

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
   __TEXT.__swift5_types: 0x20
-  __TEXT.__cstring: 0x2241c
-  __TEXT.__oslogstring: 0x2ffd4
+  __TEXT.__cstring: 0x2244c
+  __TEXT.__oslogstring: 0x30004
   __TEXT.__swift5_capture: 0x1bc
   __TEXT.__swift_as_entry: 0x40
   __TEXT.__swift_as_ret: 0x3c
   __TEXT.__swift_as_cont: 0x48
   __TEXT.__dlopen_cstrs: 0x5a
-  __TEXT.__gcc_except_tab: 0xa22c
-  __TEXT.__unwind_info: 0x7eb8
+  __TEXT.__gcc_except_tab: 0xa244
+  __TEXT.__unwind_info: 0x7ec0
   __TEXT.__eh_frame: 0xa60
   __DATA_CONST.__const: 0x15c70
-  __DATA_CONST.__cfstring: 0x1c640
+  __DATA_CONST.__cfstring: 0x1c660
   __DATA_CONST.__objc_classlist: 0x918
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x258

   __DATA_CONST.__got: 0x1488
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA.__objc_const: 0x23f18
-  __DATA.__objc_selrefs: 0x99a0
+  __DATA.__objc_selrefs: 0x99a8
   __DATA.__objc_ivar: 0x1b08
   __DATA.__objc_data: 0x5de8
   __DATA.__data: 0x30a0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 10095
+  Functions: 10096
   Symbols:   1856
-  CStrings:  16463
+  CStrings:  16465
 
CStrings:
+ "Out of band fetch disabled due to bad TLK state"
+ "anyViewsInBadTLKStateForOutOfBand:"
```

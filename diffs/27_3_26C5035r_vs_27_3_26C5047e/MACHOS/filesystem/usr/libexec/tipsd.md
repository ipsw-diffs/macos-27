## tipsd

> `/usr/libexec/tipsd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
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
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-866.3.1.0.0
-  __TEXT.__text: 0x17d10
-  __TEXT.__auth_stubs: 0xad0
-  __TEXT.__objc_stubs: 0x2cc0
+866.3.3.0.0
+  __TEXT.__text: 0x17dc8
+  __TEXT.__auth_stubs: 0xae0
+  __TEXT.__objc_stubs: 0x2d00
   __TEXT.__objc_methlist: 0xd18
   __TEXT.__const: 0x376
   __TEXT.__gcc_except_tab: 0x498
   __TEXT.__cstring: 0xccc
-  __TEXT.__objc_methname: 0x366c
-  __TEXT.__oslogstring: 0x177e
+  __TEXT.__objc_methname: 0x368c
+  __TEXT.__oslogstring: 0x1791
   __TEXT.__objc_classname: 0x225
   __TEXT.__objc_methtype: 0x1139
   __TEXT.__swift5_entry: 0x8

   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_intobj: 0x60
-  __DATA_CONST.__auth_got: 0x578
+  __DATA_CONST.__auth_got: 0x580
   __DATA_CONST.__got: 0x390
   __DATA_CONST.__auth_ptr: 0xd8
   __DATA.__objc_const: 0xc50
-  __DATA.__objc_selrefs: 0xe58
+  __DATA.__objc_selrefs: 0xe68
   __DATA.__objc_ivar: 0x68
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x650

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 505
-  Symbols:   347
-  CStrings:  893
+  Symbols:   348
+  CStrings:  896
 
Symbols:
+ _arc4random_uniform
Functions:
~ sub_100008bc8 : 1336 -> 1472
~ sub_10001679c -> sub_100016824 : 260 -> 284
~ sub_1000168a0 -> sub_100016940 : 128 -> 152
CStrings:
+ "Rollout bucket %ld"
+ "rolloutBucket"
+ "setRolloutBucket:"
```

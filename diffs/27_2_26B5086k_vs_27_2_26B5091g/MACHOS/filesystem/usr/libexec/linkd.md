## linkd

> `/usr/libexec/linkd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-301.1.9.1.401
-  __TEXT.__text: 0xb9d44
+301.1.10.1.0
+  __TEXT.__text: 0xb9d7c
   __TEXT.__auth_stubs: 0x25d0
   __TEXT.__objc_stubs: 0x2760
   __TEXT.__objc_methlist: 0xe84

   __TEXT.__swift5_types: 0x1ac
   __TEXT.__swift5_capture: 0x2fb0
   __TEXT.__oslogstring: 0x4ec3
-  __TEXT.__cstring: 0x1b55
+  __TEXT.__cstring: 0x1bb5
   __TEXT.__swift_as_entry: 0x5a4
   __TEXT.__swift_as_ret: 0x56c
   __TEXT.__swift_as_cont: 0x72c

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 5341
   Symbols:   1100
-  CStrings:  1211
+  CStrings:  1214
 
Functions:
~ sub_1000b7010 : 120 -> 164
~ sub_1000b7088 -> sub_1000b70b4 : 20 -> 32
CStrings:
+ "preConfirmationClientHydration"
+ "preConfirmationEntityHydration"
+ "preConfirmationEntityQuery"
```

## textunderstandingd

> `/usr/libexec/textunderstandingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 176.3.0.1.0
-  __TEXT.__text: 0xb70
+  __TEXT.__text: 0xb34
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_stubs: 0x160
   __TEXT.__objc_methlist: 0x1ac

   __TEXT.__swift5_types: 0x8
   __TEXT.__cstring: 0x3a
   __TEXT.__oslogstring: 0x190
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__const: 0xb8
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
Functions:
~ sub_1000019d0 : 256 -> 244
~ sub_100001ad0 -> sub_100001ac4 : 92 -> 80
~ sub_100001bd8 -> sub_100001bc0 : 56 -> 44
~ sub_100001f9c -> sub_100001f78 : 92 -> 80
~ sub_10000206c -> sub_10000203c : 56 -> 44
```

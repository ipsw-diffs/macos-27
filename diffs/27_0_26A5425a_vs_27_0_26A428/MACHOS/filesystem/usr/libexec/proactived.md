## proactived

> `/usr/libexec/proactived`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 671.0.1.0.1
-  __TEXT.__text: 0x9e8
+  __TEXT.__text: 0x9ac
   __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__objc_methlist: 0x94

   __TEXT.__objc_methtype: 0x47
   __TEXT.__oslogstring: 0x286
   __TEXT.__cstring: 0xa8
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ sub_100000e18 : 72 -> 60
~ sub_1000011ec -> sub_1000011e0 : 28 -> 16
~ sub_100001208 -> sub_1000011f0 : 68 -> 56
~ sub_10000124c -> sub_100001228 : 160 -> 148
~ sub_10000156c -> sub_10000153c : 68 -> 56
```

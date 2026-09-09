## symptomsd-diag

> `/usr/libexec/symptomsd-diag`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 469.0.0.0.0
-  __TEXT.__text: 0xa44
+  __TEXT.__text: 0xa20
   __TEXT.__auth_stubs: 0x250
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x4c
   __TEXT.__oslogstring: 0x25d
   __TEXT.__objc_methname: 0x66
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x130
Functions:
~ sub_100000a20 : 68 -> 56
~ sub_100000a64 -> sub_100000a58 : 72 -> 60
~ sub_1000011f0 -> sub_1000011d8 : 28 -> 16
```

## mdfind

> `/usr/bin/mdfind`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 2459.405.0.0.0
-  __TEXT.__text: 0xc10
+  __TEXT.__text: 0xbe0
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__objc_stubs: 0x2a0
   __TEXT.__objc_methlist: 0x2c

   __TEXT.__objc_classname: 0xc
   __TEXT.__objc_methname: 0x1c5
   __TEXT.__objc_methtype: 0xb
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0x80
   __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000ac0 : 156 -> 144
~ sub_100000df0 -> sub_100000de4 : 48 -> 36
~ sub_100000e20 -> sub_100000e08 : 128 -> 116
~ sub_10000155c -> sub_100001538 : 264 -> 252
```

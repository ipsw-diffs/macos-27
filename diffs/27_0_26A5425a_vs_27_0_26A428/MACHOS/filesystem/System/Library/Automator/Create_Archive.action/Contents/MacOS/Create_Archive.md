## Create Archive

> `/System/Library/Automator/Create Archive.action/Contents/MacOS/Create Archive`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 406.0.0.0.0
-  __TEXT.__text: 0x1548
+  __TEXT.__text: 0x1518
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__objc_stubs: 0x900
   __TEXT.__objc_methlist: 0x38

   __TEXT.__objc_methname: 0x60b
   __TEXT.__objc_classname: 0xf
   __TEXT.__objc_methtype: 0x2b
-  __TEXT.__unwind_info: 0x70
+  __TEXT.__unwind_info: 0x78
   __DATA_CONST.__cfstring: 0x360
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_af0 : 360 -> 348
~ sub_c58 -> sub_c4c : 852 -> 840
~ sub_fac -> sub_f94 : 548 -> 536
~ sub_11d0 -> sub_11ac : 3688 -> 3676
```

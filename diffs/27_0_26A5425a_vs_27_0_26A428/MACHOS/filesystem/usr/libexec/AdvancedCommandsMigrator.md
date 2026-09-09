## AdvancedCommandsMigrator

> `/usr/libexec/AdvancedCommandsMigrator`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 6.1.89.0.0
-  __TEXT.__text: 0x9dc
+  __TEXT.__text: 0x9b8
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x360
   __TEXT.__objc_methlist: 0x50

   __TEXT.__oslogstring: 0x1a4
   __TEXT.__objc_classname: 0x9
   __TEXT.__objc_methtype: 0x67
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000dc8 : 80 -> 68
~ sub_100001260 -> sub_100001254 : 92 -> 80
~ sub_1000012d0 -> sub_1000012b8 : 28 -> 16
```

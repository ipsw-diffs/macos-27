## NVMeAgent

> `/usr/libexec/NVMeAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 877.0.7.0.0
-  __TEXT.__text: 0xdb8
+  __TEXT.__text: 0xd4c
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__objc_stubs: 0x4e0
   __TEXT.__objc_methlist: 0x154

   __TEXT.__objc_methname: 0x57d
   __TEXT.__objc_methtype: 0x141
   __TEXT.__oslogstring: 0xb7
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__cfstring: 0x280
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100000c00 : 584 -> 572
~ sub_100000e48 -> sub_100000e3c : 152 -> 140
~ sub_100000ee0 -> sub_100000ec8 : 184 -> 172
~ sub_100000f98 -> sub_100000f74 : 320 -> 308
~ sub_1000010d8 -> sub_1000010a8 : 60 -> 48
~ sub_100001114 -> sub_1000010d8 : 60 -> 48
~ sub_100001150 -> sub_100001108 : 48 -> 36
~ sub_100001820 -> sub_1000017cc : 92 -> 80
~ sub_100001894 -> sub_100001834 : 28 -> 16
```

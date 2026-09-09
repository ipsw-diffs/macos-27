## Memory Slot Utility

> `/System/Library/CoreServices/Memory Slot Utility.app/Contents/MacOS/Memory Slot Utility`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 172.0.0.0.0
-  __TEXT.__text: 0x1508
+  __TEXT.__text: 0x14e4
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__objc_stubs: 0x580
   __TEXT.__objc_methlist: 0x3ec

   __TEXT.__objc_classname: 0x2d
   __TEXT.__objc_methname: 0xa83
   __TEXT.__objc_methtype: 0x493
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__cfstring: 0x860
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100000e1c : 64 -> 52
~ sub_1000014f8 -> sub_1000014ec : 624 -> 612
~ sub_100001fec -> sub_100001fd4 : 72 -> 60
```

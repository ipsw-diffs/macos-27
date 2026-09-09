## MemorySlotNotification

> `/System/Library/CoreServices/MemorySlotNotification`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 92.0.0.0.0
-  __TEXT.__text: 0xa4c
+  __TEXT.__text: 0xa10
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__objc_stubs: 0x280
   __TEXT.__objc_methlist: 0x164

   __TEXT.__objc_methname: 0x407
   __TEXT.__objc_methtype: 0x190
   __TEXT.__oslogstring: 0x37
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0xc0
   __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100000c64 : 72 -> 60
~ sub_100000d48 -> sub_100000d3c : 272 -> 260
~ sub_100000e58 -> sub_100000e40 : 204 -> 192
~ sub_100001490 -> sub_10000146c : 220 -> 208
~ sub_10000156c -> sub_10000153c : 180 -> 168
```

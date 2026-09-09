## xip

> `/usr/bin/xip`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 883.0.0.0.0
-  __TEXT.__text: 0xcb0
+  __TEXT.__text: 0xc74
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__objc_stubs: 0x520
   __TEXT.__const: 0x40
   __TEXT.__gcc_except_tab: 0x90
   __TEXT.__cstring: 0x366
   __TEXT.__objc_methname: 0x39b
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_10000144c : 72 -> 60
~ sub_100001494 -> sub_100001488 : 80 -> 68
~ sub_1000014e4 -> sub_1000014cc : 68 -> 56
~ sub_100001528 -> sub_100001504 : 72 -> 60
~ sub_100001570 -> sub_100001540 : 32 -> 20
```

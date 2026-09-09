## afclip

> `/usr/bin/afclip`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x4c8c
+  __TEXT.__text: 0x4c08
   __TEXT.__auth_stubs: 0x350
   __TEXT.__gcc_except_tab: 0x260
   __TEXT.__const: 0x98
   __TEXT.__cstring: 0xdc4
   __TEXT.__oslogstring: 0x20
-  __TEXT.__unwind_info: 0x1b0
+  __TEXT.__unwind_info: 0x1d0
   __DATA_CONST.__const: 0x110
   __DATA_CONST.__auth_got: 0x1b0
   __DATA_CONST.__got: 0x48
Functions:
~ sub_100000acc : 848 -> 836
~ sub_100000f48 -> sub_100000f3c : 2016 -> 2032
~ sub_10000244c -> sub_100002450 : 132 -> 120
~ sub_1000026c0 -> sub_1000026b8 : 196 -> 192
~ sub_100002784 -> sub_100002778 : 424 -> 412
~ sub_100002b1c -> sub_100002b04 : 472 -> 460
~ sub_100002d54 -> sub_100002d30 : 116 -> 104
~ sub_100002dcc -> sub_100002d9c : 56 -> 44
~ sub_100003a20 -> sub_1000039e4 : 2804 -> 2756
~ sub_100005444 -> sub_1000053d8 : 44 -> 32
~ sub_100005474 -> sub_1000053fc : 56 -> 44
```

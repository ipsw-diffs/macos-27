## tidy

> `/usr/bin/tidy`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 21.0.0.0.0
-  __TEXT.__text: 0x1cd0
+  __TEXT.__text: 0x1c88
   __TEXT.__auth_stubs: 0x3b0
   __TEXT.__cstring: 0x1155
   __TEXT.__const: 0xd3
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x7b8
   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0x10
Functions:
~ sub_100001040 : 708 -> 696
~ sub_100001304 -> sub_1000012f8 : 300 -> 288
~ sub_100001430 -> sub_100001418 : 220 -> 208
~ sub_1000015dc -> sub_1000015b8 : 172 -> 160
~ sub_100001764 -> sub_100001734 : 332 -> 320
~ sub_100001ed8 -> sub_100001e9c : 76 -> 64
```

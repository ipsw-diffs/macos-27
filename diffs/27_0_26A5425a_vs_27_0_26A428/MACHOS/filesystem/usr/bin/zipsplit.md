## zipsplit

> `/usr/bin/zipsplit`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x906c
+  __TEXT.__text: 0x9004
   __TEXT.__auth_stubs: 0x370
   __TEXT.__cstring: 0x28eb
   __TEXT.__const: 0x110
-  __TEXT.__unwind_info: 0x148
+  __TEXT.__unwind_info: 0x178
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x1b8
   __DATA_CONST.__got: 0x18
Functions:
~ sub_1000008c8 : 128 -> 116
~ sub_100000948 -> sub_10000093c : 152 -> 140
~ sub_100001a7c -> sub_100001a64 : 168 -> 156
~ sub_100003b24 -> sub_100003b00 : 1448 -> 1452
~ sub_1000044c4 -> sub_1000044a4 : 1312 -> 1300
~ sub_1000049e4 -> sub_1000049b8 : 852 -> 832
~ sub_100006d98 -> sub_100006d58 : 312 -> 300
~ sub_10000807c -> sub_100008030 : 2804 -> 2800
~ sub_100008b70 -> sub_100008b20 : 1088 -> 1064
```

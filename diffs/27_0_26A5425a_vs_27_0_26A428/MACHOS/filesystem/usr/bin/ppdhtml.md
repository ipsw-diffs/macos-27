## ppdhtml

> `/usr/bin/ppdhtml`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 532.0.0.0.0
-  __TEXT.__text: 0xd548
+  __TEXT.__text: 0xd3b4
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__gcc_except_tab: 0x9c4
   __TEXT.__cstring: 0x2fb0
   __TEXT.__const: 0xf9
-  __TEXT.__unwind_info: 0x568
+  __TEXT.__unwind_info: 0x578
   __DATA_CONST.__const: 0x480
   __DATA_CONST.__auth_got: 0x1f8
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000e00 : 144 -> 132
~ sub_100000ea8 -> sub_100000e9c : 40 -> 28
~ sub_100000fbc -> sub_100000fa4 : 148 -> 136
~ sub_10000117c -> sub_100001158 : 116 -> 104
~ sub_1000011f4 -> sub_1000011c4 : 40 -> 28
~ sub_100001608 -> sub_1000015cc : 1632 -> 1636
~ sub_100001c6c -> sub_100001c34 : 108 -> 96
~ sub_100001cdc -> sub_100001c98 : 40 -> 28
~ sub_100002848 -> sub_1000027f8 : 108 -> 96
~ sub_1000028b8 -> sub_10000285c : 40 -> 28
~ sub_1000029fc -> sub_100002994 : 116 -> 104
~ sub_100002a74 -> sub_100002a00 : 40 -> 28
~ sub_100002df4 -> sub_100002d74 : 244 -> 232
~ sub_100002eec -> sub_100002e60 : 40 -> 28
~ sub_100005ee8 -> sub_100005e50 : 100 -> 88
~ sub_100005f50 -> sub_100005eac : 40 -> 28
~ sub_1000060a4 -> sub_100005ff4 : 116 -> 104
~ sub_10000611c -> sub_100006060 : 40 -> 28
~ sub_10000632c -> sub_100006264 : 120 -> 108
~ sub_1000063a8 -> sub_1000062d4 : 40 -> 28
~ sub_1000065c8 -> sub_1000064e8 : 116 -> 104
~ sub_100006640 -> sub_100006554 : 40 -> 28
~ sub_10000672c -> sub_100006634 : 100 -> 88
~ sub_100006794 -> sub_100006690 : 40 -> 28
~ sub_10000699c -> sub_10000688c : 120 -> 108
~ sub_100006a18 -> sub_1000068fc : 40 -> 28
~ sub_100006be4 -> sub_100006abc : 100 -> 88
~ sub_100006c4c -> sub_100006b18 : 40 -> 28
~ sub_1000070b4 -> sub_100006f74 : 132 -> 120
~ sub_10000713c -> sub_100006ff0 : 40 -> 28
~ sub_100007164 -> sub_10000700c : 172 -> 160
~ sub_10000dbd0 -> sub_10000da6c : 92 -> 80
~ sub_10000dc30 -> sub_10000dac0 : 40 -> 28
~ sub_10000dd1c -> sub_10000dba0 : 100 -> 88
~ sub_10000dd84 -> sub_10000dbfc : 40 -> 28
```

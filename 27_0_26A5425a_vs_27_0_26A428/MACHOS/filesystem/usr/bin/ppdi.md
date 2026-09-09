## ppdi

> `/usr/bin/ppdi`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 532.0.0.0.0
-  __TEXT.__text: 0xe084
+  __TEXT.__text: 0xdee4
   __TEXT.__auth_stubs: 0x410
   __TEXT.__gcc_except_tab: 0xab4
   __TEXT.__cstring: 0x2f91
   __TEXT.__const: 0xf9
-  __TEXT.__unwind_info: 0x580
+  __TEXT.__unwind_info: 0x590
   __DATA_CONST.__const: 0x480
   __DATA_CONST.__auth_got: 0x210
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000b80 : 144 -> 132
~ sub_100000c28 -> sub_100000c1c : 40 -> 28
~ sub_100000d3c -> sub_100000d24 : 148 -> 136
~ sub_100000efc -> sub_100000ed8 : 116 -> 104
~ sub_100000f74 -> sub_100000f44 : 40 -> 28
~ sub_100001388 -> sub_10000134c : 1632 -> 1636
~ sub_1000019ec -> sub_1000019b4 : 108 -> 96
~ sub_100001a5c -> sub_100001a18 : 40 -> 28
~ sub_1000025c8 -> sub_100002578 : 108 -> 96
~ sub_100002638 -> sub_1000025dc : 40 -> 28
~ sub_10000277c -> sub_100002714 : 116 -> 104
~ sub_1000027f4 -> sub_100002780 : 40 -> 28
~ sub_100002b74 -> sub_100002af4 : 244 -> 232
~ sub_100002c6c -> sub_100002be0 : 40 -> 28
~ sub_100005c68 -> sub_100005bd0 : 100 -> 88
~ sub_100005cd0 -> sub_100005c2c : 40 -> 28
~ sub_100005e24 -> sub_100005d74 : 116 -> 104
~ sub_100005e9c -> sub_100005de0 : 40 -> 28
~ sub_1000060ac -> sub_100005fe4 : 120 -> 108
~ sub_100006128 -> sub_100006054 : 40 -> 28
~ sub_100006f0c -> sub_100006e2c : 108 -> 96
~ sub_100007104 -> sub_100007018 : 116 -> 104
~ sub_10000717c -> sub_100007084 : 40 -> 28
~ sub_100007268 -> sub_100007164 : 100 -> 88
~ sub_1000072d0 -> sub_1000071c0 : 40 -> 28
~ sub_1000074d8 -> sub_1000073bc : 120 -> 108
~ sub_100007554 -> sub_10000742c : 40 -> 28
~ sub_100007720 -> sub_1000075ec : 100 -> 88
~ sub_100007788 -> sub_100007648 : 40 -> 28
~ sub_100007bf0 -> sub_100007aa4 : 132 -> 120
~ sub_100007c78 -> sub_100007b20 : 40 -> 28
~ sub_100007ca0 -> sub_100007b3c : 172 -> 160
~ sub_10000e70c -> sub_10000e59c : 92 -> 80
~ sub_10000e76c -> sub_10000e5f0 : 40 -> 28
~ sub_10000e858 -> sub_10000e6d0 : 100 -> 88
~ sub_10000e8c0 -> sub_10000e72c : 40 -> 28
```

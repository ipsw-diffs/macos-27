## locale

> `/usr/bin/locale`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x7034
+  __TEXT.__text: 0x6ed8
   __TEXT.__auth_stubs: 0x340
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x101
   __TEXT.__gcc_except_tab: 0x940
   __TEXT.__cstring: 0x31a
-  __TEXT.__unwind_info: 0x250
+  __TEXT.__unwind_info: 0x290
   __DATA_CONST.__const: 0x138
   __DATA_CONST.__auth_got: 0x1a8
   __DATA_CONST.__got: 0x70
Functions:
~ sub_100001aec : 432 -> 392
~ sub_100001c9c -> sub_100001c74 : 360 -> 320
~ sub_100001e04 -> sub_100001db4 : 288 -> 248
~ sub_100003eac -> sub_100003e34 : 368 -> 328
~ sub_100005bac -> sub_100005b0c : 804 -> 764
~ sub_100005f20 -> sub_100005e58 : 216 -> 204
~ sub_100005ffc -> sub_100005f28 : 40 -> 28
~ sub_100006024 -> sub_100005f44 : 68 -> 56
~ sub_100006104 -> sub_100006018 : 40 -> 28
~ sub_100006380 -> sub_100006288 : 664 -> 624
~ sub_1000066d4 -> sub_1000065b4 : 264 -> 260
~ sub_1000068b8 -> sub_100006794 : 84 -> 72
~ sub_100006db8 -> sub_100006c88 : 40 -> 28
~ sub_1000070b0 -> sub_100006f74 : 112 -> 108
~ sub_1000073f8 -> sub_1000072b8 : 88 -> 76
~ sub_100007450 -> sub_100007304 : 196 -> 192
~ sub_1000075f8 -> sub_1000074a8 : 144 -> 132
```

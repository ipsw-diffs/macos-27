## ed

> `/bin/ed`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0x7f70
+  __TEXT.__text: 0x7f50
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__const: 0x86
   __TEXT.__cstring: 0x495
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x180
   __DATA_CONST.__auth_got: 0x1d0
   __DATA_CONST.__got: 0x38
   __DATA.__data: 0x30
Functions:
~ sub_100001074 : 176 -> 164
~ sub_1000030f0 -> sub_1000030e4 : 220 -> 212
~ sub_1000031cc -> sub_1000031b8 : 7008 -> 7004
~ sub_100005410 -> sub_1000053f8 : 152 -> 140
~ sub_100006318 -> sub_1000062f4 : 408 -> 404
~ sub_100006d00 -> sub_100006cd8 : 608 -> 596
~ sub_100007c78 -> sub_100007c44 : 1100 -> 1104
~ sub_1000082cc -> sub_10000829c : 592 -> 608
```

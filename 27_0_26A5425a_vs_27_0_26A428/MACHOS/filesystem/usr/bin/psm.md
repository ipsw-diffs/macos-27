## psm

> `/usr/bin/psm`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 2383.1.1.0.0
-  __TEXT.__text: 0xb7b8
+  __TEXT.__text: 0xb644
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__const: 0x1274
   __TEXT.__cstring: 0x28d5
-  __TEXT.__unwind_info: 0x300
+  __TEXT.__unwind_info: 0x418
   __DATA_CONST.__const: 0x1768
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__auth_got: 0x3f8
Functions:
~ sub_100000960 : 48 -> 52
~ sub_100000f14 -> sub_100000f18 : 132 -> 120
~ sub_100001274 -> sub_10000126c : 144 -> 136
~ sub_100001358 -> sub_100001348 : 176 -> 164
~ sub_100001728 -> sub_10000170c : 24 -> 12
~ sub_10000174c -> sub_100001724 : 12 -> 24
~ sub_100001758 -> sub_10000173c : 36 -> 24
~ sub_100002fc0 -> sub_100002f98 : 28 -> 16
~ sub_100002fdc -> sub_100002fa8 : 32 -> 20
~ sub_100003010 -> sub_100002fd0 : 32 -> 20
~ sub_10000304c -> sub_100003000 : 28 -> 16
~ sub_100003068 -> sub_100003010 : 28 -> 16
~ sub_100003108 -> sub_1000030a4 : 20 -> 12
~ sub_100003134 -> sub_1000030c8 : 12 -> 20
~ sub_100003140 -> sub_1000030dc : 32 -> 20
~ sub_100003770 -> sub_100003700 : 172 -> 160
~ sub_100003bc8 -> sub_100003b4c : 168 -> 156
~ sub_100003c90 -> sub_100003c08 : 32 -> 20
~ sub_100003f8c -> sub_100003ef8 : 32 -> 20
~ sub_1000046d8 -> sub_100004638 : 136 -> 132
~ sub_100004760 -> sub_1000046bc : 144 -> 132
~ sub_1000048b0 -> sub_100004800 : 52 -> 40
~ sub_1000048e4 -> sub_100004828 : 32 -> 20
~ sub_100004914 -> sub_10000484c : 40 -> 28
~ sub_10000497c -> sub_1000048a8 : 32 -> 20
~ sub_1000049bc -> sub_1000048dc : 36 -> 24
~ sub_1000049e0 -> sub_1000048f4 : 28 -> 16
~ sub_1000049fc -> sub_100004904 : 36 -> 24
~ sub_100004a44 -> sub_100004940 : 28 -> 16
~ sub_100004a78 -> sub_100004968 : 32 -> 20
~ sub_100004a98 -> sub_10000497c : 32 -> 20
~ sub_100004afc -> sub_1000049d4 : 28 -> 16
~ sub_100004b6c -> sub_100004a38 : 28 -> 16
~ sub_100004b88 -> sub_100004a48 : 28 -> 16
~ sub_100004ba4 -> sub_100004a58 : 28 -> 16
~ sub_100004c38 -> sub_100004ae0 : 32 -> 20
~ sub_100005ea0 -> sub_100005d3c : 32 -> 20
~ sub_10000b978 -> sub_10000b808 : 296 -> 292
```

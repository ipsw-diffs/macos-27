## odproxyd

> `/usr/libexec/odproxyd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x33fc
+  __TEXT.__text: 0x32dc
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x4b6
-  __TEXT.__unwind_info: 0x140
+  __TEXT.__unwind_info: 0x188
   __DATA_CONST.__const: 0x580
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__auth_got: 0x3f8
Functions:
~ sub_10000099c : 80 -> 68
~ sub_100000b24 -> sub_100000b18 : 80 -> 68
~ sub_100000e08 -> sub_100000df0 : 92 -> 80
~ sub_100001570 -> sub_10000154c : 84 -> 72
~ sub_1000015e0 -> sub_1000015b0 : 128 -> 116
~ sub_1000016c0 -> sub_100001684 : 236 -> 224
~ sub_1000018f4 -> sub_1000018ac : 84 -> 72
~ sub_10000226c -> sub_100002218 : 112 -> 100
~ sub_100002308 -> sub_1000022a8 : 160 -> 148
~ sub_1000023bc -> sub_100002350 : 148 -> 136
~ sub_100002574 -> sub_1000024fc : 60 -> 48
~ sub_1000025b0 -> sub_10000252c : 104 -> 92
~ sub_100002618 -> sub_100002588 : 448 -> 400
~ sub_100002b2c -> sub_100002a6c : 80 -> 68
~ sub_100002b7c -> sub_100002ab0 : 68 -> 56
~ sub_100002d1c -> sub_100002c44 : 420 -> 408
~ sub_100003070 -> sub_100002f8c : 364 -> 352
~ sub_10000335c -> sub_10000326c : 112 -> 100
~ sub_10000356c -> sub_100003470 : 80 -> 68
~ sub_1000035e8 -> sub_1000034e0 : 144 -> 132
~ sub_1000036b4 -> sub_1000035a0 : 144 -> 132
```

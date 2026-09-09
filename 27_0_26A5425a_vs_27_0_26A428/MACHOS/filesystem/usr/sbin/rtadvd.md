## rtadvd

> `/usr/sbin/rtadvd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 557.0.0.0.0
-  __TEXT.__text: 0x7adc
+  __TEXT.__text: 0x7a90
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__cstring: 0x25b3
   __TEXT.__oslogstring: 0x1e
   __TEXT.__const: 0xc0
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x1e8
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__auth_got: 0x1f0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000f60 : 5792 -> 5788
~ sub_100002600 -> sub_1000025fc : 80 -> 68
~ sub_100002984 -> sub_100002974 : 1808 -> 1804
~ sub_1000034b0 -> sub_10000349c : 40 -> 28
~ sub_1000034d8 -> sub_1000034b8 : 40 -> 28
~ sub_100003500 -> sub_1000034d4 : 32 -> 20
~ sub_100004458 -> sub_100004420 : 200 -> 188
~ sub_1000072e0 -> sub_10000729c : 156 -> 148
```

## lsof

> `/usr/sbin/lsof`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 76.0.0.0.0
-  __TEXT.__text: 0x1200c
+  __TEXT.__text: 0x11fb8
   __TEXT.__auth_stubs: 0x5e0
   __TEXT.__cstring: 0x3491
   __TEXT.__const: 0x44
-  __TEXT.__unwind_info: 0x1c8
+  __TEXT.__unwind_info: 0x230
   __DATA_CONST.__const: 0x2f8
   __DATA_CONST.__auth_got: 0x2f0
   __DATA_CONST.__got: 0x38
Functions:
~ sub_100000724 : 2224 -> 2228
~ sub_1000015d0 -> sub_1000015d4 : 164 -> 152
~ sub_100001674 -> sub_10000166c : 396 -> 372
~ sub_1000028f8 -> sub_1000028d8 : 5368 -> 5356
~ sub_100004f4c -> sub_100004f20 : 1380 -> 1384
~ sub_100007e1c -> sub_100007df4 : 9660 -> 9652
~ sub_10000a564 -> sub_10000a534 : 440 -> 432
~ sub_10000b14c -> sub_10000b114 : 160 -> 148
~ sub_10000bf3c -> sub_10000bef8 : 160 -> 148
~ sub_10000c2e0 -> sub_10000c290 : 744 -> 756
~ sub_10000c5c8 -> sub_10000c584 : 2956 -> 2952
~ sub_100011fd8 -> sub_100011f90 : 1724 -> 1712
```

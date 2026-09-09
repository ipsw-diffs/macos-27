## zipcloak

> `/usr/bin/zipcloak`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x91b0
+  __TEXT.__text: 0x9154
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__cstring: 0x2a9a
   __TEXT.__const: 0x910
-  __TEXT.__unwind_info: 0x150
+  __TEXT.__unwind_info: 0x188
   __DATA_CONST.__const: 0x98
   __DATA_CONST.__auth_got: 0x1f0
   __DATA_CONST.__got: 0x20
Functions:
~ sub_100000874 : 128 -> 116
~ sub_1000008f4 -> sub_1000008e8 : 152 -> 140
~ sub_1000032b0 -> sub_100003298 : 1448 -> 1452
~ sub_100003c50 -> sub_100003c3c : 1312 -> 1300
~ sub_100004170 -> sub_100004150 : 852 -> 832
~ sub_100006524 -> sub_1000064f0 : 312 -> 300
~ sub_100007808 -> sub_1000077c8 : 2804 -> 2800
~ sub_1000082fc -> sub_1000082b8 : 1088 -> 1064
```

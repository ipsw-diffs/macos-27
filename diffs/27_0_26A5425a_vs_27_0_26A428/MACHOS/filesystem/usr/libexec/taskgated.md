## taskgated

> `/usr/libexec/taskgated`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 55186.0.0.0.0
-  __TEXT.__text: 0x5550
+  __TEXT.__text: 0x5460
   __TEXT.__auth_stubs: 0x880
   __TEXT.__const: 0x218
   __TEXT.__gcc_except_tab: 0x57c
   __TEXT.__oslogstring: 0x74d
   __TEXT.__cstring: 0x34e
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x330
+  __TEXT.__unwind_info: 0x3d0
   __DATA_CONST.__const: 0x358
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x448
Functions:
~ sub_100001048 : 104 -> 92
~ sub_100002b14 -> sub_100002b08 : 56 -> 44
~ sub_100002b88 -> sub_100002b70 : 92 -> 80
~ sub_100002be4 -> sub_100002bc0 : 68 -> 56
~ sub_100002cc0 -> sub_100002c90 : 28 -> 16
~ sub_100002cf0 -> sub_100002cb4 : 32 -> 20
~ sub_100002d1c -> sub_100002cd4 : 32 -> 20
~ sub_1000030dc -> sub_100003088 : 1532 -> 1484
~ sub_1000036d8 -> sub_100003654 : 224 -> 212
~ sub_100003c2c -> sub_100003b9c : 72 -> 60
~ sub_1000044a8 -> sub_10000440c : 56 -> 44
~ sub_1000044e0 -> sub_100004438 : 56 -> 44
~ sub_100004518 -> sub_100004464 : 56 -> 44
~ sub_100004550 -> sub_100004490 : 56 -> 44
~ sub_1000046cc -> sub_100004600 : 580 -> 568
~ sub_100005300 -> sub_100005228 : 76 -> 64
~ sub_100005794 -> sub_1000056b0 : 120 -> 108
```

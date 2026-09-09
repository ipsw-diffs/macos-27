## snmptable

> `/usr/bin/snmptable`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 1726.0.0.0.0
-  __TEXT.__text: 0x1fc8
+  __TEXT.__text: 0x1fa0
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__cstring: 0x52e
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__auth_got: 0x168
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x10
Functions:
~ sub_100000878 : 400 -> 388
~ sub_100000a08 -> sub_1000009fc : 96 -> 100
~ sub_100000a68 -> sub_100000a60 : 780 -> 784
~ sub_100000f78 -> sub_100000f74 : 928 -> 924
~ sub_100001fe8 -> sub_100001fe0 : 1304 -> 1308
~ sub_100002524 -> sub_100002520 : 36 -> 24
~ sub_100002548 -> sub_100002538 : 32 -> 20
~ sub_100002568 -> sub_10000254c : 24 -> 12
```

## dd

> `/bin/dd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x2b2c
+  __TEXT.__text: 0x2ab8
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x6c6
   __TEXT.__cstring: 0x650
-  __TEXT.__unwind_info: 0x118
+  __TEXT.__unwind_info: 0x1b8
   __DATA_CONST.__const: 0x540
   __DATA_CONST.__auth_got: 0x190
   __DATA_CONST.__got: 0x10
Functions:
~ sub_10000096c : 36 -> 24
~ sub_100000990 -> sub_100000984 : 32 -> 20
~ sub_100000d58 -> sub_100000d40 : 2720 -> 2716
~ sub_100001b60 -> sub_100001b44 : 32 -> 20
~ sub_100001c30 -> sub_100001c08 : 600 -> 596
~ sub_100002b4c -> sub_100002b20 : 40 -> 28
~ sub_100002b74 -> sub_100002b3c : 40 -> 28
~ sub_100002b9c -> sub_100002b58 : 40 -> 28
~ sub_100002bc4 -> sub_100002b74 : 36 -> 24
~ sub_100002be8 -> sub_100002b8c : 32 -> 20
~ sub_100002c24 -> sub_100002bbc : 72 -> 60
```

## crontab

> `/usr/bin/crontab`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 52.0.0.0.0
-  __TEXT.__text: 0x2ff8
+  __TEXT.__text: 0x2fb0
   __TEXT.__auth_stubs: 0x550
   __TEXT.__const: 0x82
   __TEXT.__cstring: 0xb03
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__auth_got: 0x2a8
   __DATA_CONST.__got: 0x38
Functions:
~ sub_1000017b4 : 76 -> 64
~ sub_100002640 -> sub_100002634 : 80 -> 68
~ sub_1000030dc -> sub_1000030c4 : 180 -> 168
~ sub_10000343c -> sub_100003418 : 52 -> 40
~ sub_100003470 -> sub_100003440 : 32 -> 20
~ sub_100003490 -> sub_100003454 : 32 -> 20
```

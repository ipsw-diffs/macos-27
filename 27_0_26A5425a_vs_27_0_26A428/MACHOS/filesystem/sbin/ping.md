## ping

> `/sbin/ping`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 755.0.0.0.0
-  __TEXT.__text: 0x3a84
+  __TEXT.__text: 0x3a60
   __TEXT.__auth_stubs: 0x3b0
   __TEXT.__const: 0x30
   __TEXT.__cstring: 0x123b
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0x38
Functions:
~ sub_1000006c8 : 8028 -> 8016
~ sub_10000270c -> sub_100002700 : 428 -> 432
~ sub_100002d30 -> sub_100002d28 : 256 -> 244
~ sub_100002e30 -> sub_100002e1c : 2772 -> 2756
```

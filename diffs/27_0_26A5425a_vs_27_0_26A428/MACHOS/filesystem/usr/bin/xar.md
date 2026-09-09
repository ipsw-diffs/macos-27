## xar

> `/usr/bin/xar`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 514.0.1.0.0
-  __TEXT.__text: 0x29ec
+  __TEXT.__text: 0x29a4
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__const: 0x30
   __TEXT.__cstring: 0x14ff
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__const: 0x330
   __DATA_CONST.__auth_got: 0x260
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100001f60 : 1576 -> 1564
~ sub_100002a60 -> sub_100002a54 : 388 -> 376
~ sub_100002be4 -> sub_100002bcc : 44 -> 32
~ sub_100002c10 -> sub_100002bec : 40 -> 28
~ sub_100002c38 -> sub_100002c08 : 32 -> 20
~ sub_100002c58 -> sub_100002c1c : 44 -> 32
```

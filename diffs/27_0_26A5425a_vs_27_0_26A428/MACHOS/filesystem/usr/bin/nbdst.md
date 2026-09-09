## nbdst

> `/usr/bin/nbdst`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`

```diff

 704.0.0.0.0
-  __TEXT.__text: 0xd70
+  __TEXT.__text: 0xd4c
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__cstring: 0x712
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__auth_got: 0x178
   __DATA_CONST.__got: 0x40
Functions:
~ sub_100000d10 : 200 -> 188
~ sub_100000dd8 -> sub_100000dcc : 44 -> 32
~ sub_100000ef8 -> sub_100000ee0 : 348 -> 336
```

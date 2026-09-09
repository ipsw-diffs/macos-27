## getconf

> `/usr/bin/getconf`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0xf14
+  __TEXT.__text: 0xed8
   __TEXT.__auth_stubs: 0x140
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x1448
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x14a8
   __DATA_CONST.__auth_got: 0xa0
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000a08 : 156 -> 144
~ sub_100000aa4 -> sub_100000a98 : 364 -> 352
~ sub_100000c10 -> sub_100000bf8 : 192 -> 180
~ sub_100000cd0 -> sub_100000cac : 228 -> 216
~ sub_100000db4 -> sub_100000d84 : 28 -> 16
```

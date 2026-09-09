## cmp

> `/usr/bin/cmp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 77.0.0.0.0
-  __TEXT.__text: 0xff8
+  __TEXT.__text: 0xfd0
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__const: 0x62
   __TEXT.__cstring: 0x27d
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__auth_got: 0xf0
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000e2c : 960 -> 940
~ sub_100001284 -> sub_100001270 : 32 -> 20
~ sub_100001358 -> sub_100001338 : 552 -> 544
```

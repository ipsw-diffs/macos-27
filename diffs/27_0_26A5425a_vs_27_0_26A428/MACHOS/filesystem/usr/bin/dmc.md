## dmc

> `/usr/bin/dmc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 13.0.0.0.0
-  __TEXT.__text: 0x1030
+  __TEXT.__text: 0x1018
   __TEXT.__auth_stubs: 0x210
   __TEXT.__cstring: 0x5e5
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__auth_got: 0x108
   __DATA_CONST.__got: 0x48
Functions:
~ sub_100001118 : 84 -> 72
~ sub_10000116c -> sub_100001160 : 48 -> 36
```

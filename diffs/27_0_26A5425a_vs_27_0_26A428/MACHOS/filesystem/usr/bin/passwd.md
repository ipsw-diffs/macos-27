## passwd

> `/usr/bin/passwd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x1a80
+  __TEXT.__text: 0x1a5c
   __TEXT.__auth_stubs: 0x530
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x68c
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x298
   __DATA_CONST.__got: 0x68
Functions:
~ sub_1000012cc : 32 -> 20
~ sub_1000016e8 -> sub_1000016dc : 32 -> 20
~ sub_100001b4c -> sub_100001b34 : 212 -> 200
```

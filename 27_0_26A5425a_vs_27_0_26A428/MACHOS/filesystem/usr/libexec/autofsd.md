## autofsd

> `/usr/libexec/autofsd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

 328.0.0.0.0
-  __TEXT.__text: 0x3f0
+  __TEXT.__text: 0x3cc
   __TEXT.__auth_stubs: 0x150
   __TEXT.__cstring: 0x210
   __TEXT.__unwind_info: 0x70
Functions:
~ sub_10000092c : 72 -> 60
~ sub_100000acc -> sub_100000ac0 : 72 -> 60
~ sub_100000b14 -> sub_100000afc : 68 -> 56
```

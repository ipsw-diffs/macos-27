## install

> `/usr/bin/install`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x28c0
+  __TEXT.__text: 0x288c
   __TEXT.__auth_stubs: 0x500
   __TEXT.__const: 0x3e
   __TEXT.__cstring: 0x78b
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x280
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_10000247c : 876 -> 860
~ sub_100002a94 -> sub_100002a84 : 32 -> 20
~ sub_100002ab4 -> sub_100002a98 : 24 -> 12
~ sub_100002acc -> sub_100002aa4 : 36 -> 24
```

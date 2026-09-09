## nc

> `/usr/bin/nc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 56.0.0.0.0
-  __TEXT.__text: 0x47fc
+  __TEXT.__text: 0x47cc
   __TEXT.__auth_stubs: 0x440
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x24c4
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x1a0
   __DATA_CONST.__const: 0x680
   __DATA_CONST.__auth_got: 0x220
   __DATA_CONST.__got: 0x40
Functions:
~ sub_1000027c4 : 508 -> 496
~ sub_100003b84 -> sub_100003b78 : 264 -> 252
~ sub_100003ef0 -> sub_100003ed8 : 32 -> 20
~ sub_100003f10 -> sub_100003eec : 28 -> 16
```

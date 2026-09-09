## dseditgroup

> `/usr/sbin/dseditgroup`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 191.0.0.0.0
-  __TEXT.__text: 0x259c
+  __TEXT.__text: 0x2560
   __TEXT.__auth_stubs: 0x4a0
   __TEXT.__const: 0x50
   __TEXT.__cstring: 0xed1
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0x50
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x250
Functions:
~ sub_100002740 : 96 -> 84
~ sub_1000027a0 -> sub_100002794 : 172 -> 160
~ sub_100002a30 -> sub_100002a18 : 80 -> 68
~ sub_100002a80 -> sub_100002a5c : 68 -> 56
~ sub_100002ac4 -> sub_100002a94 : 112 -> 100
```

## pwpolicy

> `/usr/bin/pwpolicy`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 191.0.0.0.0
-  __TEXT.__text: 0x3874
+  __TEXT.__text: 0x3820
   __TEXT.__auth_stubs: 0x790
   __TEXT.__const: 0x50
   __TEXT.__cstring: 0x12e0
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0x300
   __DATA_CONST.__cfstring: 0x600
   __DATA_CONST.__auth_got: 0x3c8
Functions:
~ sub_1000026d0 : 96 -> 84
~ sub_100002730 -> sub_100002724 : 80 -> 68
~ sub_100003ab4 -> sub_100003a9c : 312 -> 300
~ sub_100003d18 -> sub_100003cf4 : 28 -> 16
~ sub_100003d34 -> sub_100003d04 : 44 -> 32
~ sub_100003d60 -> sub_100003d24 : 24 -> 12
~ sub_100003d78 -> sub_100003d30 : 36 -> 24
```

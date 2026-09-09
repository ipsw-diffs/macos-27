## ps

> `/bin/ps`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x43a0
+  __TEXT.__text: 0x4358
   __TEXT.__auth_stubs: 0x460
   __TEXT.__const: 0x130
   __TEXT.__cstring: 0x7df
-  __TEXT.__unwind_info: 0x120
+  __TEXT.__unwind_info: 0x198
   __DATA_CONST.__const: 0x20
   __DATA_CONST.__auth_got: 0x230
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000ab8 : 248 -> 236
~ sub_100000bb0 -> sub_100000ba4 : 1044 -> 1032
~ sub_100000fc4 -> sub_100000fac : 248 -> 236
~ sub_100001c70 -> sub_100001c4c : 92 -> 80
~ sub_1000026b8 -> sub_100002688 : 96 -> 84
~ sub_1000043b4 -> sub_100004378 : 28 -> 16
```

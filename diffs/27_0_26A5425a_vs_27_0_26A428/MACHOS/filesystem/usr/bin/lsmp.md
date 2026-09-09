## lsmp

> `/usr/bin/lsmp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x4804
+  __TEXT.__text: 0x47dc
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__const: 0x38
   __TEXT.__cstring: 0x1434
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x278
   __DATA_CONST.__auth_got: 0x170
   __DATA_CONST.__got: 0x20
Functions:
~ sub_100000d28 : 28 -> 16
~ sub_100000d68 -> sub_100000d5c : 748 -> 744
~ sub_100003dd0 -> sub_100003dc0 : 140 -> 128
~ sub_100003e5c -> sub_100003e40 : 412 -> 400
```

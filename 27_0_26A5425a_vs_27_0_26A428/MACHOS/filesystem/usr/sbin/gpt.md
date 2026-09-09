## gpt

> `/usr/sbin/gpt`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 24.0.0.0.0
-  __TEXT.__text: 0x3720
+  __TEXT.__text: 0x3700
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__const: 0x72e
   __TEXT.__cstring: 0x9ac
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x138
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__auth_got: 0x170
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000b64 : 1364 -> 1352
~ sub_100001fbc -> sub_100001fb0 : 672 -> 660
~ sub_100002b4c -> sub_100002b34 : 176 -> 168
```

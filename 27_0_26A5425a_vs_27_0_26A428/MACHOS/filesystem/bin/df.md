## df

> `/bin/df`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x1754
+  __TEXT.__text: 0x1720
   __TEXT.__auth_stubs: 0x270
   __TEXT.__const: 0x52
   __TEXT.__cstring: 0x48f
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0x90
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__auth_got: 0x138
   __DATA_CONST.__got: 0x10
Functions:
~ sub_1000006a8 : 3124 -> 3076
~ sub_1000015c8 -> sub_100001598 : 1720 -> 1716
```

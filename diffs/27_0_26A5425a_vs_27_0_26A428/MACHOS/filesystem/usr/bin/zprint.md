## zprint

> `/usr/bin/zprint`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x26f0
+  __TEXT.__text: 0x26b8
   __TEXT.__auth_stubs: 0x240
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0xfcd
Functions:
~ sub_100000840 : 3724 -> 3704
~ sub_1000028f8 -> sub_1000028e4 : 204 -> 192
~ sub_100002ec8 -> sub_100002ea8 : 36 -> 24
~ sub_100002eec -> sub_100002ec0 : 32 -> 20
```

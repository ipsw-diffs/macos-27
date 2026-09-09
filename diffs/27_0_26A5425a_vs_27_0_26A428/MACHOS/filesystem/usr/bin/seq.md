## seq

> `/usr/bin/seq`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 334.0.0.0.0
-  __TEXT.__text: 0xbb0
+  __TEXT.__text: 0xba8
   __TEXT.__auth_stubs: 0x150
   __TEXT.__const: 0x42
   __TEXT.__cstring: 0x148
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0x88
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__auth_got: 0xa8
   __DATA_CONST.__got: 0x28
Functions:
~ sub_100000628 : 1664 -> 1656
```

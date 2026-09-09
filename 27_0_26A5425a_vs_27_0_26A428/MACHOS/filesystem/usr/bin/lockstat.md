## lockstat

> `/usr/bin/lockstat`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 416.0.3.0.0
-  __TEXT.__text: 0x3490
+  __TEXT.__text: 0x3480
   __TEXT.__auth_stubs: 0x430
   __TEXT.__const: 0x8
   __TEXT.__cstring: 0x137d
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__auth_got: 0x218
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x3488
Functions:
~ _lockstat_mergesort : 320 -> 316
~ _addr_to_sym : 172 -> 160
```

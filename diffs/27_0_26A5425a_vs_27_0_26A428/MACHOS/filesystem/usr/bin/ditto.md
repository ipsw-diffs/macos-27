## ditto

> `/usr/bin/ditto`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 279.2.0.0.0
-  __TEXT.__text: 0x2830
+  __TEXT.__text: 0x2808
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__cstring: 0x1f74
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__cfstring: 0x3c0
   __DATA_CONST.__auth_got: 0x260
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000748 : 5748 -> 5768
~ sub_100001e9c -> sub_100001eb0 : 168 -> 156
~ sub_10000210c -> sub_100002114 : 296 -> 284
~ sub_10000236c -> sub_100002368 : 1036 -> 1012
~ sub_100002778 -> sub_10000275c : 564 -> 552
```

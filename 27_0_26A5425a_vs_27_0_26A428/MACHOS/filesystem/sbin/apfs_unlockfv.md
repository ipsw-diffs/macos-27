## apfs_unlockfv

> `/sbin/apfs_unlockfv`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 3288.1.3.0.0
-  __TEXT.__text: 0x33c8
+  __TEXT.__text: 0x3380
   __TEXT.__auth_stubs: 0x2b0
   __TEXT.__cstring: 0xbbc
   __TEXT.__const: 0x31
   __TEXT.__oslogstring: 0x125
-  __TEXT.__unwind_info: 0x120
+  __TEXT.__unwind_info: 0x170
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x158
Functions:
~ sub_1000011e0 : 84 -> 72
~ sub_1000015a8 -> sub_10000159c : 32 -> 20
~ sub_1000016c8 -> sub_1000016b0 : 28 -> 16
~ sub_1000016f4 -> sub_1000016d0 : 28 -> 16
~ sub_100001ec0 -> sub_100001e90 : 28 -> 16
~ sub_100001f3c -> sub_100001f00 : 32 -> 20
```

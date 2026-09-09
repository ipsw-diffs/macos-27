## nvram

> `/usr/sbin/nvram`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 1071.0.1.0.0
-  __TEXT.__text: 0x21b4
+  __TEXT.__text: 0x2170
   __TEXT.__auth_stubs: 0x470
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x9fa
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0x20
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x238
Functions:
~ sub_100001750 : 712 -> 700
~ sub_100001a5c -> sub_100001a50 : 484 -> 476
~ sub_1000020c8 -> sub_1000020b4 : 144 -> 120
~ sub_1000021d4 -> sub_1000021a8 : 32 -> 20
~ sub_1000021f4 -> sub_1000021bc : 36 -> 24
```

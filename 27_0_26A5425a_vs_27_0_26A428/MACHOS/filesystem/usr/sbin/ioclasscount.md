## ioclasscount

> `/usr/sbin/ioclasscount`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 130.0.0.0.0
-  __TEXT.__text: 0x1e34
+  __TEXT.__text: 0x1dac
   __TEXT.__auth_stubs: 0x550
   __TEXT.__const: 0x78
   __TEXT.__cstring: 0x5f0
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0xe0
   __DATA_CONST.__auth_got: 0x2a8
Functions:
~ sub_100000960 : 228 -> 216
~ sub_100000a44 -> sub_100000a38 : 92 -> 80
~ sub_1000014f8 -> sub_1000014e0 : 2952 -> 2888
~ sub_10000238c -> sub_100002334 : 172 -> 160
~ sub_100002438 -> sub_1000023d4 : 80 -> 68
~ sub_100002488 -> sub_100002418 : 68 -> 56
~ sub_1000024cc -> sub_100002450 : 32 -> 20
```

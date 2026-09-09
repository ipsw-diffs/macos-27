## kextload

> `/sbin/kextload`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x5484
+  __TEXT.__text: 0x5418
   __TEXT.__auth_stubs: 0x890
   __TEXT.__objc_stubs: 0x4c0
   __TEXT.__cstring: 0x199d

   __TEXT.__oslogstring: 0x2a
   __TEXT.__const: 0x8
   __TEXT.__objc_methname: 0x345
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x168
   __DATA_CONST.__cfstring: 0x940
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x50
Functions:
~ sub_1000011a0 : 484 -> 460
~ sub_1000035c0 -> sub_1000035a8 : 452 -> 440
~ sub_1000038a8 -> sub_100003884 : 320 -> 308
~ sub_1000039e8 -> sub_1000039b8 : 448 -> 436
~ sub_100004d08 -> sub_100004ccc : 440 -> 428
~ sub_1000052d0 -> sub_100005288 : 104 -> 92
~ sub_10000554c -> sub_1000054f8 : 120 -> 108
~ sub_1000055e4 -> sub_100005584 : 164 -> 152
```

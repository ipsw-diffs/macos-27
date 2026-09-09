## disklabel

> `/sbin/disklabel`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`

```diff

 7.0.0.0.0
-  __TEXT.__text: 0x26c8
+  __TEXT.__text: 0x2668
   __TEXT.__auth_stubs: 0x400
   __TEXT.__cstring: 0x1230
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__auth_got: 0x200
   __DATA_CONST.__got: 0x10
Functions:
~ sub_100000690 : 1268 -> 1256
~ sub_100000f7c -> sub_100000f70 : 40 -> 28
~ sub_100000fa4 -> sub_100000f8c : 592 -> 568
~ sub_1000011f4 -> sub_1000011c4 : 520 -> 508
~ sub_1000013fc -> sub_1000013c0 : 188 -> 176
~ sub_100002ccc -> sub_100002c84 : 56 -> 44
~ sub_100002d04 -> sub_100002cb0 : 56 -> 44
```

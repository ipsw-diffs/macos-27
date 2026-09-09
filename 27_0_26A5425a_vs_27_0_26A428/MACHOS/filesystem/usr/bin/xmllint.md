## xmllint

> `/usr/bin/xmllint`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 40.1.0.0.0
-  __TEXT.__text: 0x6c80
+  __TEXT.__text: 0x6bbc
   __TEXT.__auth_stubs: 0xbb0
   __TEXT.__cstring: 0x21e3
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__auth_got: 0x5d8
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_10000229c : 1824 -> 1812
~ sub_1000029bc -> sub_1000029b0 : 1324 -> 1312
~ sub_100002ee8 -> sub_100002ed0 : 284 -> 272
~ sub_100003930 -> sub_10000390c : 644 -> 608
~ sub_100005608 -> sub_1000055c0 : 240 -> 228
~ sub_100005a00 -> sub_1000059ac : 152 -> 140
~ sub_100005c2c -> sub_100005bcc : 244 -> 232
~ sub_100005dd0 -> sub_100005d64 : 200 -> 192
~ sub_100005e98 -> sub_100005e24 : 200 -> 192
~ sub_100006298 -> sub_10000621c : 240 -> 228
~ sub_100006388 -> sub_100006300 : 744 -> 732
~ sub_100006670 -> sub_1000065dc : 632 -> 620
~ sub_1000068e8 -> sub_100006848 : 240 -> 228
~ sub_100006f00 -> sub_100006e54 : 164 -> 152
~ sub_10000701c -> sub_100006f64 : 576 -> 564
```

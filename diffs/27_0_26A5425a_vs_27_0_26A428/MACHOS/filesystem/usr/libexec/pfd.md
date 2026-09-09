## pfd

> `/usr/libexec/pfd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0x7680
+  __TEXT.__text: 0x75ec
   __TEXT.__auth_stubs: 0x760
   __TEXT.__const: 0x2190
   __TEXT.__cstring: 0x1753
   __TEXT.__oslogstring: 0x1e
-  __TEXT.__unwind_info: 0x118
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__auth_got: 0x3b0
Functions:
~ sub_100000ea4 : 92 -> 80
~ sub_100001628 -> sub_10000161c : 116 -> 104
~ sub_100001878 -> sub_100001860 : 200 -> 176
~ sub_100001a48 -> sub_100001a18 : 6648 -> 6640
~ sub_100003440 -> sub_100003408 : 112 -> 100
~ sub_1000037ec -> sub_1000037a8 : 288 -> 276
~ sub_100004b24 -> sub_100004ad4 : 248 -> 236
~ sub_100006c14 -> sub_100006bb8 : 372 -> 364
~ sub_10000744c -> sub_1000073e8 : 28 -> 16
~ sub_100007468 -> sub_1000073f8 : 32 -> 20
~ sub_1000074ac -> sub_100007430 : 28 -> 16
~ sub_1000074c8 -> sub_100007440 : 32 -> 20
```

## fsck_exfat

> `/System/Library/Filesystems/exfat.fs/Contents/Resources/fsck_exfat`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 561.0.3.0.0
-  __TEXT.__text: 0xcf48
+  __TEXT.__text: 0xce68
   __TEXT.__auth_stubs: 0x620
   __TEXT.__const: 0x288
   __TEXT.__cstring: 0x3532
   __TEXT.__oslogstring: 0x18
-  __TEXT.__unwind_info: 0x238
+  __TEXT.__unwind_info: 0x328
   __DATA_CONST.__const: 0x420
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__auth_got: 0x310
Functions:
~ sub_100000bb4 : 200 -> 188
~ sub_100001618 -> sub_10000160c : 80 -> 68
~ sub_100001e40 -> sub_100001e28 : 44 -> 32
~ sub_100001f98 -> sub_100001f74 : 696 -> 692
~ sub_100002c24 -> sub_100002bfc : 244 -> 232
~ sub_100002d18 -> sub_100002ce4 : 132 -> 120
~ sub_100002f0c -> sub_100002ecc : 68 -> 56
~ sub_100003240 -> sub_1000031f4 : 248 -> 236
~ sub_100003528 -> sub_1000034d0 : 484 -> 480
~ sub_1000041e0 -> sub_100004184 : 188 -> 176
~ sub_10000559c -> sub_100005534 : 168 -> 156
~ sub_1000059d0 -> sub_10000595c : 764 -> 760
~ sub_100005ccc -> sub_100005c54 : 524 -> 516
~ sub_100005ed8 -> sub_100005e58 : 740 -> 736
~ sub_1000063d0 -> sub_10000634c : 2296 -> 2292
~ sub_100007bc8 -> sub_100007b40 : 740 -> 736
~ sub_100009924 -> sub_100009898 : 192 -> 168
~ sub_10000a4a0 -> sub_10000a3fc : 188 -> 176
~ sub_10000a55c -> sub_10000a4ac : 96 -> 84
~ sub_10000a5bc -> sub_10000a500 : 80 -> 68
~ sub_10000a62c -> sub_10000a564 : 80 -> 68
~ sub_10000a67c -> sub_10000a5a8 : 68 -> 56
```

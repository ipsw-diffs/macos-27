## newfs_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/newfs_hfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 751.0.0.0.0
-  __TEXT.__text: 0x3320
+  __TEXT.__text: 0x32a8
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x1077
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x1f0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_1000007f0 : 5372 -> 5336
~ sub_100001cec -> sub_100001cc8 : 156 -> 152
~ sub_100001d88 -> sub_100001d60 : 24 -> 12
~ sub_100001da0 -> sub_100001d6c : 24 -> 12
~ sub_100002e78 -> sub_100002e38 : 524 -> 488
~ sub_100003084 -> sub_100003020 : 480 -> 484
~ sub_10000341c -> sub_1000033bc : 24 -> 12
~ sub_100003434 -> sub_1000033c8 : 188 -> 176
```

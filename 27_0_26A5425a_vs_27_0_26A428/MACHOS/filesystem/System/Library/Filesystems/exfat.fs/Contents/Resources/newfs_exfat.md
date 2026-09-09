## newfs_exfat

> `/System/Library/Filesystems/exfat.fs/Contents/Resources/newfs_exfat`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 561.0.3.0.0
-  __TEXT.__text: 0x3574
+  __TEXT.__text: 0x3540
   __TEXT.__auth_stubs: 0x380
   __TEXT.__const: 0x4a58
   __TEXT.__cstring: 0xecf
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__auth_got: 0x1c0
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100000728 : 1368 -> 1372
~ sub_100000ce0 -> sub_100000ce4 : 148 -> 156
~ sub_1000012ac -> sub_1000012b8 : 128 -> 116
~ sub_100002580 : 496 -> 488
~ sub_100002a88 -> sub_100002a80 : 100 -> 88
~ sub_100002aec -> sub_100002ad8 : 304 -> 292
~ sub_100003340 -> sub_100003320 : 200 -> 196
~ sub_100003418 -> sub_1000033f4 : 240 -> 236
~ sub_100003a28 -> sub_100003a00 : 156 -> 144
```

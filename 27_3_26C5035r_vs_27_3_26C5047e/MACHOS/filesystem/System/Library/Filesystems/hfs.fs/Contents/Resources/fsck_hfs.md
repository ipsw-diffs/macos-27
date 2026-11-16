## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-753.60.3.0.0
-  __TEXT.__text: 0x348f4
+753.60.5.0.0
+  __TEXT.__text: 0x34ac4
   __TEXT.__auth_stubs: 0x7c0
   __TEXT.__const: 0x10b4
-  __TEXT.__cstring: 0x6fcb
+  __TEXT.__cstring: 0x703c
   __TEXT.__unwind_info: 0x690
   __DATA_CONST.__const: 0x378
   __DATA_CONST.__cfstring: 0x40

   - /usr/lib/libSystem.B.dylib
   Functions: 487
   Symbols:   139
-  CStrings:  794
+  CStrings:  796
 
Functions:
~ sub_100005b78 : 1132 -> 1232
~ sub_100006b38 -> sub_100006b9c : 904 -> 928
~ sub_100011854 -> sub_1000118d0 : 7200 -> 7404
~ sub_100015cf8 -> sub_100015e40 : 692 -> 828
CStrings:
+ "hfs_swap_BTNode: header node has %d records, should be 3\n"
+ "hfs_swap_BTNode: map node has %d records, should be 1\n"
```

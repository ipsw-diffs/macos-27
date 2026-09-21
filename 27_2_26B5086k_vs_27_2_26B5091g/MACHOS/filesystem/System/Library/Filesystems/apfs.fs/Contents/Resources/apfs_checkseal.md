## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_checkseal`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x4fcc8
+3288.40.14.0.0
+  __TEXT.__text: 0x4fde0
   __TEXT.__auth_stubs: 0x790
   __TEXT.__const: 0x4c0
   __TEXT.__cstring: 0x1041d
Functions:
~ sub_1000205c0 : 572 -> 596
~ sub_100041e60 -> sub_100041e78 : 1028 -> 1040
~ sub_100042264 -> sub_100042288 : 3756 -> 3816
~ sub_100045074 -> sub_1000450d4 : 3460 -> 3504
~ sub_100045df8 -> sub_100045e84 : 3596 -> 3720
~ sub_1000490b4 -> sub_1000491bc : 68 -> 84
```

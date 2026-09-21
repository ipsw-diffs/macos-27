## apfs_invert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_invert`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x52384
+3288.40.14.0.0
+  __TEXT.__text: 0x52494
   __TEXT.__auth_stubs: 0x800
   __TEXT.__cstring: 0x1100e
   __TEXT.__const: 0x8418
Functions:
~ sub_100008bb8 : 68 -> 84
~ sub_10001bae0 -> sub_10001baf0 : 572 -> 596
~ sub_100038cf4 -> sub_100038d1c : 300 -> 292
~ sub_1000474ac -> sub_1000474cc : 1028 -> 1040
~ sub_1000478b0 -> sub_1000478dc : 3756 -> 3816
~ sub_10004a6c0 -> sub_10004a728 : 3460 -> 3504
~ sub_10004b444 -> sub_10004b4d8 : 3596 -> 3720
CStrings:
+ "3288.40.14"
- "3288.40.13"
```

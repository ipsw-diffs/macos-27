## apfs_shrink_diskimage

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_shrink_diskimage`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x59548
+3288.40.14.0.0
+  __TEXT.__text: 0x59668
   __TEXT.__auth_stubs: 0x7e0
   __TEXT.__cstring: 0x12f95
   __TEXT.__const: 0x230
Functions:
~ sub_10001dc04 : 572 -> 596
~ sub_100048104 -> sub_10004811c : 4520 -> 4528
~ sub_10004ac70 -> sub_10004ac90 : 1028 -> 1040
~ sub_10004b074 -> sub_10004b0a0 : 3756 -> 3816
~ sub_10004de84 -> sub_10004deec : 3460 -> 3504
~ sub_10004ec08 -> sub_10004ec9c : 3596 -> 3720
~ sub_100052a44 -> sub_100052b54 : 68 -> 84
```

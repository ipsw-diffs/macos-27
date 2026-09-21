## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_condenser`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x4d574
+3288.40.14.0.0
+  __TEXT.__text: 0x4d684
   __TEXT.__auth_stubs: 0x820
   __TEXT.__cstring: 0xfbc6
   __TEXT.__const: 0x220
Functions:
~ sub_100005fcc : 68 -> 84
~ sub_1000155a8 -> sub_1000155b8 : 572 -> 596
~ sub_100031344 -> sub_10003136c : 284 -> 276
~ sub_1000433cc -> sub_1000433ec : 1028 -> 1040
~ sub_1000437d0 -> sub_1000437fc : 3756 -> 3816
~ sub_1000465e0 -> sub_100046648 : 3460 -> 3504
~ sub_100047364 -> sub_1000473f8 : 3596 -> 3720
CStrings:
+ "3288.40.14"
- "3288.40.13"
```

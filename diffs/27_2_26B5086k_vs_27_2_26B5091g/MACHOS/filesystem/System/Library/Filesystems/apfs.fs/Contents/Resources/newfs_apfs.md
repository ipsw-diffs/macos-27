## newfs_apfs

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x544fc
+3288.40.14.0.0
+  __TEXT.__text: 0x54614
   __TEXT.__auth_stubs: 0x900
   __TEXT.__cstring: 0x10710
   __TEXT.__const: 0x84a1
Functions:
~ sub_100013d14 : 572 -> 596
~ sub_1000304a8 -> sub_1000304c0 : 68 -> 84
~ sub_100036b70 -> sub_100036b98 : 304 -> 296
~ sub_100043d5c -> sub_100043d7c : 2556 -> 2564
~ sub_100046ae8 -> sub_100046b10 : 1028 -> 1040
~ sub_100046eec -> sub_100046f20 : 3756 -> 3816
~ sub_100049cfc -> sub_100049d6c : 3460 -> 3504
~ sub_10004aa80 -> sub_10004ab1c : 3596 -> 3720
CStrings:
+ "3288.40.14"
- "3288.40.13"
```

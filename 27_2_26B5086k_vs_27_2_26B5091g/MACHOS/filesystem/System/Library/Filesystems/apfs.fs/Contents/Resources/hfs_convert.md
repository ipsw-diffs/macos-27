## hfs_convert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__cstring`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0xb6f48
+3288.40.14.0.0
+  __TEXT.__text: 0xb7060
   __TEXT.__auth_stubs: 0x11a0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__init_offsets: 0x4
Functions:
~ sub_1000308f0 : 572 -> 596
~ sub_10004296c -> sub_100042984 : 20 -> 12
~ sub_100053b08 -> sub_100053b18 : 68 -> 84
~ sub_100058a1c -> sub_100058a3c : 2556 -> 2564
~ sub_10005ba54 -> sub_10005ba7c : 1028 -> 1040
~ sub_10005be58 -> sub_10005be8c : 3756 -> 3816
~ sub_10005e96c -> sub_10005e9dc : 3460 -> 3504
~ sub_10005f6f0 -> sub_10005f78c : 3596 -> 3720
CStrings:
+ "3288.40.14"
- "3288.40.13"
```

## hfs_convert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.60.7.0.0
-  __TEXT.__text: 0xb7004
+3288.60.11.0.1
+  __TEXT.__text: 0xb700c
   __TEXT.__auth_stubs: 0x11a0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x1a8ff
+  __TEXT.__cstring: 0x1a904
   __TEXT.__const: 0xa428
   __TEXT.__objc_methname: 0x48
   __TEXT.__unwind_info: 0x1fc8
Functions:
~ sub_100066784 : 88 -> 96
CStrings:
+ "3288.60.11.0.1"
- "3288.60.7"
```

## apfs_invert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_invert`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.60.7.0.0
-  __TEXT.__text: 0x52438
+3288.60.11.0.1
+  __TEXT.__text: 0x52440
   __TEXT.__auth_stubs: 0x800
-  __TEXT.__cstring: 0x1105f
+  __TEXT.__cstring: 0x11064
   __TEXT.__const: 0x8418
   __TEXT.__unwind_info: 0xb50
   __DATA_CONST.__const: 0x838
Functions:
~ sub_100051854 : 88 -> 96
CStrings:
+ "3288.60.11.0.1"
- "3288.60.7"
```

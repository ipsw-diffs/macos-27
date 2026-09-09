## apfs_checkdigest

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_checkdigest`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

 3288.1.3.0.0
-  __TEXT.__text: 0xf30
+  __TEXT.__text: 0xf00
   __TEXT.__auth_stubs: 0x250
   __TEXT.__const: 0x28
   __TEXT.__cstring: 0x684
Functions:
~ sub_100000780 : 1980 -> 1976
~ sub_100000f3c -> sub_100000f38 : 60 -> 56
~ sub_100000f78 -> sub_100000f70 : 32 -> 20
~ sub_10000106c -> sub_100001058 : 620 -> 604
~ sub_100001468 -> sub_100001444 : 56 -> 44
```

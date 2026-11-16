## fsck_exfat

> `/System/Library/Filesystems/exfat.fs/Contents/Resources/fsck_exfat`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-561.60.2.0.0
-  __TEXT.__text: 0xceb0
+561.60.3.0.0
+  __TEXT.__text: 0xcf24
   __TEXT.__auth_stubs: 0x620
   __TEXT.__const: 0x288
   __TEXT.__cstring: 0x355d
Functions:
~ sub_100007b88 : 736 -> 852
```

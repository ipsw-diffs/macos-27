## pam_mount.so.2

> `/usr/lib/pam/pam_mount.so.2`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 231.0.1.0.0
-  __TEXT.__text: 0x21fc
+  __TEXT.__text: 0x21c8
   __TEXT.__auth_stubs: 0x3d0
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__cstring: 0xbd8
   __TEXT.__const: 0x26
   __TEXT.__objc_methname: 0x7d
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x1f0
Functions:
~ _pam_shm_read : 424 -> 420
~ _pam_shm_cleanup : 60 -> 48
~ _pam_copy_secret_with_fallback : 184 -> 160
~ _pam_safe_string_release : 84 -> 72
```

## pam_ntlm.so.2

> `/usr/lib/pam/pam_ntlm.so.2`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 231.0.1.0.0
-  __TEXT.__text: 0x1ed0
+  __TEXT.__text: 0x1e9c
   __TEXT.__auth_stubs: 0x370
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__cstring: 0xa1a
   __TEXT.__const: 0x1c
   __TEXT.__objc_methname: 0x7d
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__cfstring: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x1c0
Functions:
~ _pam_shm_read : 424 -> 420
~ _pam_shm_cleanup : 60 -> 48
~ _pam_copy_secret_with_fallback : 184 -> 160
~ _pam_safe_string_release : 84 -> 72
```

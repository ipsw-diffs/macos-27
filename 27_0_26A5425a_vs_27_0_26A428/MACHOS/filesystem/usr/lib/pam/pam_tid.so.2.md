## pam_tid.so.2

> `/usr/lib/pam/pam_tid.so.2`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

 231.0.1.0.0
-  __TEXT.__text: 0x18b8
+  __TEXT.__text: 0x1864
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__const: 0x40

   __TEXT.__dlopen_cstrs: 0x5d
   __TEXT.__gcc_except_tab: 0x44
   __TEXT.__objc_methname: 0x1a4
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x158
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ _LA_LOG_coreauthd_client : 68 -> 56
~ ___LAEvaluatePolicy_block_invoke : 100 -> 88
~ _LAContextFromCFType : 132 -> 120
~ _getLAContextClass : 224 -> 212
~ ___LA_LOG_coreauthd_client_block_invoke : 72 -> 60
```

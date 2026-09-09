## filecoordinationd

> `/usr/sbin/filecoordinationd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 5027.0.69.0.0
-  __TEXT.__text: 0x13a0
+  __TEXT.__text: 0x137c
   __TEXT.__auth_stubs: 0x1a0
   __TEXT.__objc_stubs: 0x260
   __TEXT.__const: 0x78

   __TEXT.__oslogstring: 0x1aa
   __TEXT.__cstring: 0xf1
   __TEXT.__objc_methname: 0x29b
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__const: 0x220
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ ___receive_vfs_resolve_reparent_with_audit_token_block_invoke : 112 -> 100
~ ___handle_nspace_request_with_info_block_invoke : 100 -> 88
~ _OUTLINED_FUNCTION_1 : 28 -> 16
```

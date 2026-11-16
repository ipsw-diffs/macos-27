## libdispatch.dylib

> `/usr/lib/system/introspection/libdispatch.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-1605.60.4.0.0
-  __TEXT.__text: 0x47804
+1605.60.5.0.0
+  __TEXT.__text: 0x47890
   __TEXT.__auth_stubs: 0xd30
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__objc_methlist: 0x684
Functions:
~ _dispatch_data_create_with_transform : 296 -> 308
~ ____dispatch_transform_from_base32_with_table_block_invoke : 572 -> 588
~ ____dispatch_transform_from_base64_block_invoke : 480 -> 496
~ ____dispatch_transform_from_utf16_block_invoke : 900 -> 992
~ ____dispatch_transform_to_utf16_block_invoke : 696 -> 700
```

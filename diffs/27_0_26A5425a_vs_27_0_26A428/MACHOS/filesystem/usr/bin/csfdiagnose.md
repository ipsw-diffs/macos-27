## csfdiagnose

> `/usr/bin/csfdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 301.24.0.31.0
-  __TEXT.__text: 0x15acc
+  __TEXT.__text: 0x15028
   __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_stubs: 0x180
   __TEXT.__const: 0x15a2

   __TEXT.__swift_as_ret: 0x28
   __TEXT.__swift_as_cont: 0x44
   __TEXT.__objc_methname: 0xfb
-  __TEXT.__unwind_info: 0x538
+  __TEXT.__unwind_info: 0x698
   __TEXT.__eh_frame: 0x8b0
   __DATA_CONST.__const: 0xcb8
   __DATA_CONST.__objc_imageinfo: 0x8
```

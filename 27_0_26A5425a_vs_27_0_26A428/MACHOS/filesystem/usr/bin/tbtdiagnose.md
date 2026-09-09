## tbtdiagnose

> `/usr/bin/tbtdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 130.0.0.0.0
-  __TEXT.__text: 0x4cd4
+  __TEXT.__text: 0x4c50
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__objc_stubs: 0x9a0
   __TEXT.__objc_methlist: 0x458

   __TEXT.__objc_methtype: 0x3dc
   __TEXT.__const: 0x48
   __TEXT.__gcc_except_tab: 0x10
-  __TEXT.__unwind_info: 0x150
+  __TEXT.__unwind_info: 0x1b0
   __DATA_CONST.__cfstring: 0x820
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
```

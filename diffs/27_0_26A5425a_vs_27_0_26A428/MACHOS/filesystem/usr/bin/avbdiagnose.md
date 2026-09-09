## avbdiagnose

> `/usr/bin/avbdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 1500.16.0.0.0
-  __TEXT.__text: 0x6c34
+  __TEXT.__text: 0x6af0
   __TEXT.__auth_stubs: 0x200
   __TEXT.__objc_stubs: 0x18a0
   __TEXT.__objc_methlist: 0x134

   __TEXT.__objc_methname: 0xf79
   __TEXT.__objc_classname: 0x2a
   __TEXT.__objc_methtype: 0xba
-  __TEXT.__unwind_info: 0x100
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0x398
   __DATA_CONST.__cfstring: 0x12c0
   __DATA_CONST.__objc_classlist: 0x20
```

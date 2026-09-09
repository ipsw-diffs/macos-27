## leaks

> `/usr/bin/leaks`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 64578.57.1.0.0
-  __TEXT.__text: 0x152f4
+  __TEXT.__text: 0x14f34
   __TEXT.__auth_stubs: 0xbc0
   __TEXT.__objc_stubs: 0x3560
   __TEXT.__objc_methlist: 0x794

   __TEXT.__objc_classname: 0x48
   __TEXT.__objc_methtype: 0x256
   __TEXT.__oslogstring: 0xd97
-  __TEXT.__unwind_info: 0x370
+  __TEXT.__unwind_info: 0x4c0
   __DATA_CONST.__const: 0xdc0
   __DATA_CONST.__cfstring: 0x1880
   __DATA_CONST.__objc_classlist: 0x20
```

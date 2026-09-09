## mddiagnose

> `/usr/bin/mddiagnose`

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

 2459.405.0.0.0
-  __TEXT.__text: 0x10d98
+  __TEXT.__text: 0x10a1c
   __TEXT.__auth_stubs: 0xf60
   __TEXT.__objc_stubs: 0x1400
   __TEXT.__objc_methlist: 0x32c

   __TEXT.__gcc_except_tab: 0xcc
   __TEXT.__objc_classname: 0x4b
   __TEXT.__objc_methtype: 0x16b
-  __TEXT.__unwind_info: 0x430
+  __TEXT.__unwind_info: 0x558
   __DATA_CONST.__const: 0x638
   __DATA_CONST.__cfstring: 0x4ee0
   __DATA_CONST.__objc_classlist: 0x18
```

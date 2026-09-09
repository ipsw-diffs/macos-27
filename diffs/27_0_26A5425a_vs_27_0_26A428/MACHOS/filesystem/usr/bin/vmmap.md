## vmmap

> `/usr/bin/vmmap`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 64578.57.1.0.0
-  __TEXT.__text: 0x8814
+  __TEXT.__text: 0x85e0
   __TEXT.__auth_stubs: 0x860
   __TEXT.__objc_stubs: 0x1360
   __TEXT.__objc_methlist: 0x170

   __TEXT.__cstring: 0x20b2
   __TEXT.__objc_methtype: 0x87
   __TEXT.__oslogstring: 0x5f9
-  __TEXT.__unwind_info: 0x1c0
+  __TEXT.__unwind_info: 0x270
   __DATA_CONST.__const: 0x6c0
   __DATA_CONST.__cfstring: 0x5a0
   __DATA_CONST.__objc_classlist: 0x10
```

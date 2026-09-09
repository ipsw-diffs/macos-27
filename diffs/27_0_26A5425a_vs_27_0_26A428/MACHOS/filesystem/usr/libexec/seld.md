## seld

> `/usr/libexec/seld`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 370.42.1.0.0
-  __TEXT.__text: 0x2884c
+  __TEXT.__text: 0x28304
   __TEXT.__auth_stubs: 0x6f0
   __TEXT.__objc_stubs: 0x33a0
   __TEXT.__objc_methlist: 0xef4

   __TEXT.__oslogstring: 0x3eec
   __TEXT.__objc_classname: 0x234
   __TEXT.__objc_methtype: 0xceb
-  __TEXT.__unwind_info: 0x470
+  __TEXT.__unwind_info: 0x5a8
   __DATA_CONST.__const: 0xba0
   __DATA_CONST.__cfstring: 0x20e0
   __DATA_CONST.__objc_classlist: 0x58
```

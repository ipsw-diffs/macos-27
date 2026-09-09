## mdschema

> `/usr/bin/mdschema`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 2459.405.0.0.0
-  __TEXT.__text: 0x1e68
+  __TEXT.__text: 0x1e50
   __TEXT.__auth_stubs: 0x410
   __TEXT.__objc_stubs: 0x380
   __TEXT.__const: 0x40
   __TEXT.__cstring: 0x94e
   __TEXT.__objc_methname: 0x20d
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__cfstring: 0x340
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_1000023a8 : 564 -> 552
~ sub_1000025dc -> sub_1000025d0 : 188 -> 176
```

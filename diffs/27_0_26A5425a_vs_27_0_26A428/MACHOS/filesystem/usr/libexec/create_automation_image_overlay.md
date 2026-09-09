## create_automation_image_overlay

> `/usr/libexec/create_automation_image_overlay`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 9.0.0.0.0
-  __TEXT.__text: 0x1550
+  __TEXT.__text: 0x1544
   __TEXT.__auth_stubs: 0x280
   __TEXT.__objc_stubs: 0x420
   __TEXT.__objc_methlist: 0x14

   __TEXT.__objc_classname: 0xf
   __TEXT.__objc_methtype: 0x8
   __TEXT.__objc_methname: 0x32a
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__objc_catlist: 0x8
Functions:
~ sub_100001da4 : 496 -> 484
```

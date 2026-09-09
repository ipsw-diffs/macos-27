## diagnosticextensionsd

> `/usr/libexec/diagnosticextensionsd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

 222.0.0.0.0
-  __TEXT.__text: 0x780
+  __TEXT.__text: 0x768
   __TEXT.__auth_stubs: 0x160
   __TEXT.__objc_stubs: 0x80
   __TEXT.__cstring: 0x80
   __TEXT.__const: 0x18
   __TEXT.__oslogstring: 0x1b6
   __TEXT.__objc_methname: 0x28
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0xb8
Functions:
~ sub_100000ae0 : 72 -> 60
~ sub_100000f18 -> sub_100000f0c : 32 -> 20
```

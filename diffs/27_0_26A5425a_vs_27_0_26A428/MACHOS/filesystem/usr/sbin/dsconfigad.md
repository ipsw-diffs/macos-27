## dsconfigad

> `/usr/sbin/dsconfigad`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 114.0.0.0.0
-  __TEXT.__text: 0x2bf8
+  __TEXT.__text: 0x2bc8
   __TEXT.__auth_stubs: 0x450
   __TEXT.__objc_stubs: 0x3c0
   __TEXT.__const: 0x90
   __TEXT.__cstring: 0x1e42
   __TEXT.__oslogstring: 0x13
   __TEXT.__objc_methname: 0x290
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0x108
   __DATA_CONST.__const: 0x58
   __DATA_CONST.__cfstring: 0xc20
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100002bc8 : 148 -> 136
~ sub_10000306c -> sub_100003060 : 220 -> 208
~ sub_10000315c -> sub_100003144 : 92 -> 80
~ sub_10000335c -> sub_100003338 : 28 -> 16
```

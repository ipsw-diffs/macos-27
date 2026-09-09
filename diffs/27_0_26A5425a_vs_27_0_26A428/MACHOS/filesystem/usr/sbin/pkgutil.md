## pkgutil

> `/usr/sbin/pkgutil`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 883.0.0.0.0
-  __TEXT.__text: 0x51a0
+  __TEXT.__text: 0x5180
   __TEXT.__auth_stubs: 0x570
   __TEXT.__objc_stubs: 0xec0
   __TEXT.__const: 0x38
   __TEXT.__gcc_except_tab: 0xac
   __TEXT.__cstring: 0x1f8e
   __TEXT.__objc_methname: 0x9b3
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0x560
   __DATA_CONST.__cfstring: 0x4a0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_10000417c : 876 -> 868
~ sub_1000053b4 -> sub_1000053ac : 72 -> 60
~ sub_1000053fc -> sub_1000053e8 : 148 -> 136
```

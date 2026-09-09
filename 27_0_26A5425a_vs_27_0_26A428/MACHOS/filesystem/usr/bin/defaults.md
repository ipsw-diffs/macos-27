## defaults

> `/usr/bin/defaults`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 5027.0.69.0.0
-  __TEXT.__text: 0x32b0
+  __TEXT.__text: 0x3238
   __TEXT.__auth_stubs: 0x570
   __TEXT.__objc_stubs: 0x760
   __TEXT.__const: 0x48

   __TEXT.__cstring: 0x10af
   __TEXT.__oslogstring: 0x3
   __TEXT.__objc_methname: 0x499
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0xea0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _getHost : 236 -> 224
~ _getContainerIdentifier : 176 -> 164
~ _pathsForTriple : 564 -> 552
~ _getValue : 1560 -> 1500
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_2 : 32 -> 20
```

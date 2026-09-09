## corerepaird

> `/usr/libexec/corerepaird`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1307.1.2.0.0
-  __TEXT.__text: 0x1180
+  __TEXT.__text: 0x115c
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x220
   __TEXT.__objc_methlist: 0x294

   __TEXT.__objc_classname: 0xce
   __TEXT.__objc_methtype: 0x371
   __TEXT.__oslogstring: 0x206
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__cfstring: 0x100
   __DATA_CONST.__objc_classlist: 0x20
Functions:
~ sub_100000f90 : 68 -> 56
~ sub_100000fd4 -> sub_100000fc8 : 64 -> 52
~ sub_100001b4c -> sub_100001b34 : 24 -> 12
```

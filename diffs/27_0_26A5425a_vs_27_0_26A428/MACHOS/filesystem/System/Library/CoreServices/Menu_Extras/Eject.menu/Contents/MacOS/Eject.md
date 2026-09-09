## Eject

> `/System/Library/CoreServices/Menu Extras/Eject.menu/Contents/MacOS/Eject`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 263.0.2.0.0
-  __TEXT.__text: 0x1260
+  __TEXT.__text: 0x1230
   __TEXT.__auth_stubs: 0x110
   __TEXT.__objc_stubs: 0x740
   __TEXT.__objc_methlist: 0x234

   __TEXT.__cstring: 0x18d
   __TEXT.__objc_classname: 0x23
   __TEXT.__objc_methtype: 0x25b
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__cfstring: 0x360
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
Functions:
~ sub_de8 : 112 -> 100
~ sub_eb8 -> sub_eac : 112 -> 100
~ sub_1808 -> sub_17f0 : 144 -> 132
~ sub_1e74 -> sub_1e50 : 100 -> 88
```

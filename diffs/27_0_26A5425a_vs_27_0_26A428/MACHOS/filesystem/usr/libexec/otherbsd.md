## otherbsd

> `/usr/libexec/otherbsd`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0x1518
+  __TEXT.__text: 0x14f4
   __TEXT.__auth_stubs: 0x4a0
   __TEXT.__objc_stubs: 0x40
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x556
   __TEXT.__oslogstring: 0xc5
   __TEXT.__objc_methname: 0x2d
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000f2c : 84 -> 72
~ sub_1000011c0 -> sub_1000011b4 : 72 -> 60
~ sub_100001bd8 -> sub_100001bc0 : 344 -> 332
CStrings:
+ "@(#)VERSION:Darwin Auxiliary Bootstrapper Version 1.0.0: Sat Aug 22 16:54:30 PDT 2026; root:libxpc_executables-3298.1.1~67/otherbsd/RELEASE_ARM64E"
+ "Darwin Auxiliary Bootstrapper Version 1.0.0: Sat Aug 22 16:54:30 PDT 2026; root:libxpc_executables-3298.1.1~67/otherbsd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Auxiliary Bootstrapper Version 1.0.0: Tue Aug 25 19:32:07 PDT 2026; root:libxpc_executables-3298.1.1~70/otherbsd/RELEASE_ARM64E"
- "Darwin Auxiliary Bootstrapper Version 1.0.0: Tue Aug 25 19:32:07 PDT 2026; root:libxpc_executables-3298.1.1~70/otherbsd/RELEASE_ARM64E"
```

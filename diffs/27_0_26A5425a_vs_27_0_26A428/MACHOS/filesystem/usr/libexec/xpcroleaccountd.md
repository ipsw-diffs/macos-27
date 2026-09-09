## xpcroleaccountd

> `/usr/libexec/xpcroleaccountd`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0x29c0
+  __TEXT.__text: 0x2984
   __TEXT.__auth_stubs: 0x600
   __TEXT.__objc_stubs: 0x60
   __TEXT.__const: 0xa0

   __TEXT.__gcc_except_tab: 0x1e8
   __TEXT.__oslogstring: 0x93e
   __TEXT.__objc_methname: 0x30
-  __TEXT.__unwind_info: 0xe8
+  __TEXT.__unwind_info: 0x108
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__cfstring: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000c78 : 136 -> 124
~ sub_100000ec4 -> sub_100000eb8 : 84 -> 72
~ sub_100001058 -> sub_100001040 : 72 -> 60
~ sub_100001de0 -> sub_100001dbc : 676 -> 664
~ sub_100002084 -> sub_100002054 : 1504 -> 1492
CStrings:
+ "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Sat Aug 22 16:54:55 PDT 2026; root:libxpc_executables-3298.1.1~67/xpcroleaccountd/RELEASE_ARM64E"
+ "Darwin Role Account Bootstrapper Version 1.0.0: Sat Aug 22 16:54:55 PDT 2026; root:libxpc_executables-3298.1.1~67/xpcroleaccountd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Tue Aug 25 19:32:32 PDT 2026; root:libxpc_executables-3298.1.1~70/xpcroleaccountd/RELEASE_ARM64E"
- "Darwin Role Account Bootstrapper Version 1.0.0: Tue Aug 25 19:32:32 PDT 2026; root:libxpc_executables-3298.1.1~70/xpcroleaccountd/RELEASE_ARM64E"
```

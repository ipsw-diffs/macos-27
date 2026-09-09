## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 3298.1.1.0.0
-  __TEXT.__text: 0x107b8
+  __TEXT.__text: 0x10404
   __TEXT.__auth_stubs: 0xc80
   __TEXT.__objc_stubs: 0x1500
   __TEXT.__objc_methlist: 0x9f0

   __TEXT.__objc_methname: 0x14d1
   __TEXT.__cstring: 0x134d
   __TEXT.__gcc_except_tab: 0x2dc
-  __TEXT.__unwind_info: 0x3d0
+  __TEXT.__unwind_info: 0x4a8
   __DATA_CONST.__const: 0x518
   __DATA_CONST.__cfstring: 0x1c0
   __DATA_CONST.__objc_classlist: 0x70
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Sat Aug 22 16:54:35 PDT 2026; root:libxpc_executables-3298.1.1~67/smd/RELEASE_ARM64E"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Sat Aug 22 16:54:35 PDT 2026; root:libxpc_executables-3298.1.1~67/smd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Aug 25 19:32:12 PDT 2026; root:libxpc_executables-3298.1.1~70/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Aug 25 19:32:12 PDT 2026; root:libxpc_executables-3298.1.1~70/smd/RELEASE_ARM64E"
```

## Installer

> `/System/Library/CoreServices/Installer.app/Contents/MacOS/Installer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1370.0.0.0.0
-  __TEXT.__text: 0x19410
+1371.0.0.0.0
+  __TEXT.__text: 0x193b8
   __TEXT.__auth_stubs: 0x5e0
   __TEXT.__objc_stubs: 0x6e40
   __TEXT.__objc_methlist: 0x1b08

   __TEXT.__objc_classname: 0x450
   __TEXT.__objc_methtype: 0xd06
   __TEXT.__gcc_except_tab: 0xdc
-  __TEXT.__unwind_info: 0x8d8
+  __TEXT.__unwind_info: 0x8d0
   __DATA_CONST.__const: 0x4b8
   __DATA_CONST.__cfstring: 0x28e0
   __DATA_CONST.__objc_classlist: 0x118

   - /usr/lib/libDiskUnlock.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 553
+  Functions: 551
   Symbols:   275
   CStrings:  1914
 
```

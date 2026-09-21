## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1155.40.6.0.0
-  __TEXT.__text: 0xb0050
+1155.40.7.0.0
+  __TEXT.__text: 0xb00d8
   __TEXT.__objc_methlist: 0x262c
   __TEXT.__cstring: 0x21a53
   __TEXT.__const: 0xc2c1
   __TEXT.__gcc_except_tab: 0x3b6c
   __TEXT.__dlopen_cstrs: 0x63
   __TEXT.__oslogstring: 0xad5
-  __TEXT.__unwind_info: 0x36a8
+  __TEXT.__unwind_info: 0x36b0
   __TEXT.__eh_frame: 0x7c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libz.1.dylib
   - /usr/lib/updaters/libAppleTconUARPUpdater.dylib
   - /usr/lib/updaters/libT200Updater.dylib
-  Functions: 3824
-  Symbols:   5424
+  Functions: 3826
+  Symbols:   5426
   CStrings:  4817
 
Symbols:
+ _AMAuthInstallCopyDebugPath
+ _AMAuthInstallSetDebugPath
CStrings:
+ "libauthinstall-1155.40.7"
- "libauthinstall-1155.40.6"
```

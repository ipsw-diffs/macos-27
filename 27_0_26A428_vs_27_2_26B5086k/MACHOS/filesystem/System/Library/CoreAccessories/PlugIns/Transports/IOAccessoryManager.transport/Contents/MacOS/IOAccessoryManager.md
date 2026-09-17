## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/Contents/MacOS/IOAccessoryManager`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1216.0.0.0.0
-  __TEXT.__text: 0x496dc
+1219.40.5.0.0
+  __TEXT.__text: 0x496ec
   __TEXT.__auth_stubs: 0x1050
   __TEXT.__objc_stubs: 0x4ee0
   __TEXT.__objc_methlist: 0x2910

   __DATA.__objc_ivar: 0x3d8
   __DATA.__objc_data: 0x550
   __DATA.__data: 0x6c4
-  __DATA.__bss: 0x190
+  __DATA.__bss: 0x198
   __DATA.__common: 0x1c
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
   Functions: 1381
-  Symbols:   2941
+  Symbols:   2942
   CStrings:  2701
 
Symbols:
+ systemInfo_isDeveloperBuild.developerBuild
Functions:
~ _systemInfo_isDeveloperBuild : 52 -> 56
~ ___systemInfo_isDeveloperBuild_block_invoke : 4 -> 16
```

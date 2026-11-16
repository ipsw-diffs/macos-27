## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 100288.60.4.0.0
-  __TEXT.__text: 0xbb5b8
+  __TEXT.__text: 0xbb16c
   __TEXT.__objc_methlist: 0x150
   __TEXT.__cstring: 0xf2ea
   __TEXT.__const: 0x10610

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   - /usr/lib/system/libkxld.dylib
-  Functions: 3911
+  Functions: 3906
   Symbols:   4358
   CStrings:  2999
 
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "OSKEXT_BUILD_DATE 23:30:05 Nov  9 2026"
- "OSKEXT_BUILD_DATE 22:20:58 Oct 28 2026"
```

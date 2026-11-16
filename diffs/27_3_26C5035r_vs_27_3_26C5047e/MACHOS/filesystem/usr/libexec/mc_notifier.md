## mc_notifier

> `/usr/libexec/mc_notifier`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-579.60.5.0.0
-  __TEXT.__text: 0x1724
-  __TEXT.__auth_stubs: 0x2c0
+579.60.8.0.0
+  __TEXT.__text: 0x1a84
+  __TEXT.__auth_stubs: 0x2f0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__objc_methlist: 0x50
   __TEXT.__const: 0x750
-  __TEXT.__cstring: 0x101
+  __TEXT.__cstring: 0x12f
   __TEXT.__oslogstring: 0x46e
   __TEXT.__objc_methname: 0x5a
   __TEXT.__objc_classname: 0xa
   __TEXT.__objc_methtype: 0x30
-  __TEXT.__unwind_info: 0xc8
-  __DATA_CONST.__const: 0x40
+  __TEXT.__unwind_info: 0x100
+  __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__auth_got: 0x168
-  __DATA_CONST.__got: 0x48
+  __DATA_CONST.__auth_got: 0x180
+  __DATA_CONST.__got: 0x40
   __DATA.__objc_const: 0xd0
   __DATA.__objc_selrefs: 0x30
   __DATA.__objc_ivar: 0x4
   __DATA.__objc_data: 0x50
   __DATA.__common: 0x8
+  __DATA.__bss: 0x60
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /System/Library/PrivateFrameworks/SMBClient.framework/Versions/A/SMBClient
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 30
-  Symbols:   61
-  CStrings:  56
+  Functions: 50
+  Symbols:   63
+  CStrings:  63
 
Symbols:
+ _dispatch_once
+ _objc_claimAutoreleasedReturnValue
+ _os_log_create
- __os_log_default
CStrings:
+ "auth"
+ "com.apple.SMBClient"
+ "dfs"
+ "io"
+ "mount"
+ "nic"
+ "rpc"
```

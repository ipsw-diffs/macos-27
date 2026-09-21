## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/Versions/A/PhotoLibraryServicesCore`

```diff

-916.41.100.0.0
-  __TEXT.__text: 0xd01cc
+916.45.110.0.0
+  __TEXT.__text: 0xd025c
   __TEXT.__objc_methlist: 0x84ac
   __TEXT.__const: 0x22b4
   __TEXT.__dlopen_cstrs: 0xe1
   __TEXT.__gcc_except_tab: 0x5760
   __TEXT.__cstring: 0x15884
-  __TEXT.__oslogstring: 0xb79a
+  __TEXT.__oslogstring: 0xb788
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x41f0
   __TEXT.__objc_stubs: 0x0

   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x2b8
   __AUTH_CONST.__auth_got: 0xd10
-  __AUTH.__objc_data: 0x2f8
+  __AUTH.__objc_data: 0xf0
   __DATA.__objc_ivar: 0x694
   __DATA.__data: 0x10e0
-  __DATA.__bss: 0x878
-  __DATA_DIRTY.__objc_data: 0x2508
+  __DATA.__bss: 0x888
+  __DATA_DIRTY.__objc_data: 0x2710
   __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x8c8
+  __DATA_DIRTY.__bss: 0x8b8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
Functions:
~ -[PLFileBackedLogger _inlock_createLoggerRecordWithLogFileURL:logRotate:didRebuildLogArchive:error:] : 660 -> 768
~ -[PLFileBackedLogger close] : 620 -> 656
CStrings:
+ "PLFileBackedLogger: Failed to open log file at %@. Error: %@"
+ "PLFileBackedLogger: close url backed logger: %@"
+ "PLFileBackedLogger: open url backed logger: %@"
+ "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %@"
- "PLFileBackedLogger: Failed to open log file. Error: %@"
- "PLFileBackedLogger: close url backed logger: %{public}@"
- "PLFileBackedLogger: open url backed logger: %{public}@"
- "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %{public}@"
```

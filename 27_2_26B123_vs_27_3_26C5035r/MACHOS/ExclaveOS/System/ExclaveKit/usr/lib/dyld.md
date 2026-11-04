## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

-27104.0.0.0.0
-  __TEXT.__text: 0x5caa4
+27200.1.0.0.0
+  __TEXT.__text: 0x5ce64
   __TEXT.__const: 0x1c0ac
-  __TEXT.__cstring: 0xed2e
-  __TEXT.__unwind_info: 0x2390
+  __TEXT.__cstring: 0xed7e
+  __TEXT.__unwind_info: 0x23a0
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0xb50
-  __AUTH_CONST.__const: 0x3f50
+  __AUTH_CONST.__const: 0x3f80
   __AUTH.__data: 0x470
   __DATA.__data: 0x1448
   __DATA.__ENDPOINTS: 0x62a

   __DATA.__common: 0x550
   __DATA.__bss: 0xba408
   __DATA_DIRTY.__all_image_info: 0x170
-  Functions: 2767
-  Symbols:   2219
-  CStrings:  1480
+  Functions: 2772
+  Symbols:   2221
+  CStrings:  1481
 
Symbols:
+ __ZN5dyld35ArrayIN5dyld417InterposeTupleAllEE9push_backERKS2_
+ __ZNK5dyld46Loader6headerERKNS_12RuntimeStateE
CStrings:
+ "  cache dylib rooted, so also interposed cache binds to 0x%08lX with 0x%08lX\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveKit.MacOSX.platform/Developer/SDKs/ExclaveKit.MacOSX27.3.Internal.sdk/System/ExclaveKit/usr/include/xrt/thread.h"
+ "27200.1"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveKit.MacOSX.platform/Developer/SDKs/ExclaveKit.MacOSX27.2.Internal.sdk/System/ExclaveKit/usr/include/xrt/thread.h"
- "27104"
```

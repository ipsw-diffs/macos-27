## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Versions/A/Frameworks/MPSCore.framework/Versions/A/MPSCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-130.1.1.0.0
+130.1.2.0.0
   __TEXT.__text: 0x955ac
   __TEXT.__objc_methlist: 0x283c
   __TEXT.__const: 0x2984

   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x408
   __DATA.__objc_ivar: 0x32c
-  __DATA.__data: 0x25a8
+  __DATA.__data: 0x2000
   __DATA.__common: 0x28
   __DATA.__bss: 0x48
   __DATA_DIRTY.__objc_ivar: 0x64
   __DATA_DIRTY.__objc_data: 0xff0
+  __DATA_DIRTY.__data: 0x5a8
   __DATA_DIRTY.__bss: 0x270
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
CStrings:
+ "130.1.2"
- "130.1.1"
```

## WebKit

> `/System/Library/Frameworks/WebKit.framework/Versions/A/WebKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-625.1.29.11.24
-  __TEXT.__text: 0x1508414
+625.1.29.11.25
+  __TEXT.__text: 0x15083fc
   __TEXT.__objc_methlist: 0x152d8
   __TEXT.__dlsym_cstr: 0xa81
   __TEXT.__getClass_cstr: 0xb1c
Functions:
~ __ZN6WebKit19WebExtensionContext18addInjectedContentERKN3WTF6VectorINS_12WebExtension19InjectedContentDataELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEERNS_24WebExtensionMatchPatternE : 5848 -> 5824
CStrings:
+ "22625.1.29.11.25"
- "22625.1.29.11.24"
```

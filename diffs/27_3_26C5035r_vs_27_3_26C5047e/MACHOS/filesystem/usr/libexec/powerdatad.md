## powerdatad

> `/usr/libexec/powerdatad`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`

```diff

-2043.60.6.0.0
-  __TEXT.__text: 0x796c
-  __TEXT.__auth_stubs: 0x530
-  __TEXT.__objc_stubs: 0xfa0
-  __TEXT.__objc_methlist: 0x300
-  __TEXT.__const: 0x108
-  __TEXT.__cstring: 0x742
-  __TEXT.__oslogstring: 0xfb8
-  __TEXT.__gcc_except_tab: 0x324
-  __TEXT.__objc_methname: 0xd92
+2043.60.10.0.1
+  __TEXT.__text: 0x82f0
+  __TEXT.__auth_stubs: 0x520
+  __TEXT.__objc_stubs: 0x10e0
+  __TEXT.__objc_methlist: 0x310
+  __TEXT.__const: 0x100
+  __TEXT.__cstring: 0x7c1
+  __TEXT.__oslogstring: 0x10bf
+  __TEXT.__gcc_except_tab: 0x30c
+  __TEXT.__objc_methname: 0xe84
   __TEXT.__objc_classname: 0x2e
-  __TEXT.__objc_methtype: 0x283
+  __TEXT.__objc_methtype: 0x29f
   __TEXT.__dlopen_cstrs: 0x5e
-  __TEXT.__unwind_info: 0x328
-  __DATA_CONST.__const: 0x368
-  __DATA_CONST.__cfstring: 0xb40
+  __TEXT.__unwind_info: 0x330
+  __DATA_CONST.__const: 0x348
+  __DATA_CONST.__cfstring: 0xd00
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0x2a8
-  __DATA_CONST.__got: 0x110
-  __DATA.__objc_const: 0x3b8
-  __DATA.__objc_selrefs: 0x468
-  __DATA.__objc_ivar: 0x30
+  __DATA_CONST.__auth_got: 0x2a0
+  __DATA_CONST.__got: 0x120
+  __DATA.__objc_const: 0x3e8
+  __DATA.__objc_selrefs: 0x4c8
+  __DATA.__objc_ivar: 0x34
   __DATA.__objc_data: 0xf0
-  __DATA.__data: 0x248
+  __DATA.__data: 0x1e8
   __DATA.__bss: 0x48
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 170
-  Symbols:   127
-  CStrings:  414
+  Functions: 179
+  Symbols:   128
+  CStrings:  445
 
Symbols:
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_CLASS_$_NSMutableSet
- _CFStringCreateWithCString
CStrings:
+ "%@-%@"
+ "%@.%@.plist"
+ "%@/%@"
+ "Auto-deriving storage for channel %{public}@ in group %{public}@"
+ "Duplicate channel %{public}@ in group %{public}@ -- its data will be merged with the first instance"
+ "Failed to allocate defaults for file: %{public}@"
+ "Failed to get group for channel %{public}@"
+ "M2CPU"
+ "M3CPU"
+ "MACC2_V_T"
+ "MACC3_V_T"
+ "No channels found for group '%s*' subgroup '%s'"
+ "No domain name for LTS store"
+ "No map entry for channel %{public}@ in group %{public}@"
+ "Q24@0:8^{__CFDictionary=}16"
+ "Skipping unnamed channel in group %{public}@"
+ "T@\"NSMutableDictionary\",&,N,V_channelMap"
+ "UTF8String"
+ "_channelMap"
+ "buildChannelMapPruning:"
+ "channelMap"
+ "containsObject:"
+ "decimalDigitCharacterSet"
+ "group"
+ "hasPrefix:"
+ "initWithFileName:"
+ "invertedSet"
+ "lowercaseString"
+ "lts.%@.plist"
+ "lts.m2cpu.plist"
+ "lts.m3cpu.plist"
+ "rangeOfCharacterFromSet:"
+ "reportName"
+ "set"
+ "setChannelMap:"
+ "stringByDeletingPathExtension"
+ "stringWithFormat:"
+ "substringFromIndex:"
- "Failed to allocate defaults for chName: %{public}@"
- "Failed to get domain name for chName: %{public}@"
- "No channels found for group '%s' subgroup '%s'"
- "Using LTS group name: %s"
- "getfileNameForChannel:"
- "initForChannel:"
- "setChannelExistsForChannel:"
```

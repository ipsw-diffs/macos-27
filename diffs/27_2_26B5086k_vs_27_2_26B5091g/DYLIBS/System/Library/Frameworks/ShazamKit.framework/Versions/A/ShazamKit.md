## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/Versions/A/ShazamKit`

```diff

-427.2.4.0.0
-  __TEXT.__text: 0xa534c
+427.2.5.0.0
+  __TEXT.__text: 0xa53c8
   __TEXT.__objc_methlist: 0x51f0
   __TEXT.__const: 0x22a97
   __TEXT.__cstring: 0x3c4d
   __TEXT.__gcc_except_tab: 0x38bc
-  __TEXT.__oslogstring: 0x14e1
+  __TEXT.__oslogstring: 0x1531
   __TEXT.__constg_swiftt: 0xa6c
   __TEXT.__swift5_typeref: 0x10ac
   __TEXT.__swift5_builtin: 0xdc

   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__auth_got: 0x1280
-  __AUTH.__objc_data: 0xa0
-  __AUTH.__data: 0x338
   __DATA.__objc_ivar: 0x4ec
-  __DATA.__data: 0x1b2518
-  __DATA.__bss: 0x2a28
+  __DATA.__data: 0x1b1650
+  __DATA.__bss: 0x29a8
   __DATA.__common: 0x168
-  __DATA_DIRTY.__objc_data: 0x2288
-  __DATA_DIRTY.__data: 0xa68
-  __DATA_DIRTY.__bss: 0x360
+  __DATA_DIRTY.__objc_data: 0x2328
+  __DATA_DIRTY.__data: 0x1c48
+  __DATA_DIRTY.__bss: 0x3e0
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3832
   Symbols:   6280
-  CStrings:  590
+  CStrings:  591
 
Functions:
~ -[SHAttribution initWithTask:] : 460 -> 432
~ +[SHAttribution productNameForBundleIdentifier:] : 128 -> 280
CStrings:
+ "Unable to get localized name for bundle identifier %{mask.hash}@: %{public}@"
```

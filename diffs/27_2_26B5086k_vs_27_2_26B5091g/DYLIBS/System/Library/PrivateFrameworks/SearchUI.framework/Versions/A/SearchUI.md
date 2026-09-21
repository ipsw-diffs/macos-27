## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/Versions/A/SearchUI`

```diff

-685.1.2.0.0
-  __TEXT.__text: 0xcde94
-  __TEXT.__objc_methlist: 0xf75c
+685.1.3.0.0
+  __TEXT.__text: 0xcdec8
+  __TEXT.__objc_methlist: 0xf774
   __TEXT.__const: 0x2f74
-  __TEXT.__cstring: 0x3534
+  __TEXT.__cstring: 0x3514
   __TEXT.__oslogstring: 0x2635
   __TEXT.__gcc_except_tab: 0x7d0
   __TEXT.__ustring: 0xa8

   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x1e28
-  __AUTH_CONST.__const: 0x3ce0
-  __AUTH_CONST.__cfstring: 0x36a0
+  __DATA_CONST.__got: 0x1e20
+  __AUTH_CONST.__const: 0x3ca0
+  __AUTH_CONST.__cfstring: 0x3660
   __AUTH_CONST.__objc_const: 0x1ae30
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_arrayobj: 0x9c0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1410
-  __AUTH.__objc_data: 0x34b8
+  __AUTH.__objc_data: 0x2d88
   __AUTH.__data: 0x3c8
   __DATA.__objc_ivar: 0xbac
-  __DATA.__data: 0x2658
-  __DATA.__bss: 0xb38
+  __DATA.__data: 0x25b0
+  __DATA.__bss: 0xa78
   __DATA.__common: 0xe8
-  __DATA_DIRTY.__objc_data: 0x3a08
-  __DATA_DIRTY.__data: 0xb00
-  __DATA_DIRTY.__bss: 0x1790
+  __DATA_DIRTY.__objc_data: 0x4138
+  __DATA_DIRTY.__data: 0xba8
+  __DATA_DIRTY.__bss: 0x1830
   __DATA_DIRTY.__common: 0x58
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5947
-  Symbols:   13511
-  CStrings:  803
+  Functions: 5945
+  Symbols:   13505
+  CStrings:  801
 
Symbols:
+ +[SearchUIUtilities isCurrentProcessHostingSpotlight]
+ -[SearchUICardSectionView contentViewLayoutMargins]
+ -[SearchUICardSectionView updateSecondaryCommandViewAlignmentInsets]
+ -[SearchUIImageView shadowDisabled]
+ _objc_msgSend$contentViewLayoutMargins
+ _objc_msgSend$isCurrentProcessHostingSpotlight
+ _objc_msgSend$updateSecondaryCommandViewAlignmentInsets
- +[SearchUIUtilities isCampoProcess]
- +[SearchUIUtilities isSpotlightProcess]
- _OBJC_CLASS_$_NSProcessInfo
- ___35+[SearchUIUtilities isCampoProcess]_block_invoke
- ___39+[SearchUIUtilities isSpotlightProcess]_block_invoke
- _objc_msgSend$isCampoProcess
- _objc_msgSend$isSpotlightProcess
- _objc_msgSend$processInfo
- _objc_msgSend$processName
- isCampoProcess.isCampoProcess
- isCampoProcess.onceToken
- isSpotlightProcess.isSpotlightProcess
- isSpotlightProcess.onceToken
CStrings:
- "Campo"
- "com.apple.Spotlight"
```

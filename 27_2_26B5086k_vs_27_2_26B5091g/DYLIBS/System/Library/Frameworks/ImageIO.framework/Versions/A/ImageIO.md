## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2851.1.4.0.0
-  __TEXT.__text: 0x3cc5a8
+2851.1.5.0.0
+  __TEXT.__text: 0x3cc618
   __TEXT.__objc_methlist: 0xd68
   __TEXT.__const: 0x2b620
   __TEXT.__gcc_except_tab: 0x1d7d4

   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x470
   __DATA_CONST.__got: 0xaf0
-  __AUTH_CONST.__const: 0x4edd8
+  __AUTH_CONST.__const: 0x4eec8
   __AUTH_CONST.__cfstring: 0x35f60
   __AUTH_CONST.__objc_const: 0x11d0
   __AUTH_CONST.__weak_auth_got: 0x30

   __AUTH.__thread_bss: 0x1
   __DATA.__objc_ivar: 0xa4
   __DATA.__data: 0x6440
-  __DATA.__bss: 0x30c88
-  __DATA.__common: 0xaf8
+  __DATA.__bss: 0x30888
+  __DATA.__common: 0xaf0
   __DATA_DIRTY.__data: 0x38c
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0xc50
-  __DATA_DIRTY.__common: 0xfd9
+  __DATA_DIRTY.__bss: 0x1050
+  __DATA_DIRTY.__common: 0xfe0
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 19847
-  Symbols:   23065
+  Functions: 19849
+  Symbols:   23067
   CStrings:  15218
 
Symbols:
+ __ZN13IIOReadPlugin29willApplyOrientationTransformEv
+ __ZN14HEIFReadPlugin29willApplyOrientationTransformEv
Functions:
~ __ZN14IIOImageSource22createThumbnailAtIndexEmP13IIODictionaryPiPj : 5916 -> 5900
+ __ZN13IIOReadPlugin29willApplyOrientationTransformEv
~ __ZN13IIOSubsampler17subsampleRGBA8888EPhjS0_Pj : 472 -> 464
~ __ZN13IIOSubsampler15subsampleRGBA16EPhjS0_Pj : 528 -> 572
~ __ZN13IIOSubsampler15subsampleRGBA32EPhjS0_Pj : 528 -> 572
~ __ZN19AppleJPEGReadPlugin16copyIOSurfaceSetEP7InfoRecP15CGImageProviderPK14__CFDictionary : 248 -> 256
+ __ZN14HEIFReadPlugin29willApplyOrientationTransformEv
~ __ZN14HEIFReadPlugin20copyImageBlockSetImpEP7InfoRecP15CGImageProvider6CGRect6CGSizePK14__CFDictionary : 4716 -> 4720
~ __ZN14HEIFReadPlugin19decodeIntoIOSurfaceEP18IIODecodeParameterP11__IOSurface : 1876 -> 1888
CStrings:
+ "*** ERROR: failed to allocte temp (%zu bytes)\n"
- "*** ERROR: failed to allocte temp (%d bytes)\n"
```

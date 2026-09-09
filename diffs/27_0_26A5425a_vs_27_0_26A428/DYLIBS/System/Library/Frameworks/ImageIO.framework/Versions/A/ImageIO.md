## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

 2851.0.0.0.0
-  __TEXT.__text: 0x3d2e64
+  __TEXT.__text: 0x3d3aa0
   __TEXT.__objc_methlist: 0xd58
   __TEXT.__const: 0x2b480
-  __TEXT.__gcc_except_tab: 0x1d60c
-  __TEXT.__cstring: 0x77365
+  __TEXT.__gcc_except_tab: 0x1d648
+  __TEXT.__cstring: 0x77765
   __TEXT.__oslogstring: 0x17
   __TEXT.__constg_swiftt: 0x26a4
   __TEXT.__swift5_typeref: 0x3d88

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0x112d8
-  __TEXT.__eh_frame: 0x8fe4
+  __TEXT.__unwind_info: 0x112f0
+  __TEXT.__eh_frame: 0x8fec
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_arraydata: 0x470
   __DATA_CONST.__got: 0xa88
   __AUTH_CONST.__const: 0x4ed98
-  __AUTH_CONST.__cfstring: 0x35f40
+  __AUTH_CONST.__cfstring: 0x35f60
   __AUTH_CONST.__objc_const: 0x11d0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x20

   __DATA_DIRTY.__data: 0x38c
   __DATA_DIRTY.__crash_info: 0x148
   __DATA_DIRTY.__bss: 0xbd0
-  __DATA_DIRTY.__common: 0xfa1
+  __DATA_DIRTY.__common: 0xfd9
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 19794
-  Symbols:   22993
-  CStrings:  15174
+  Functions: 19796
+  Symbols:   23002
+  CStrings:  15190
 
Symbols:
+ __ZL33IIOCopyDNGProvenanceFromContainerPK14__CFDictionaryPK10__CFString
+ __ZN14IIOImageSource25copyProvenanceDataAtIndexEmP21CGImageProvenanceType
+ _gFunc_CMPhotoDNGCopyProperties
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp
+ _gIIO_kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage
+ _gIIO_kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage
CStrings:
+ "*** CMPhotoCompressionSessionAddCustomMetadata (provenance) err = %s [%d]\n"
+ "CMPhotoDNGCopyProperties"
+ "SubIFD"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp"
+ "kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage"
+ "kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage"
+ "❌  failed to load 'CMPhotoDNGCopyProperties' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp' [%s]\n"
+ "❌  failed to load 'kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage' [%s]\n"
```

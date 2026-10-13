## AVKit

> `/System/Library/Frameworks/AVKit.framework/Versions/A/AVKit`

```diff

-1385.12.1.0.0
-  __TEXT.__text: 0xe3840
-  __TEXT.__objc_methlist: 0xe7c8
+1385.14.5.1.0
+  __TEXT.__text: 0xe3e44
+  __TEXT.__objc_methlist: 0xe7e0
   __TEXT.__const: 0x1e48
   __TEXT.__constg_swiftt: 0x9c4
   __TEXT.__swift5_typeref: 0x310e

   __TEXT.__swift5_assocty: 0xf0
   __TEXT.__swift5_proto: 0x60
   __TEXT.__swift5_types: 0x54
-  __TEXT.__cstring: 0xb66d
+  __TEXT.__cstring: 0xb6be
   __TEXT.__swift5_capture: 0x6e8
   __TEXT.__swift_as_entry: 0x58
   __TEXT.__swift_as_cont: 0x68

   __TEXT.__oslogstring: 0x23b3
   __TEXT.__gcc_except_tab: 0xe60
   __TEXT.__ustring: 0x15e
-  __TEXT.__unwind_info: 0x47b0
+  __TEXT.__unwind_info: 0x47c8
   __TEXT.__eh_frame: 0xfa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7f00
+  __DATA_CONST.__objc_selrefs: 0x7f40
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x458
   __DATA_CONST.__objc_arraydata: 0x1e0
-  __DATA_CONST.__got: 0xef0
-  __AUTH_CONST.__const: 0x2f30
-  __AUTH_CONST.__cfstring: 0x7e80
+  __DATA_CONST.__got: 0xf50
+  __AUTH_CONST.__const: 0x2f50
+  __AUTH_CONST.__cfstring: 0x7f20
   __AUTH_CONST.__objc_const: 0x18f90
   __AUTH_CONST.__objc_doubleobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x1e0
   __AUTH_CONST.__objc_floatobj: 0x60
-  __AUTH_CONST.__auth_got: 0xd78
+  __AUTH_CONST.__auth_got: 0xd80
   __AUTH.__objc_data: 0x3c58
   __AUTH.__data: 0x2b0
   __DATA.__objc_ivar: 0x1460
-  __DATA.__data: 0x2860
-  __DATA.__bss: 0xe70
+  __DATA.__data: 0x2870
+  __DATA.__bss: 0xe80
   __DATA.__common: 0xc0
   __DATA_DIRTY.__objc_data: 0xa78
   __DATA_DIRTY.__data: 0x30

   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
   - /System/Library/Frameworks/Symbols.framework/Versions/A/Symbols
+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/PrivateFrameworks/AVKitCore.framework/Versions/A/AVKitCore
   - /System/Library/PrivateFrameworks/CoreAutoLayout.framework/Versions/A/CoreAutoLayout
   - /System/Library/PrivateFrameworks/DFRFoundation.framework/Versions/A/DFRFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5398
-  Symbols:   12193
-  CStrings:  1510
+  Functions: 5404
+  Symbols:   12218
+  CStrings:  1515
 
Symbols:
+ -[AVNowPlayingInfoController _stringForIdentifier:inSupplementalMetadata:]
+ -[AVNowPlayingInfoController _supplementalMetadataForCurrentItem]
+ AVNowPlayingInfoSupplementalMetadataIsAvailable.determineSupplementalMetadataAvailabilityOnce
+ AVNowPlayingInfoSupplementalMetadataIsAvailable.isAvailable
+ GCC_except_table2640
+ GCC_except_table2659
+ GCC_except_table2679
+ GCC_except_table2790
+ GCC_except_table2984
+ GCC_except_table3072
+ GCC_except_table3075
+ GCC_except_table3106
+ GCC_except_table3118
+ GCC_except_table3209
+ GCC_except_table3275
+ GCC_except_table3410
+ GCC_except_table3415
+ GCC_except_table3417
+ GCC_except_table3478
+ GCC_except_table3486
+ GCC_except_table3491
+ GCC_except_table3544
+ GCC_except_table3549
+ GCC_except_table3550
+ GCC_except_table3630
+ GCC_except_table3715
+ GCC_except_table3717
+ GCC_except_table3834
+ GCC_except_table3903
+ GCC_except_table3906
+ GCC_except_table3908
+ GCC_except_table3915
+ GCC_except_table3933
+ GCC_except_table4353
+ _AVMetadataCommonIdentifierArtist
+ _AVMetadataCommonIdentifierArtwork
+ _AVMetadataCommonKeyArtwork
+ _AVNowPlayingInfoMIMETypeForImageData
+ _CGImageSourceGetType
+ _OBJC_CLASS_$_UTType
+ ___AVNowPlayingInfoSupplementalMetadataIsAvailable_block_invoke
+ _kCMMetadataBaseDataType_BMP
+ _kCMMetadataBaseDataType_GIF
+ _kCMMetadataBaseDataType_JPEG
+ _kCMMetadataBaseDataType_PNG
+ _kMRMediaRemoteNowPlayingInfoArtworkData
+ _kMRMediaRemoteNowPlayingInfoArtworkMIMEType
+ _objc_msgSend$_stringForIdentifier:inSupplementalMetadata:
+ _objc_msgSend$_supplementalMetadataForCurrentItem
+ _objc_msgSend$dataType
+ _objc_msgSend$dataValue
+ _objc_msgSend$instancesRespondToSelector:
+ _objc_msgSend$preferredMIMEType
+ _objc_msgSend$supplementalMetadata
+ _objc_msgSend$typeWithIdentifier:
- GCC_except_table2639
- GCC_except_table2655
- GCC_except_table2675
- GCC_except_table2786
- GCC_except_table2980
- GCC_except_table3068
- GCC_except_table3071
- GCC_except_table3102
- GCC_except_table3114
- GCC_except_table3205
- GCC_except_table3271
- GCC_except_table3402
- GCC_except_table3411
- GCC_except_table3413
- GCC_except_table3474
- GCC_except_table3482
- GCC_except_table3487
- GCC_except_table3540
- GCC_except_table3545
- GCC_except_table3546
- GCC_except_table3626
- GCC_except_table3711
- GCC_except_table3713
- GCC_except_table3830
- GCC_except_table3899
- GCC_except_table3902
- GCC_except_table3904
- GCC_except_table3911
- GCC_except_table3929
- GCC_except_table4349
CStrings:
+ "image/bmp"
+ "image/gif"
+ "image/jpeg"
+ "image/png"
+ "player.currentItem.supplementalMetadata"
```

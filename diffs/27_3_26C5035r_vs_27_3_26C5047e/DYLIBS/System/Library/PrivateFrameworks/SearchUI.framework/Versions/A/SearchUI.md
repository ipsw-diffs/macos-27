## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/Versions/A/SearchUI`

```diff

-685.2.5.0.0
-  __TEXT.__text: 0xcf154
-  __TEXT.__objc_methlist: 0xf8f4
+685.2.9.0.0
+  __TEXT.__text: 0xcf5c8
+  __TEXT.__objc_methlist: 0xf954
   __TEXT.__const: 0x2f94
   __TEXT.__cstring: 0x3544
   __TEXT.__oslogstring: 0x2685

   __TEXT.__ustring: 0xa8
   __TEXT.__dlopen_cstrs: 0xb2
   __TEXT.__swift5_typeref: 0x2c54
-  __TEXT.__constg_swiftt: 0x1208
+  __TEXT.__constg_swiftt: 0x1210
   __TEXT.__swift5_reflstr: 0x58a
   __TEXT.__swift5_fieldmd: 0x7bc
   __TEXT.__swift5_builtin: 0x78

   __TEXT.__swift_as_ret: 0xdc
   __TEXT.__swift_as_cont: 0x164
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x47c0
-  __TEXT.__eh_frame: 0x19e0
+  __TEXT.__unwind_info: 0x47d8
+  __TEXT.__eh_frame: 0x19d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6a0
+  __DATA_CONST.__const: 0x6b8
   __DATA_CONST.__objc_classlist: 0x9d0
   __DATA_CONST.__objc_catlist: 0x408
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x87d0
+  __DATA_CONST.__objc_selrefs: 0x8810
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x1e70
+  __DATA_CONST.__got: 0x1e80
   __AUTH_CONST.__const: 0x3ca0
   __AUTH_CONST.__cfstring: 0x36a0
-  __AUTH_CONST.__objc_const: 0x1af40
+  __AUTH_CONST.__objc_const: 0x1af78
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_arrayobj: 0x9c0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1420
-  __AUTH.__objc_data: 0x2d88
+  __AUTH.__objc_data: 0x2d90
   __AUTH.__data: 0x3c8
-  __DATA.__objc_ivar: 0xbbc
+  __DATA.__objc_ivar: 0xbc0
   __DATA.__data: 0x26f0
   __DATA.__bss: 0xa78
   __DATA.__common: 0xf0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5984
-  Symbols:   13491
+  Functions: 5992
+  Symbols:   13505
   CStrings:  804
 
Symbols:
+ +[SearchUIPhotosImage targetPixelSizeForSize:pixelSize:scale:maxPixelSize:]
+ +[SearchUIUtilities imageDataFromImage:scale:isDarkStyle:maxPixelSize:completion:]
+ -[SearchUIDataSourceSnapshotBuilder prefersCardSectionIDForResult:cardSection:]
+ -[SearchUIImage maxPixelSize]
+ -[SearchUIImage setMaxPixelSize:]
+ _OBJC_IVAR_$_SearchUIImage._maxPixelSize
+ __OBJC_$_CLASS_METHODS_SearchUIPhotosImage
+ ___82+[SearchUIUtilities imageDataFromImage:scale:isDarkStyle:maxPixelSize:completion:]_block_invoke
+ ___block_descriptor_106_e8_32s40bs_e17_v16?0"PHAsset"8l
+ ___block_descriptor_114_e8_32s40s48bs_e5_v8?0l
+ _objc_msgSend$imageDataFromImage:scale:isDarkStyle:maxPixelSize:completion:
+ _objc_msgSend$isEventLive
+ _objc_msgSend$maxPixelSize
+ _objc_msgSend$prefersCardSectionIDForResult:cardSection:
+ _objc_msgSend$setMaxPixelSize:
+ _objc_msgSend$shouldUseTVFavoritingFor:
+ _objc_msgSend$targetPixelSizeForSize:pixelSize:scale:maxPixelSize:
- ___69+[SearchUIUtilities imageDataFromImage:scale:isDarkStyle:completion:]_block_invoke
- ___block_descriptor_90_e8_32s40bs_e17_v16?0"PHAsset"8l
- ___block_descriptor_98_e8_32s40s48bs_e5_v8?0l
```

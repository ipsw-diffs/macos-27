## PhotosUIFoundation

> `/System/iOSSupport/System/Library/PrivateFrameworks/PhotosUIFoundation.framework/Versions/A/PhotosUIFoundation`

### Sections with Same Size but Changed Content

- `__TEXT.__ustring`

```diff

-916.58.114.0.0
-  __TEXT.__text: 0xed624
-  __TEXT.__objc_methlist: 0xfc6c
-  __TEXT.__const: 0x7220
-  __TEXT.__swift5_typeref: 0x2e14
-  __TEXT.__constg_swiftt: 0x3a90
+920.8.100.0.0
+  __TEXT.__text: 0xedf3c
+  __TEXT.__objc_methlist: 0xfd84
+  __TEXT.__const: 0x7260
+  __TEXT.__swift5_typeref: 0x2e10
+  __TEXT.__constg_swiftt: 0x3a8c
   __TEXT.__swift5_builtin: 0x208
-  __TEXT.__swift5_reflstr: 0x17c7
-  __TEXT.__swift5_fieldmd: 0x1b94
+  __TEXT.__swift5_reflstr: 0x17aa
+  __TEXT.__swift5_fieldmd: 0x1ba4
   __TEXT.__swift5_assocty: 0x9d0
-  __TEXT.__swift5_proto: 0x3b8
-  __TEXT.__swift5_types: 0x268
-  __TEXT.__cstring: 0xb8e5
-  __TEXT.__swift5_capture: 0xe28
+  __TEXT.__swift5_proto: 0x3bc
+  __TEXT.__swift5_types: 0x26c
+  __TEXT.__cstring: 0xb96f
   __TEXT.__swift5_protos: 0x98
-  __TEXT.__oslogstring: 0x1a3a
+  __TEXT.__swift5_capture: 0xe28
+  __TEXT.__oslogstring: 0x1a71
   __TEXT.__swift_as_entry: 0x74
   __TEXT.__swift_as_ret: 0x50
   __TEXT.__swift_as_cont: 0x94
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__gcc_except_tab: 0xce4
   __TEXT.__ustring: 0x124
-  __TEXT.__unwind_info: 0x69c8
-  __TEXT.__eh_frame: 0x1c88
+  __TEXT.__unwind_info: 0x6a20
+  __TEXT.__eh_frame: 0x1cc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x348
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7838
+  __DATA_CONST.__objc_selrefs: 0x78f0
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0x300
-  __DATA_CONST.__got: 0xe98
-  __AUTH_CONST.__const: 0x6120
-  __AUTH_CONST.__cfstring: 0x7c40
-  __AUTH_CONST.__objc_const: 0x1f178
-  __AUTH_CONST.__objc_intobj: 0x150
-  __AUTH_CONST.__objc_doubleobj: 0x1e0
+  __DATA_CONST.__got: 0xea0
+  __AUTH_CONST.__const: 0x61b8
+  __AUTH_CONST.__cfstring: 0x7ca0
+  __AUTH_CONST.__objc_const: 0x1f2f0
   __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__objc_dictobj: 0x168
+  __AUTH_CONST.__objc_intobj: 0x150
+  __AUTH_CONST.__objc_doubleobj: 0x1e0
   __AUTH_CONST.__auth_got: 0x1950
-  __AUTH.__objc_data: 0x34c0
+  __AUTH.__objc_data: 0x34a0
   __AUTH.__data: 0x1920
-  __DATA.__objc_ivar: 0x10e8
-  __DATA.__data: 0x39b8
-  __DATA.__bss: 0x5330
+  __DATA.__objc_ivar: 0x1104
+  __DATA.__data: 0x39c0
+  __DATA.__bss: 0x53b8
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1bb0
-  __DATA_DIRTY.__data: 0x1100
+  __DATA_DIRTY.__data: 0x10f0
   __DATA_DIRTY.__bss: 0x18c0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9581
-  Symbols:   13722
-  CStrings:  1569
+  Functions: 9613
+  Symbols:   13771
+  CStrings:  1572
 
Symbols:
+ +[PXAssetActionMenuBuilder _submenuWithTitle:systemImageName:actionTypes:actionManager:topRowActionTypesSet:titleOverrides:shouldInlineSingleAction:]
+ +[PXBadgeHelper setSharedAlbumBadgeSymbolName:]
+ +[PXBadgeHelper sharedAlbumBadgeImageMini]
+ +[PXBadgeHelper sharedAlbumBadgeImage]
+ +[PXBadgeHelper sharedAlbumBadgeSymbolName]
+ -[PXActionPerformer dismissHostViewControllerWithCompletionHandler:]
+ -[PXActionPerformer setWaitsForAsynchronousWork:]
+ -[PXActionPerformer waitsForAsynchronousWork]
+ -[PXAssetActionManager objectReferenceOverridesSelection]
+ -[PXAssetActionManager setObjectReferenceOverridesSelection:]
+ -[PXExtendedTraitCollection _setVerticalBarEdge:]
+ -[PXExtendedTraitCollection _updateVerticalBarEdgeIfNeeded]
+ -[PXExtendedTraitCollection invalidateVerticalBarEdge]
+ -[PXExtendedTraitCollection verticalBarEdge]
+ -[PXExtendedTraitCollection(PlatformSpecific) getVerticalBarEdge:]
+ -[PXFeatureSpec verticalBarEdge]
+ -[PXMediaProvider setSearchResultContextualVideoThumbnailIdentifiers:]
+ -[PXUserDefaults allPhotosLibraryPreferredIndividualItemsColumnWidth]
+ -[PXUserDefaults photosGridPreferredIndividualItemsColumnWidth]
+ -[PXUserDefaults searchPreferredIndividualItemsColumnWidth]
+ -[PXUserDefaults setAllPhotosLibraryPreferredIndividualItemsColumnWidth:]
+ -[PXUserDefaults setPhotosGridPreferredIndividualItemsColumnWidth:]
+ -[PXUserDefaults setSearchPreferredIndividualItemsColumnWidth:]
+ GCC_except_table1009
+ GCC_except_table1097
+ GCC_except_table1122
+ GCC_except_table1156
+ GCC_except_table117
+ GCC_except_table1174
+ GCC_except_table1206
+ GCC_except_table1284
+ GCC_except_table1294
+ GCC_except_table142
+ GCC_except_table147
+ GCC_except_table1562
+ GCC_except_table1564
+ GCC_except_table1599
+ GCC_except_table1622
+ GCC_except_table180
+ GCC_except_table190
+ GCC_except_table1956
+ GCC_except_table2005
+ GCC_except_table2170
+ GCC_except_table224
+ GCC_except_table2425
+ GCC_except_table2429
+ GCC_except_table2432
+ GCC_except_table2435
+ GCC_except_table2443
+ GCC_except_table2447
+ GCC_except_table2454
+ GCC_except_table2456
+ GCC_except_table2458
+ GCC_except_table2460
+ GCC_except_table2462
+ GCC_except_table2464
+ GCC_except_table2466
+ GCC_except_table2472
+ GCC_except_table2508
+ GCC_except_table2509
+ GCC_except_table2522
+ GCC_except_table257
+ GCC_except_table2587
+ GCC_except_table2589
+ GCC_except_table2876
+ GCC_except_table3025
+ GCC_except_table3220
+ GCC_except_table3293
+ GCC_except_table3384
+ GCC_except_table3632
+ GCC_except_table3643
+ GCC_except_table3716
+ GCC_except_table3718
+ GCC_except_table3729
+ GCC_except_table3732
+ GCC_except_table3751
+ GCC_except_table3756
+ GCC_except_table3764
+ GCC_except_table3768
+ GCC_except_table3772
+ GCC_except_table3959
+ GCC_except_table3980
+ GCC_except_table3989
+ GCC_except_table3991
+ GCC_except_table4008
+ GCC_except_table4036
+ GCC_except_table4079
+ GCC_except_table4080
+ GCC_except_table4083
+ GCC_except_table438
+ GCC_except_table452
+ GCC_except_table456
+ GCC_except_table4566
+ GCC_except_table470
+ GCC_except_table485
+ GCC_except_table492
+ GCC_except_table4923
+ GCC_except_table506
+ GCC_except_table5144
+ GCC_except_table5218
+ GCC_except_table5239
+ GCC_except_table5264
+ GCC_except_table614
+ GCC_except_table691
+ GCC_except_table692
+ GCC_except_table822
+ GCC_except_table826
+ GCC_except_table842
+ GCC_except_table902
+ _OBJC_IVAR_$_PXActionPerformer._waitsForAsynchronousWork
+ _OBJC_IVAR_$_PXAssetActionManager._objectReferenceOverridesSelection
+ _OBJC_IVAR_$_PXExtendedTraitCollection._verticalBarEdge
+ _OBJC_IVAR_$_PXFeatureSpec._verticalBarEdge
+ _OBJC_IVAR_$_PXUserDefaults._allPhotosLibraryPreferredIndividualItemsColumnWidth
+ _OBJC_IVAR_$_PXUserDefaults._photosGridPreferredIndividualItemsColumnWidth
+ _OBJC_IVAR_$_PXUserDefaults._searchPreferredIndividualItemsColumnWidth
+ _PXApplyVerticalBarEdgePaddingIfNeeded
+ _PXBoundaryLayoutRegions
+ _PXEnhancedLandscapeBarEnabled
+ _PXHasCenteredBoundaryLayoutRegion
+ _PXHasVerticalBar
+ _PXHasVerticalBarEdge
+ _PXHasVerticalStatusBar
+ _PXImageFromCGImageWithSize
+ __OBJC_$_CATEGORY_CLASS_METHODS_UIViewController_$_PXExtendedTraitCollection
+ __OBJC_$_CATEGORY_NSObject_$_PhotosUIFoundation
+ __OBJC_$_CATEGORY_NSValue_$_PXDisplayAsset
+ __OBJC_$_CATEGORY_UIViewController_$_PXExtendedTraitCollection
+ __OBJC_$_CATEGORY_UIView_$_PhotosUICoreScrolling
+ __OBJC_$_CLASS_METHODS_NSObject(PhotosUIFoundation|PXAssertAdditions|PXReusableObject)
+ __OBJC_$_CLASS_METHODS_NSValue(PXDisplayAsset|PXEdgeInsets|PXViewSpecDescriptor|PXSimpleIndexPath|PXTileGeometry)
+ __OBJC_$_CLASS_METHODS_UIView(PhotosUICoreScrolling|PhotosUIFoundation)
+ __OBJC_$_INSTANCE_METHODS_NSObject(PhotosUIFoundation|PXAssertAdditions|PXReusableObject)
+ __OBJC_$_INSTANCE_METHODS_NSValue(PXDisplayAsset|PXEdgeInsets|PXViewSpecDescriptor|PXSimpleIndexPath|PXTileGeometry)
+ __OBJC_$_INSTANCE_METHODS_PXAssetsDataSource(DisplayAsset|FetchResultInfo)
+ __OBJC_$_INSTANCE_METHODS_PXExtendedTraitCollection(SwiftImplementation|PlatformSpecific|PXExtendedTraitCollectionSnapshot)
+ __OBJC_$_INSTANCE_METHODS_UIView(PhotosUICoreScrolling|PhotosUIFoundation)
+ __OBJC_$_INSTANCE_METHODS_UIViewController(PXExtendedTraitCollection|PhotosDetailsNavigation|PhotosUIFoundation)
+ __OBJC_CLASS_PROTOCOLS_$_PXAssetsDataSource(DisplayAsset|FetchResultInfo)
+ __OBJC_CLASS_PROTOCOLS_$_UIView(PhotosUICoreScrolling|PhotosUIFoundation)
+ __OBJC_CLASS_PROTOCOLS_$_UIViewController(PXExtendedTraitCollection|PhotosDetailsNavigation|PhotosUIFoundation)
+ ___68-[PXActionPerformer dismissHostViewControllerWithCompletionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e5_v8?0ls32l8r40l8
+ ___block_descriptor_64_e8_32s40bs48r_e12_v24?0Q8^B16ls32l8s40l8r48l8
+ __sharedAlbumBadgeSymbolName
+ _objc_msgSend$_setVerticalBarEdge:
+ _objc_msgSend$_submenuWithTitle:systemImageName:actionTypes:actionManager:topRowActionTypesSet:titleOverrides:shouldInlineSingleAction:
+ _objc_msgSend$_updateVerticalBarEdgeIfNeeded
+ _objc_msgSend$actionPerformer:dismissHostViewControllerWithCompletionHandler:
+ _objc_msgSend$getVerticalBarEdge:
+ _objc_msgSend$invalidateVerticalBarEdge
+ _objc_msgSend$objectReferenceOverridesSelection
+ _objc_msgSend$sharedAlbumBadgeSymbolName
+ _objc_msgSend$verticalBarEdge
+ _symbolic _____ 18PhotosUIFoundation40IsPXEnhancedLandscapeBarEnabledPredicateV
- GCC_except_table1131
- GCC_except_table1135
- GCC_except_table1138
- GCC_except_table1141
- GCC_except_table1149
- GCC_except_table1153
- GCC_except_table1160
- GCC_except_table1162
- GCC_except_table1164
- GCC_except_table1166
- GCC_except_table1168
- GCC_except_table1170
- GCC_except_table1172
- GCC_except_table1178
- GCC_except_table1240
- GCC_except_table1305
- GCC_except_table15
- GCC_except_table1567
- GCC_except_table1577
- GCC_except_table1602
- GCC_except_table1628
- GCC_except_table1843
- GCC_except_table1864
- GCC_except_table1873
- GCC_except_table1875
- GCC_except_table1930
- GCC_except_table1931
- GCC_except_table1934
- GCC_except_table2071
- GCC_except_table2086
- GCC_except_table2104
- GCC_except_table2144
- GCC_except_table2232
- GCC_except_table2396
- GCC_except_table2612
- GCC_except_table2646
- GCC_except_table2647
- GCC_except_table2674
- GCC_except_table2943
- GCC_except_table3042
- GCC_except_table3044
- GCC_except_table3097
- GCC_except_table3111
- GCC_except_table3115
- GCC_except_table3122
- GCC_except_table3129
- GCC_except_table3144
- GCC_except_table315
- GCC_except_table3151
- GCC_except_table3165
- GCC_except_table3433
- GCC_except_table3468
- GCC_except_table3489
- GCC_except_table3569
- GCC_except_table3571
- GCC_except_table3606
- GCC_except_table3637
- GCC_except_table3641
- GCC_except_table3657
- GCC_except_table3706
- GCC_except_table3722
- GCC_except_table4021
- GCC_except_table4031
- GCC_except_table4094
- GCC_except_table410
- GCC_except_table411
- GCC_except_table4248
- GCC_except_table430
- GCC_except_table4359
- GCC_except_table4380
- GCC_except_table4385
- GCC_except_table4536
- GCC_except_table4655
- GCC_except_table4944
- GCC_except_table4946
- GCC_except_table4957
- GCC_except_table4960
- GCC_except_table4979
- GCC_except_table4984
- GCC_except_table4992
- GCC_except_table4996
- GCC_except_table5000
- GCC_except_table5033
- GCC_except_table5092
- GCC_except_table5118
- GCC_except_table5159
- __OBJC_$_CATEGORY_CLASS_METHODS_UIView_$_PhotosUIFoundation
- __OBJC_$_CATEGORY_NSObject_$_PXReusableObject
- __OBJC_$_CATEGORY_NSValue_$_PXEdgeInsets
- __OBJC_$_CATEGORY_UIViewController_$_PhotosDetailsNavigation
- __OBJC_$_CATEGORY_UIView_$_PhotosUIFoundation
- __OBJC_$_CLASS_METHODS_NSObject(PXReusableObject|PhotosUIFoundation|PXAssertAdditions)
- __OBJC_$_CLASS_METHODS_NSValue(PXEdgeInsets|PXViewSpecDescriptor|PXTileGeometry|PXDisplayAsset|PXSimpleIndexPath)
- __OBJC_$_CLASS_METHODS_UIViewController(PhotosDetailsNavigation|PhotosUIFoundation|PXExtendedTraitCollection)
- __OBJC_$_INSTANCE_METHODS_NSObject(PXReusableObject|PhotosUIFoundation|PXAssertAdditions)
- __OBJC_$_INSTANCE_METHODS_NSValue(PXEdgeInsets|PXViewSpecDescriptor|PXTileGeometry|PXDisplayAsset|PXSimpleIndexPath)
- __OBJC_$_INSTANCE_METHODS_PXAssetsDataSource(FetchResultInfo|DisplayAsset)
- __OBJC_$_INSTANCE_METHODS_PXExtendedTraitCollection(SwiftImplementation|PXExtendedTraitCollectionSnapshot|PlatformSpecific)
- __OBJC_$_INSTANCE_METHODS_UIView(PhotosUIFoundation|PhotosUICoreScrolling)
- __OBJC_$_INSTANCE_METHODS_UIViewController(PhotosDetailsNavigation|PhotosUIFoundation|PXExtendedTraitCollection)
- __OBJC_CATEGORY_PROTOCOLS_$_UIView_$_PhotosUIFoundation
- __OBJC_CLASS_PROTOCOLS_$_PXAssetsDataSource(FetchResultInfo|DisplayAsset)
- __OBJC_CLASS_PROTOCOLS_$_UIViewController(PhotosDetailsNavigation|PhotosUIFoundation|PXExtendedTraitCollection)
- ___block_descriptor_48_e8_32bs40r_e5_v8?0lr40l8s32l8
- ___block_descriptor_64_e8_32o40b48r_e12_v24?0Q8^B16ls40l8s32l8r48l8
- ___swift_closure_destructor.2Tm
CStrings:
+ "%@ does not support contextual video thumbnails"
+ "1\xc1"
+ "allPhotosLibraryPreferredIndividualItemsColumnWidth"
+ "photosGridPreferredIndividualItemsColumnWidth"
+ "searchPreferredIndividualItemsColumnWidth"
+ "\xf0\xc1"
- "1\xb1"
- "\xd5"
- "\xf0\x91"
```

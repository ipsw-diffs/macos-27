## VisualTestKit

> `/System/Library/PrivateFrameworks/VisualTestKit.framework/Versions/A/VisualTestKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

 5.0.0.0.0
-  __TEXT.__text: 0x61f0
+  __TEXT.__text: 0x5e18
   __TEXT.__objc_methlist: 0xbc4
   __TEXT.__const: 0x1f8
   __TEXT.__cstring: 0x2f9
   __TEXT.__gcc_except_tab: 0x5c
-  __TEXT.__unwind_info: 0x2b8
+  __TEXT.__unwind_info: 0x340
   __TEXT.__objc_stubs: 0x1520
   __TEXT.__auth_stubs: 0x3d0
   __TEXT.__objc_classname: 0x282
Functions:
~ ___55-[VTKAttachmentStoreManager saveItems:withID:testCase:]_block_invoke_2 : 140 -> 128
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[VTKAttachmentStoreManager setItemsDirectory:] : 100 -> 88
~ -[VTKAttachmentStoreManager itemsDirectory] : 88 -> 76
~ _VTKImageWithDrawItems : 484 -> 472
~ __NSStringFromVTKAssertID : 232 -> 220
~ __StringExtensionForMask : 688 -> 676
~ ___VTKSetReferenceImagesDirectory : 96 -> 84
~ ___VTKAddVerticalGuideAt : 112 -> 100
~ ___VTKAddHorizontalGuideAt : 112 -> 100
~ ___VTKAddSqureGuideAt : 144 -> 132
~ ___VTKAddExclusionAreaAt : 116 -> 104
~ -[VTKFileReferenceItemsSource setItemsDirectory:] : 256 -> 244
~ -[VTKFileReferenceItemsSource referenceImageWithID:testCase:error:] : 304 -> 292
~ +[VTKStoreManagerImageItem itemWithImage:itemType:] : 148 -> 136
~ -[VTKStoreManagerImageItem fileNameWithTestID:] : 300 -> 288
~ -[VTKStoreManagerImageItem attachWithThestID:] : 220 -> 208
~ -[VTKStoreManagerImageItem .cxx_destruct] : 80 -> 68
~ +[VTKStoreManagerItem itemWithView:] : 172 -> 160
~ -[VTKStoreManagerItem fileNameWithTestID:] : 164 -> 152
~ -[VTKStoreManagerItem attachWithThestID:] : 212 -> 200
~ -[VTKStoreManagerItem .cxx_destruct] : 68 -> 56
~ -[VTKAntiAliasDetector .cxx_destruct] : 80 -> 68
~ ___VTKSetReferenceItemSourceType : 80 -> 68
~ ___VTKSetImageComparatorStrategy : 80 -> 68
~ ___VTKSetImageComparisonOptions : 80 -> 68
~ -[VTKInternalConfiguration referenceItemsSource] : 116 -> 104
~ +[VTKInternalConfiguration _referenceItemsSourceForType:] : 68 -> 56
~ -[VTKInternalConfiguration storeManager] : 88 -> 76
~ -[VTKInternalConfiguration imageComparator] : 140 -> 128
~ +[VTKInternalConfiguration _comparatorForStrategy:comparisonOptions:] : 160 -> 148
~ -[VTKInternalConfiguration setReferenceImagesDirectory:] : 192 -> 180
~ -[VTKInternalConfiguration referenceImagesDirectory] : 164 -> 152
~ -[VTKInternalConfiguration addVerticalGuideAt:withColor:] : 144 -> 132
~ -[VTKInternalConfiguration addHorozontalGuideAt:withColor:] : 144 -> 132
~ -[VTKInternalConfiguration addSquareGuideAt:withColor:] : 168 -> 156
~ -[VTKInternalConfiguration addExclusionAreaAt:] : 132 -> 120
~ -[VTKInternalConfiguration drawItems] : 44 -> 32
~ -[VTKInternalConfiguration exclusionAreas] : 44 -> 32
~ -[VTKInternalConfiguration .cxx_destruct] : 104 -> 92
~ -[VTKColorDifferenceComparator compareImage:withImage:] : 924 -> 912
~ ___copy_helper_block_e8_32s40s48s56s64s72r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56s64s72r : 96 -> 84
~ -[VTKColorDifferenceComparator _checkForAA] : 88 -> 76
~ -[VTKColorDifferenceComparator description] : 228 -> 216
~ +[VTKBitmapContext contextType:width:height:scale:] : 208 -> 196
~ -[VTKBitmapContext image] : 124 -> 112
~ -[VTKBitmapContext colorAt:] : 88 -> 76
~ -[VTKBitmapContext colorForDifferent] : 120 -> 108
~ -[VTKBitmapContext colorForSame] : 100 -> 88
~ -[VTKBitmapContext colorForAntiAliased] : 120 -> 108
~ -[VTKBitmapContext drawColor:at:] : 128 -> 116
~ _VTKTransverseContexs : 324 -> 312
~ -[VTKAssetCatalogReferenceItemsSource referenceImageWithID:testCase:error:] : 448 -> 436
~ -[NSString(VTKID) vtkAssertName] : 40 -> 28
~ +[VTKColor colorWithRed:green:blue:alpha:] : 100 -> 88
~ ___VTKAssertView : 180 -> 168
~ -[VTKLineDrawItem drawAtContext:] : 300 -> 288
~ -[VTKSquareDrawItem drawAtContext:] : 152 -> 140
~ -[VTKExclusionAreaDrawItem drawAtContext:] : 72 -> 60
~ -[VTKAssert referenceImagesDirectory] : 88 -> 76
~ -[VTKAssert drawItems] : 88 -> 76
~ -[VTKAssert testCase] : 44 -> 32
~ -[VTKAssert .cxx_destruct] : 64 -> 52
~ -[VTKPixelMatchStrategy differenceBetweenColor:andColor:] : 204 -> 192
~ -[VTKPixelMatchStrategy antiAliasingDifferenceBetweenColor:andColor:] : 204 -> 192
~ -[XCTestCase(VisualTestKit) VisualTestKitAssert] : 124 -> 112
~ -[XCTestCase(VisualTestKit) VisualTestKitConfiguration] : 508 -> 496
~ ___55-[XCTestCase(VisualTestKit) VisualTestKitConfiguration]_block_invoke : 228 -> 216
~ ___55-[XCTestCase(VisualTestKit) VisualTestKitConfiguration]_block_invoke_2 : 68 -> 56
~ __saveItemsRootURLWithItemsDirectory : 212 -> 200
~ -[VTKFileStoreManager setItemsDirectory:] : 288 -> 276
~ -[VTKFileStoreManager saveItems:withID:testCase:] : 356 -> 344
~ ___49-[VTKFileStoreManager saveItems:withID:testCase:]_block_invoke : 180 -> 168
~ -[VTKFileStoreManager .cxx_destruct] : 68 -> 56
~ -[VTKFileStoreManagerResult saveDescription] : 152 -> 140
~ _VTKID : 108 -> 96
~ -[UIView(VTKSnapshot) vtk_Snapshot] : 56 -> 44
~ -[UIView(VTKSnapshot) vtk_SnapshotWithScale:] : 272 -> 260
```

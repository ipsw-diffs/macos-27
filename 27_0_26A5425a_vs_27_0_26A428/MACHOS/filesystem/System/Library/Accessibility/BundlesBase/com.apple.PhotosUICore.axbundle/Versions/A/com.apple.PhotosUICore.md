## com.apple.PhotosUICore

> `/System/Library/Accessibility/BundlesBase/com.apple.PhotosUICore.axbundle/Versions/A/com.apple.PhotosUICore`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x563c
+  __TEXT.__text: 0x539c
   __TEXT.__auth_stubs: 0x370
   __TEXT.__objc_stubs: 0x1060
   __TEXT.__objc_methlist: 0xcd8

   __TEXT.__gcc_except_tab: 0x10c
   __TEXT.__ustring: 0x4
   __TEXT.__oslogstring: 0xb
-  __TEXT.__unwind_info: 0x268
+  __TEXT.__unwind_info: 0x2c0
   __DATA_CONST.__const: 0x260
   __DATA_CONST.__cfstring: 0x1200
   __DATA_CONST.__objc_classlist: 0x138
Functions:
~ +[HomeSectionTungstenLayoutAccessibility _accessibilityPerformValidations:] : 400 -> 388
~ -[HomeSectionTungstenLayoutAccessibility axLocalizedLabel] : 272 -> 260
~ -[HomeSectionTungstenLayoutAccessibility _accessibilityPhotosCustomActions] : 384 -> 372
~ -[HomeSectionTungstenLayoutAccessibility _accessibilitySectionHeaderTungstenLayout] : 392 -> 380
~ +[PXGItemsLayoutAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[PXCuratedLibrarySectionHeaderLayoutAccessibility _accessibilityPerformValidations:] : 196 -> 184
~ +[HomeAlbumCellTungstenLayoutAccessibility _accessibilityPerformValidations:] : 424 -> 412
~ -[HomeAlbumCellTungstenLayoutAccessibility axSpriteIndexes] : 92 -> 80
~ -[HomeAlbumCellTungstenLayoutAccessibility _accessibilityLabelForSpriteIndex:] : 220 -> 208
~ +[PXPhotosLayoutAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[PXNSScrollViewAccessibility accessibilityContents] : 240 -> 228
~ +[PXCuratedLibraryOverlayButtonAccessibility _accessibilityPerformValidations:] : 208 -> 196
~ -[PXCuratedLibraryOverlayButtonAccessibility accessibilityLabel] : 220 -> 208
~ +[_PXScrollDocumentViewAccessibility _accessibilityPerformValidations:] : 204 -> 192
~ -[_PXScrollDocumentViewAccessibility accessibilityFocusedUIElement] : 700 -> 688
~ ___67-[_PXScrollDocumentViewAccessibility accessibilityFocusedUIElement]_block_invoke : 88 -> 76
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ +[PXPlacesMapThumbnailAnnotationViewAccessibility _accessibilityPerformValidations:] : 240 -> 228
~ -[PXPlacesMapThumbnailAnnotationViewAccessibility accessibilityLabel] : 316 -> 304
~ ___81-[PXPlacesMapThumbnailAnnotationViewAccessibility _accessibilityCreatePlaceLabel]_block_invoke : 348 -> 336
~ +[PXGReusableAXInfoAccessibility _accessibilityPerformValidations:] : 416 -> 404
~ +[PXGReusableAXInfoAccessibility _accessibilityImageDescriptionQueue] : 68 -> 56
~ ___69+[PXGReusableAXInfoAccessibility _accessibilityImageDescriptionQueue]_block_invoke : 72 -> 60
~ -[PXGReusableAXInfoAccessibility _accessibilityContainingLayout] : 184 -> 172
~ -[PXGReusableAXInfoAccessibility accessibilityLabel] : 184 -> 172
~ -[PXGReusableAXInfoAccessibility accessibilityRole] : 184 -> 172
~ -[PXGReusableAXInfoAccessibility accessibilityRoleDescription] : 300 -> 288
~ -[PXGReusableAXInfoAccessibility accessibilityEmbeddedImageDescription] : 764 -> 752
~ -[PXGReusableAXInfoAccessibility accessibilityAttributeValue:] : 468 -> 456
~ -[PXPhotosViewUXInteractionResponderAccessibility accessibilityFocusedUIElement] : 528 -> 516
~ ___80-[PXPhotosViewUXInteractionResponderAccessibility accessibilityFocusedUIElement]_block_invoke : 160 -> 148
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ +[HomePersonCellTungstenLayoutAccessibility _accessibilityPerformValidations:] : 396 -> 384
~ -[HomePersonCellTungstenLayoutAccessibility axSpriteIndexes] : 92 -> 80
~ -[HomePersonCellTungstenLayoutAccessibility _accessibilityLabelForSpriteIndex:] : 140 -> 128
~ +[PXGBasicAXGroupAccessibility _accessibilityPerformValidations:] : 208 -> 196
~ ___38-[PXGBasicAXGroupAccessibility axRole]_block_invoke : 92 -> 80
~ -[PXGBasicAXGroupAccessibility accessibilityCustomActions] : 88 -> 76
~ -[PXGBasicAXGroupAccessibility accessibilitySelectedChildren] : 428 -> 416
~ +[HomeCellTungstenLayoutAccessibility _accessibilityPerformValidations:] : 424 -> 412
~ -[HomeCellTungstenLayoutAccessibility axSpriteIndexes] : 92 -> 80
~ -[HomeCellTungstenLayoutAccessibility _accessibilityLabelForSpriteIndex:] : 180 -> 168
~ +[PXAssetsSectionLayoutAccessibility _accessibilityPerformValidations:] : 216 -> 204
~ -[PXAssetsSectionLayoutAccessibility axLocalizedLabel] : 248 -> 236
~ +[PXGLayoutAccessibility _accessibilityPerformValidations:] : 364 -> 352
~ ___32-[PXGLayoutAccessibility update]_block_invoke : 104 -> 92
~ -[PXGLayoutAccessibility axContentInfoAtSpriteIndex:] : 664 -> 652
~ ___59-[PXGLayoutAccessibility _accessibilityUpdateFocusIfNeeded]_block_invoke : 80 -> 68
~ +[AXPhotosUICoreGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___65+[AXPhotosUICoreGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___65+[AXPhotosUICoreGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 436 -> 424
~ _accessibilityLocalizedString : 184 -> 172
```

## com.apple.Photos

> `/System/Library/Accessibility/BundlesBase/com.apple.Photos.axbundle/Versions/A/com.apple.Photos`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x4100
+  __TEXT.__text: 0x3f38
   __TEXT.__auth_stubs: 0x280
   __TEXT.__objc_stubs: 0xba0
   __TEXT.__objc_methlist: 0xab4

   __TEXT.__cstring: 0xe56
   __TEXT.__objc_methname: 0x1201
   __TEXT.__objc_methtype: 0x351
-  __TEXT.__unwind_info: 0x1d8
+  __TEXT.__unwind_info: 0x218
   __DATA_CONST.__const: 0x218
   __DATA_CONST.__cfstring: 0x1440
   __DATA_CONST.__objc_classlist: 0x128
Functions:
~ +[IPXPeopleHomeCellAccessibility _accessibilityPerformValidations:] : 208 -> 196
~ -[IPXPeopleHomeCellAccessibility accessibilityLabel] : 272 -> 260
~ -[IPXPeopleHomeCellAccessibility accessibilityCustomActions] : 704 -> 692
~ -[IPXPeopleHomeCellAccessibility _accessibilityPersonName] : 324 -> 312
~ +[IPXSearchSuggestionsTableViewCellAccessibility _accessibilityPerformValidations:] : 296 -> 284
~ +[IPXCanvasItemViewAccessibility _accessibilityPerformValidations:] : 296 -> 284
~ +[IPXCanvasItemViewAccessibility _accessibilityImageDescriptionQueue] : 68 -> 56
~ ___69+[IPXCanvasItemViewAccessibility _accessibilityImageDescriptionQueue]_block_invoke : 72 -> 60
~ -[IPXCanvasItemViewAccessibility accessibilityChildren] : 172 -> 160
~ -[IPXCanvasItemViewAccessibility _axcEmbeddedImageDescription] : 868 -> 856
~ ___62-[IPXCanvasItemViewAccessibility _axcEmbeddedImageDescription]_block_invoke : 112 -> 100
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___55-[IPXCanvasItemViewAccessibility _axcInitAccessibility]_block_invoke : 80 -> 68
~ -[IPXCanvasItemViewAccessibility accessibilityAttributeValue:] : 492 -> 480
~ +[IPXFaceNameSuggestionCellViewAccessibility _accessibilityPerformValidations:] : 244 -> 232
~ ___71-[IPXFaceNameSuggestionCellViewAccessibility accessibilityPerformPress]_block_invoke : 88 -> 76
~ -[IPXFaceNameSuggestionCellViewAccessibility accessibilityLabel] : 396 -> 384
~ +[_IPXMediaSliderAccessibility _accessibilityPerformValidations:] : 156 -> 144
~ -[_IPXMediaSliderAccessibility accessibilityValueDescription] : 464 -> 452
~ -[_IPXMediaSliderAccessibility accessibilityValue] : 180 -> 168
~ +[IPXWhatsNewViewControllerAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ +[IPXSidebarCellViewAccessibility _accessibilityPerformValidations:] : 140 -> 128
~ ___77-[IPXSidebarCellViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 80 -> 68
~ +[AXPhotosGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXPhotosGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXPhotosGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 416 -> 404
~ _accessibilityLocalizedString : 184 -> 172
~ _accessibilityLabelForSearchUserCategory : 616 -> 604
~ +[IPXMetadataInfoPopoverPanelAccessibility _accessibilityPerformValidations:] : 212 -> 200
~ ___86-[IPXMetadataInfoPopoverPanelAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 172 -> 160
~ +[IPXFilterItemViewAccessibility _accessibilityPerformValidations:] : 228 -> 216
~ -[IPXFilterItemViewAccessibility accessibilityValue] : 76 -> 64
~ +[IPXSearchSuggestionsFieldCellAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ -[IPXSearchSuggestionsFieldCellAccessibility accessibilitySharedFocusElements] : 348 -> 336
~ +[IPXInfoPanelPeopleCollectionViewItemAccessibility _accessibilityPerformValidations:] : 168 -> 156
~ +[IPXInfoPanelPeopleViewControllerAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ -[IPXInfoPanelPeopleViewControllerAccessibility collectionView:itemForRepresentedObjectAtIndexPath:] : 420 -> 408
```

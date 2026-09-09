## com.apple.finder

> `/System/Library/Accessibility/BundlesBase/com.apple.finder.axbundle/Versions/A/com.apple.finder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x8210
+  __TEXT.__text: 0x7e44
   __TEXT.__auth_stubs: 0x330
   __TEXT.__objc_stubs: 0x1640
   __TEXT.__objc_methlist: 0xd5c

   __TEXT.__const: 0x48
   __TEXT.__gcc_except_tab: 0x80
   __TEXT.__oslogstring: 0x71
-  __TEXT.__unwind_info: 0x308
+  __TEXT.__unwind_info: 0x398
   __DATA_CONST.__const: 0x418
   __DATA_CONST.__cfstring: 0x1f80
   __DATA_CONST.__objc_classlist: 0x248
Functions:
~ +[TGoToResultTableCellViewAccessibility _accessibilityPerformValidations:] : 328 -> 316
~ +[NSTableViewCellMockElementAccessibility__Finder__AppKit _accessibilityPerformValidations:] : 156 -> 144
~ +[TContextMenuItemAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[TContextMenuItemAccessibility accessibilityAttributeValue:] : 272 -> 260
~ +[TListViewControllerAccessibility _accessibilityPerformValidations:] : 164 -> 152
~ +[TTaggingSuggestionsViewControllerAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[TIconViewAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ +[TDesktopMultiWindowControllerAccessibility _accessibilityPerformValidations:] : 168 -> 156
~ ___81-[TDesktopMultiWindowControllerAccessibility accessibilitySetValue:forAttribute:]_block_invoke : 76 -> 64
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ +[TListHeaderRowViewAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[TReturnToSenderPillViewAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[TReturnToSenderPillViewAccessibility accessibilityTitle] : 188 -> 176
~ +[TDesktopWidgetViewAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[TDesktopWidgetViewAccessibility _accessibilitySharedDispatchQueue] : 68 -> 56
~ ___68+[TDesktopWidgetViewAccessibility _accessibilitySharedDispatchQueue]_block_invoke : 72 -> 60
~ -[TDesktopWidgetViewAccessibility accessibilityChildren] : 172 -> 160
~ -[TDesktopWidgetViewAccessibility _accessibilityFetchWidgetElement] : 392 -> 380
~ ___67-[TDesktopWidgetViewAccessibility _accessibilityFetchWidgetElement]_block_invoke_2 : 212 -> 200
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___copy_helper_block_e8_32s40s48w : 76 -> 64
~ ___destroy_helper_block_e8_32s40s48w : 68 -> 56
~ -[TDesktopWidgetViewAccessibility _accessibilityUnregisterWidgetUIElement] : 216 -> 204
~ +[TIconCollectionViewControllerAccessibility _accessibilityPerformValidations:] : 256 -> 244
~ -[TBrowserWindowAccessibility accessibilitySections] : 896 -> 884
~ +[TNodeViewSettingsAccessibility _accessibilityPerformValidations:] : 464 -> 452
~ ___71-[TNodeViewSettingsAccessibility axUpdateViewSettingsToCurrentFontSize]_block_invoke : 68 -> 56
~ __71-[TNodeViewSettingsAccessibility axUpdateViewSettingsToCurrentFontSize]_block_invoke.409 : 148 -> 124
~ -[TNodeViewSettingsAccessibility _axMaybeUpdateFontSizeCategoryWithSize:] : 128 -> 116
~ -[TNodeViewSettingsAccessibility _axRefreshingOrProcessingFontSizeCategoryChange] : 84 -> 72
~ -[TTitleViewBadgeAccessibility accessibilityTitle] : 136 -> 124
~ +[TColumnViewControllerAccessibility _accessibilityPerformValidations:] : 316 -> 304
~ +[TGoToWindowAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ ___70-[TGoToWindowAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 172 -> 160
~ +[TSidebarItemCellAccessibility _accessibilityPerformValidations:] : 168 -> 156
~ ___75-[TSidebarItemCellAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 88 -> 76
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ +[AXFinderGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXFinderGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXFinderGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 812 -> 800
~ _accessibilityLocalizedString : 184 -> 172
~ +[TApplicationAccessibility _accessibilityPerformValidations:] : 444 -> 432
~ +[TApplicationAccessibility accessibilitySetupExistingObjects] : 96 -> 84
~ +[TApplicationAccessibility axApplication] : 148 -> 136
~ -[TApplicationAccessibility _axSetNewFontSize] : 184 -> 172
~ -[TApplicationAccessibility _axChangeTextAndIconSizesIn:to:withViewStyle:] : 828 -> 816
~ -[TApplicationAccessibility axUpdateFontSizeCategoryWithSize:] : 116 -> 104
~ -[TApplicationAccessibility axSetFontSizeCategoryToCustom] : 96 -> 84
~ +[TBaseBrowserViewControllerAccessibility _accessibilityPerformValidations:] : 156 -> 144
~ +[TIconViewSettingsAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ +[TDesktopViewControllerAccessibility _accessibilityPerformValidations:] : 188 -> 176
~ -[TDesktopViewControllerAccessibility accessibilityAttributeValue:] : 552 -> 540
~ ___67-[TDesktopViewControllerAccessibility accessibilityAttributeValue:]_block_invoke : 104 -> 92
~ +[TListViewAccessibility _accessibilityPerformValidations:] : 264 -> 252
~ ___53-[TListViewAccessibility accessibilityPerformAction:]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[NSFontManagerAccessibility__Finder__AppKit convertFont:toSize:] : 160 -> 148
~ +[TTaggingTokenFieldAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ -[TTaggingTokenFieldAccessibility accessibilitySharedFocusElements] : 116 -> 104
~ +[TGalleryCollectionViewControllerAccessibility _accessibilityPerformValidations:] : 328 -> 316
~ +[TDesktopIconViewAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ +[TBrowserContainerControllerAccessibility _accessibilityPerformValidations:] : 364 -> 352
~ -[TBrowserContainerControllerAccessibility nodeViewSettings] : 176 -> 164
~ -[TBrowserContainerControllerAccessibility _axcBrowserWindow] : 456 -> 444
~ ___61-[TBrowserContainerControllerAccessibility _axcBrowserWindow]_block_invoke : 80 -> 68
~ -[TBrowserContainerControllerAccessibility _axcSidebarView] : 288 -> 276
~ +[TDesktopMultiViewControllerAccessibility _accessibilityPerformValidations:] : 220 -> 208
~ ___91-[TDesktopMultiViewControllerAccessibility accessibilitySetSelectedChildrenAttributeValue:]_block_invoke : 116 -> 104
~ -[TDesktopMultiViewControllerAccessibility accessibilityAttributeNames] : 168 -> 156
~ -[TDesktopMultiViewControllerAccessibility accessibilityAttributeValue:] : 292 -> 280
~ -[TDesktopMultiViewControllerAccessibility rotor:resultForSearchParameters:] : 776 -> 764
~ +[TListViewSettingsAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ +[TListHeaderCellViewAccessibility _accessibilityPerformValidations:] : 144 -> 132
~ -[TListHeaderCellViewAccessibility accessibilityLabel] : 480 -> 468
~ -[TListHeaderCellViewAccessibility _axcSelfAsTableCell] : 108 -> 96
~ -[TSplitViewAccessibility accessibilityChildrenInNavigationOrder] : 508 -> 496
```

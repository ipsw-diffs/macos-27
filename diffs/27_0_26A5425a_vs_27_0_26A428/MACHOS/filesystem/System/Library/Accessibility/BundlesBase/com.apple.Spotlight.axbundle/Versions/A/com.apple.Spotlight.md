## com.apple.Spotlight

> `/System/Library/Accessibility/BundlesBase/com.apple.Spotlight.axbundle/Versions/A/com.apple.Spotlight`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x1268
+  __TEXT.__text: 0x11d8
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x400
   __TEXT.__objc_methlist: 0x1ec

   __TEXT.__objc_methname: 0x478
   __TEXT.__objc_methtype: 0x60
   __TEXT.__const: 0x8
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x5e0
   __DATA_CONST.__objc_classlist: 0x68
Functions:
~ +[AXSpotlightGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___62+[AXSpotlightGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___62+[AXSpotlightGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 188 -> 176
~ _accessibilityLocalizedString : 184 -> 172
~ +[SearchFieldCellAccessibility _accessibilityPerformValidations:] : 148 -> 136
~ -[SearchFieldCellAccessibility accessibilitySharedFocusElements] : 280 -> 268
~ +[SPSpotlightMenuItemAccessibility _accessibilityPerformValidations:] : 164 -> 152
~ +[SPSpotlightPanelAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ +[SearchViewControllerAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[SPAppDelegateAccessibility _accessibilityPerformValidations:] : 380 -> 368
~ -[SPAppDelegateAccessibility _axbSearchResultCollectionView] : 264 -> 252
~ +[SPResultWithoutSubitemsHelperAccessibility _accessibilityPerformValidations:] : 272 -> 260
```

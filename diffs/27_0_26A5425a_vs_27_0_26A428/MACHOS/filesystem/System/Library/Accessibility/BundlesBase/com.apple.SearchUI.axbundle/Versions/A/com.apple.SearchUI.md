## com.apple.SearchUI

> `/System/Library/Accessibility/BundlesBase/com.apple.SearchUI.axbundle/Versions/A/com.apple.SearchUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x1634
+  __TEXT.__text: 0x1568
   __TEXT.__auth_stubs: 0x140
   __TEXT.__objc_stubs: 0x500
   __TEXT.__objc_methlist: 0x2dc

   __TEXT.__objc_methtype: 0x44
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x18
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__const: 0x110
   __DATA_CONST.__cfstring: 0x600
   __DATA_CONST.__objc_classlist: 0x98
Functions:
~ +[SearchUIFirstTimeExperienceViewControllerAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ +[SearchUICardSectionCollectionViewItemAccessibility _accessibilityPerformValidations:] : 252 -> 240
~ +[SearchUIHeroButtonViewAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[NSCollectionViewSectionAccessibilityAccessibility__SearchUI__AppKit _accessibilityPerformValidations:] : 280 -> 268
~ -[NSCollectionViewSectionAccessibilityAccessibility__SearchUI__AppKit _axcLabelFromBundle:] : 144 -> 132
~ -[NSCollectionViewSectionAccessibilityAccessibility__SearchUI__AppKit accessibilityCustomActions] : 304 -> 292
~ -[NSCollectionViewSectionAccessibilityAccessibility__SearchUI__AppKit accessibilityLabel] : 1276 -> 1264
~ ___89-[NSCollectionViewSectionAccessibilityAccessibility__SearchUI__AppKit accessibilityLabel]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ +[AXSearchUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___61+[AXSearchUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___61+[AXSearchUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 236 -> 224
~ _accessibilityLocalizedString : 184 -> 172
~ +[SearchUICardSectionViewAccessibility _accessibilityPerformValidations:] : 148 -> 136
~ +[SearchUIInlineActionButtonAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[SearchUIInlineActionButtonAccessibility accessibilityLabel] : 148 -> 136
```

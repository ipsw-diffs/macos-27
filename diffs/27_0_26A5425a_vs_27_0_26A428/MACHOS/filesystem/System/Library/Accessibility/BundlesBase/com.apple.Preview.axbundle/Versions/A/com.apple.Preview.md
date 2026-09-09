## com.apple.Preview

> `/System/Library/Accessibility/BundlesBase/com.apple.Preview.axbundle/Versions/A/com.apple.Preview`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x8b0
+  __TEXT.__text: 0x850
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x2e0
   __TEXT.__objc_methlist: 0xb0

   __TEXT.__objc_classname: 0xc5
   __TEXT.__objc_methname: 0x312
   __TEXT.__objc_methtype: 0x39
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x2a0
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ +[AXPreviewGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___60+[AXPreviewGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___60+[AXPreviewGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 96 -> 84
~ _accessibilityLocalizedString : 184 -> 172
~ +[PVWindowAccessibility _accessibilityPerformValidations:] : 332 -> 320
~ -[PVWindowAccessibility accessibilityHitTest:] : 180 -> 168
~ -[PVWindowAccessibility accessibilityFocusedUIElement] : 752 -> 740
~ +[PVFormFillingCoachingBannerViewControllerAccessibility _accessibilityPerformValidations:] : 144 -> 132
```

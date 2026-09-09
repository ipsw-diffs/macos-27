## com.apple.AuthKitUI

> `/System/Library/Accessibility/BundlesBase/com.apple.AuthKitUI.axbundle/Versions/A/com.apple.AuthKitUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x10a0
+  __TEXT.__text: 0x101c
   __TEXT.__auth_stubs: 0x130
   __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x1c4

   __TEXT.__objc_classname: 0x1d1
   __TEXT.__objc_methname: 0x46e
   __TEXT.__objc_methtype: 0x36
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__const: 0x100
   __DATA_CONST.__cfstring: 0x3c0
   __DATA_CONST.__objc_classlist: 0x58
Functions:
~ +[AXAuthKitUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___62+[AXAuthKitUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___62+[AXAuthKitUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 188 -> 176
~ _accessibilityLocalizedString : 184 -> 172
~ +[AKPinFieldBoxUIElementAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[AKPinFieldBoxUIElementAccessibility _accessibilityFallbackValue] : 260 -> 248
~ -[AKPinFieldBoxUIElementAccessibility accessibilityAttributeValue:] : 360 -> 348
~ +[AKDefaultSignInPromptViewControllerAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ +[NSImageCellAccessibility__AuthKitUI__AppKit _accessibilityPerformValidations:] : 136 -> 124
~ -[NSImageCellAccessibility__AuthKitUI__AppKit accessibilityDescriptionAttribute] : 192 -> 180
~ +[AKTooManyAttemptsControllerAccessibility _accessibilityPerformValidations:] : 124 -> 112
```

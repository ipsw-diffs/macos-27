## com.apple.controlcenter

> `/System/Library/Accessibility/BundlesBase/com.apple.controlcenter.axbundle/Versions/A/com.apple.controlcenter`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xda4
+  __TEXT.__text: 0xd2c
   __TEXT.__auth_stubs: 0x150
   __TEXT.__objc_stubs: 0x3c0
   __TEXT.__objc_methlist: 0x224

   __TEXT.__objc_methname: 0x447
   __TEXT.__objc_methtype: 0x36
   __TEXT.__const: 0x8
-  __TEXT.__unwind_info: 0xb0
+  __TEXT.__unwind_info: 0xc0
   __DATA_CONST.__const: 0x150
   __DATA_CONST.__cfstring: 0x4c0
   __DATA_CONST.__objc_classlist: 0x78
Functions:
~ +[AXControlCenterGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___66+[AXControlCenterGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___66+[AXControlCenterGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 196 -> 184
~ _accessibilityLocalizedString : 184 -> 172
~ +[AccessibilityNodeAccessibility__ControlCenter__SwiftUI _accessibilityPerformValidations:] : 144 -> 132
~ -[AccessibilityNodeAccessibility__ControlCenter__SwiftUI accessibilityLabel] : 508 -> 496
~ +[ApplicationAccessibility _accessibilityPerformValidations:] : 148 -> 136
~ -[ApplicationAccessibility accessibilityActionNames] : 144 -> 132
~ +[NSWindowAccessibility__ControlCenter__AppKit _accessibilityPerformValidations:] : 116 -> 104
~ -[NSWindowAccessibility__ControlCenter__AppKit accessibilitySubroleAttribute] : 116 -> 104
```

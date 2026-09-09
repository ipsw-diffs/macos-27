## com.apple.calculator

> `/System/Library/Accessibility/BundlesBase/com.apple.calculator.axbundle/Versions/A/com.apple.calculator`

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
-  __TEXT.__text: 0xfc4
+  __TEXT.__text: 0xf4c
   __TEXT.__auth_stubs: 0x110
   __TEXT.__objc_stubs: 0x380
   __TEXT.__objc_methlist: 0x148

   __TEXT.__objc_methtype: 0x39
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x30
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x2e0
   __DATA_CONST.__objc_classlist: 0x48
Functions:
~ +[AXCalculatorGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXCalculatorGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___63+[AXCalculatorGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 148 -> 136
~ _accessibilityLocalizedString : 184 -> 172
~ +[BasicAdvancedTouchBarControllerAccessibility _accessibilityPerformValidations:] : 172 -> 160
~ -[BasicAdvancedTouchBarControllerAccessibility touchBar:makeItemForIdentifier:] : 792 -> 780
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ +[HexadecimalTouchBarControllerAccessibility _accessibilityPerformValidations:] : 172 -> 160
~ -[HexadecimalTouchBarControllerAccessibility touchBar:makeItemForIdentifier:] : 792 -> 780
```

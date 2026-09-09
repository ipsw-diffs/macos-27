## com.apple.AddressBook

> `/System/Library/Accessibility/BundlesBase/com.apple.AddressBook.axbundle/Versions/A/com.apple.AddressBook`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x1f8c
+  __TEXT.__text: 0x1e90
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__objc_stubs: 0x7a0
   __TEXT.__objc_methlist: 0x384

   __TEXT.__objc_methtype: 0x39
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x2c
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x900
   __DATA_CONST.__objc_classlist: 0xa8
Functions:
~ -[CNFunctionBarControllerAccessibility _axcContactViewTouchBar] : 164 -> 152
~ +[ABCardWindowControllerAccessibility _accessibilityPerformValidations:] : 244 -> 232
~ +[ABCleanWindowControllerAccessibility _accessibilityPerformValidations:] : 268 -> 256
~ ___82-[ABCleanWindowControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 216 -> 204
~ -[CNQuickActionViewAccessibility _axcActionButton] : 312 -> 300
~ ___50-[CNQuickActionViewAccessibility _axcActionButton]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ +[NSButtonCellAccessibility__AddressBook__AppKit _accessibilityPerformValidations:] : 132 -> 120
~ +[ABCleanWindowAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[CNQuickActionViewClickHelperAccessibility _accessibilityPerformValidations:] : 180 -> 168
~ -[CNQuickActionViewClickHelperAccessibility _axcQuickActionView] : 164 -> 152
~ +[AXAddressBookGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___64+[AXAddressBookGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___64+[AXAddressBookGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 288 -> 276
~ _accessibilityLocalizedString : 184 -> 172
~ +[CNContactViewTouchBarAccessibility _accessibilityPerformValidations:] : 180 -> 168
~ +[CNContactViewTouchBarAccessibility _axcCNContactViewTouchBarInstance] : 780 -> 768
~ +[CNContactViewTouchBarAccessibility accessibilitySetupExistingObjects] : 96 -> 84
~ -[CNContactViewTouchBarAccessibility _axcShareItem] : 164 -> 152
~ +[ABPersonListCellViewAccessibility _accessibilityPerformValidations:] : 204 -> 192
```

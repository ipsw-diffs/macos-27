## com.apple.ContactsUI

> `/System/Library/Accessibility/BundlesBase/com.apple.ContactsUI.axbundle/Versions/A/com.apple.ContactsUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x1234
+  __TEXT.__text: 0x11c8
   __TEXT.__auth_stubs: 0x110
   __TEXT.__objc_stubs: 0x4c0
   __TEXT.__objc_methlist: 0x1dc

   __TEXT.__objc_classname: 0x1a2
   __TEXT.__objc_methname: 0x4a1
   __TEXT.__objc_methtype: 0x2b
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__const: 0xb0
   __DATA_CONST.__cfstring: 0x580
   __DATA_CONST.__objc_classlist: 0x58
Functions:
~ +[AXContactsUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXContactsUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___63+[AXContactsUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 156 -> 144
~ _accessibilityLocalizedString : 184 -> 172
~ +[CNContactIconViewAccessibility _accessibilityPerformValidations:] : 208 -> 196
~ -[CNContactIconViewAccessibility accessibilityRole] : 68 -> 56
~ -[CNContactIconViewAccessibility accessibilityLabel] : 372 -> 360
~ -[CNContactIconViewAccessibility accessibilityHelp] : 116 -> 104
~ +[CNContactLikenessViewAccessibility _accessibilityPerformValidations:] : 316 -> 304
```

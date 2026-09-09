## com.apple.ParsecUI

> `/System/Library/Accessibility/BundlesBase/com.apple.ParsecUI.axbundle/Versions/A/com.apple.ParsecUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x10a0
+  __TEXT.__text: 0x1004
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x1f4

   __TEXT.__cstring: 0x344
   __TEXT.__objc_methname: 0x481
   __TEXT.__objc_methtype: 0x23
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x5a0
   __DATA_CONST.__objc_classlist: 0x68
Functions:
~ -[NSImageAccessibility__ParsecUI__AppKit __accessibilityDescriptionParsec] : 856 -> 844
~ -[NSImageAccessibility__ParsecUI__AppKit accessibilityDescription] : 152 -> 140
~ +[AXParsecUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___61+[AXParsecUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___61+[AXParsecUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 176 -> 164
~ _accessibilityLocalizedString : 184 -> 172
~ +[PRSParsecResultAccessibility _accessibilityPerformValidations:] : 320 -> 308
~ -[PRSParsecResultAccessibility _accessibilityHeaderDisplayName] : 164 -> 152
~ -[PRSParsecResultAccessibility _accessibilityGroupName] : 164 -> 152
~ -[PRSParsecResultAccessibility _accessibilityDisplayName] : 164 -> 152
~ -[PRSParsecResultAccessibility _accessibilityCompletionIconLabel] : 716 -> 704
~ +[PRSAssistantPreviewControllerAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[PRSAssistantPreviewControllerAccessibility _accessibilitySliceTable] : 164 -> 152
```

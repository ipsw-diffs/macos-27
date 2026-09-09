## com.apple.MessagesAppKitBridge

> `/System/Library/Accessibility/BundlesBase/com.apple.MessagesAppKitBridge.axbundle/Versions/A/com.apple.MessagesAppKitBridge`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xcb4
+  __TEXT.__text: 0xc30
   __TEXT.__auth_stubs: 0x120
   __TEXT.__objc_stubs: 0x520
   __TEXT.__objc_methlist: 0x194

   __TEXT.__objc_methname: 0x581
   __TEXT.__objc_methtype: 0x57
   __TEXT.__oslogstring: 0x71
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x40
Functions:
~ +[CKiMessageDetailsViewControllerAccessibility _accessibilityPerformValidations:] : 260 -> 248
~ -[CKiMessageDetailsViewControllerAccessibility tableView:viewForTableColumn:row:] : 668 -> 656
~ -[CKAliasCheckboxMockElement accessibilityLabel] : 224 -> 212
~ -[CKAliasCheckboxMockElement accessibilityValue] : 100 -> 88
~ -[CKAliasCheckboxMockElement .cxx_destruct] : 84 -> 72
~ +[CKPrefsGeneralAccessibility accessibilitySetupExistingObjects] : 60 -> 48
~ ___61+[CKPrefsGeneralAccessibility _axcFontSizeCategoryDidChange:]_block_invoke : 124 -> 112
~ +[AXMessagesAppKitBridgeGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___73+[AXMessagesAppKitBridgeGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___73+[AXMessagesAppKitBridgeGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 128 -> 116
~ _accessibilityLocalizedString : 184 -> 172
```

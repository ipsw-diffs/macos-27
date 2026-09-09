## com.apple.framework.accountsui

> `/System/Library/Accessibility/BundlesBase/com.apple.framework.accountsui.axbundle/Versions/A/com.apple.framework.accountsui`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x2a64
+  __TEXT.__text: 0x298c
   __TEXT.__auth_stubs: 0x160
   __TEXT.__objc_stubs: 0x640
   __TEXT.__objc_methlist: 0x2a4

   __TEXT.__objc_methtype: 0x42
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x18
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x128
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x600
   __DATA_CONST.__objc_classlist: 0x78
Functions:
~ +[ACUIViewControllerAccessibility _accessibilityPerformValidations:] : 152 -> 140
~ +[ACUITableCellViewAccessibility _accessibilityPerformValidations:] : 148 -> 136
~ +[ACUIAccountSetupViewControllerAccessibility _accessibilityPerformValidations:] : 292 -> 280
~ -[ACUIAccountSetupViewControllerAccessibility _axcDataclassConfigurationSlice] : 156 -> 144
~ +[ACUIAccountDetailsViewControllerAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[ACUISetupManagerViewControllerAccessibility tableView:viewForTableColumn:row:] : 360 -> 348
~ +[ACUIAccountInfoViewControllerAccessibility _accessibilityPerformValidations:] : 496 -> 484
~ -[ACUIAccountInfoViewControllerAccessibility _axcDataclassesTableView] : 312 -> 300
~ ___70-[ACUIAccountInfoViewControllerAccessibility _axcDataclassesTableView]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[ACUIAccountInfoViewControllerAccessibility _axcDescriptionField] : 128 -> 116
~ -[ACUIAccountInfoViewControllerAccessibility _axcSelfAsView] : 72 -> 60
~ +[AXAccountsUIXGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___64+[AXAccountsUIXGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___64+[AXAccountsUIXGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 208 -> 196
~ _accessibilityLocalizedString : 184 -> 172
~ -[ACUIAccountTypesViewControllerAccessibility tableView:viewForTableColumn:row:] : 616 -> 604
```

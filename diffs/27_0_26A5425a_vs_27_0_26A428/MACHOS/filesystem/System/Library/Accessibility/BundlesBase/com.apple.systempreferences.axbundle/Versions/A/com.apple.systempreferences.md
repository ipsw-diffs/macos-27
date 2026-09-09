## com.apple.systempreferences

> `/System/Library/Accessibility/BundlesBase/com.apple.systempreferences.axbundle/Versions/A/com.apple.systempreferences`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x880
+  __TEXT.__text: 0x814
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__objc_stubs: 0x2a0
   __TEXT.__objc_methlist: 0x10c

   __TEXT.__cstring: 0x2cf
   __TEXT.__objc_methname: 0x339
   __TEXT.__objc_methtype: 0x2e
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__cfstring: 0x2a0
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ +[FocusableSearchFieldAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ -[FocusableSearchFieldAccessibility accessibilitySharedFocusElements] : 380 -> 368
~ -[FocusableSearchFieldAccessibility accessibilityHelp] : 316 -> 304
~ +[SearchSuggestionsViewControllerAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[SearchResultsHostingViewAccessibility accessibilitySelectedChildren] : 172 -> 160
~ +[AXSystemSettingsGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___67+[AXSystemSettingsGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___67+[AXSystemSettingsGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 116 -> 104
~ _accessibilityLocalizedString : 184 -> 172
```

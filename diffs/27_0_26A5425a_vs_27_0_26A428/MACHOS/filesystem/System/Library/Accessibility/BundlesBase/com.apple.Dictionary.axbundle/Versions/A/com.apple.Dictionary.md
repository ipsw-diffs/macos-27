## com.apple.Dictionary

> `/System/Library/Accessibility/BundlesBase/com.apple.Dictionary.axbundle/Versions/A/com.apple.Dictionary`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x618
+  __TEXT.__text: 0x5b8
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__objc_stubs: 0x240
   __TEXT.__objc_methlist: 0x5c

   __TEXT.__objc_classname: 0x62
   __TEXT.__objc_methname: 0x29b
   __TEXT.__objc_methtype: 0x23
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ +[DSIndexTableCellAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ -[DSIndexTableCellAccessibility accessibilityValue] : 632 -> 620
~ ___51-[DSIndexTableCellAccessibility accessibilityValue]_block_invoke : 120 -> 108
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ +[AXDictionaryGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXDictionaryGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

## com.apple.qldisplay.Image

> `/System/Library/Accessibility/BundlesBase/com.apple.qldisplay.Image.axbundle/Versions/A/com.apple.qldisplay.Image`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x838
+  __TEXT.__text: 0x7c0
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x220
   __TEXT.__objc_methlist: 0x74

   __TEXT.__cstring: 0x105
   __TEXT.__objc_methname: 0x274
   __TEXT.__objc_methtype: 0x23
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ +[QLImageViewAccessibility _accessibilityPerformValidations:] : 224 -> 212
~ -[QLImageViewAccessibility accessibilityIdentifier] : 188 -> 176
~ -[QLImageViewAccessibility accessibilityLabel] : 188 -> 176
~ -[QLImageViewAccessibility accessibilityEmbeddedImageDescription] : 716 -> 704
~ ___65-[QLImageViewAccessibility accessibilityEmbeddedImageDescription]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ +[AXQuickLookImagePluginGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___73+[AXQuickLookImagePluginGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

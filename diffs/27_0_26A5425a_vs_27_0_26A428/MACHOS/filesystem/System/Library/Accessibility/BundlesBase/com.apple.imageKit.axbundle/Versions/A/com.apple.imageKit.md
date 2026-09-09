## com.apple.imageKit

> `/System/Library/Accessibility/BundlesBase/com.apple.imageKit.axbundle/Versions/A/com.apple.imageKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x3a4
+  __TEXT.__text: 0x368
   __TEXT.__auth_stubs: 0xa0
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__objc_methlist: 0x74
Functions:
~ +[IKImageView2Accessibility _accessibilityPerformValidations:] : 200 -> 188
~ -[IKImageView2Accessibility accessibilityCustomActions] : 212 -> 200
~ +[AXImageKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___61+[AXImageKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

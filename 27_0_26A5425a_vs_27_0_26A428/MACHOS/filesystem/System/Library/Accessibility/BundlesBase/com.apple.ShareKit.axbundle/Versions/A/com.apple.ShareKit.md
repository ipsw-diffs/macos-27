## com.apple.ShareKit

> `/System/Library/Accessibility/BundlesBase/com.apple.ShareKit.axbundle/Versions/A/com.apple.ShareKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x6ac
+  __TEXT.__text: 0x664
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x260
   __TEXT.__objc_methlist: 0xf4

   __TEXT.__objc_classname: 0xfa
   __TEXT.__objc_methname: 0x2cc
   __TEXT.__objc_methtype: 0x2b
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0x88
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x260
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ +[AXShareKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___61+[AXShareKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___61+[AXShareKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 116 -> 104
~ _accessibilityLocalizedString : 184 -> 172
~ +[SHKSharingServiceAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ +[SHKRemoteWindowAccessibility _accessibilityPerformValidations:] : 184 -> 172
```

## com.apple.FinderKit

> `/System/Library/Accessibility/BundlesBase/com.apple.FinderKit.axbundle/Versions/A/com.apple.FinderKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x5f0
+  __TEXT.__text: 0x5a8
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x260
   __TEXT.__objc_methlist: 0xbc

   __TEXT.__cstring: 0x165
   __TEXT.__objc_methname: 0x2d4
   __TEXT.__objc_methtype: 0x37
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0x90
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x1e0
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ +[FIAirDropListViewCellViewAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[FIAirDropListViewCellViewAccessibility accessibilityLabel] : 436 -> 424
~ +[AXFinderKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___62+[AXFinderKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___62+[AXFinderKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 96 -> 84
~ _accessibilityLocalizedString : 184 -> 172
```

## com.apple.LinkPresentation

> `/System/Library/Accessibility/BundlesBase/com.apple.LinkPresentation.axbundle/Versions/A/com.apple.LinkPresentation`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x48c
+  __TEXT.__text: 0x444
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__objc_methlist: 0x80
Functions:
~ +[LPCollaborationFooterViewAccessibility _accessibilityPerformValidations:] : 172 -> 160
~ -[LPCollaborationFooterViewAccessibility accessibilityRole] : 96 -> 84
~ -[LPCollaborationFooterViewAccessibility accessibilityLabel] : 384 -> 372
~ +[AXLinkPresentationGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___69+[AXLinkPresentationGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

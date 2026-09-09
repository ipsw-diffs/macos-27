## com.apple.ConsoleKit

> `/System/Library/Accessibility/BundlesBase/com.apple.ConsoleKit.axbundle/Versions/A/com.apple.ConsoleKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x344
+  __TEXT.__text: 0x308
   __TEXT.__auth_stubs: 0x80
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__objc_methlist: 0x5c
Functions:
~ +[AXConsoleKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXConsoleKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
~ +[CSKTokenAttachmentCellAccessibility _accessibilityPerformValidations:] : 164 -> 152
~ -[CSKTokenAttachmentCellAccessibility accessibilityValue] : 176 -> 164
```

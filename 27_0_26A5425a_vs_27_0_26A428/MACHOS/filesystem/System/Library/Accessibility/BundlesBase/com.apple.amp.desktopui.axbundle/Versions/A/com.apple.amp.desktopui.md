## com.apple.amp.desktopui

> `/System/Library/Accessibility/BundlesBase/com.apple.amp.desktopui.axbundle/Versions/A/com.apple.amp.desktopui`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x4e0
+  __TEXT.__text: 0x48c
   __TEXT.__auth_stubs: 0xb0
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__objc_methlist: 0xbc
Functions:
~ +[AMPDeviceRootViewAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ -[AMPDeviceRootViewAccessibility accessibilityLabel] : 124 -> 112
~ +[AMPFilterBarViewControllerAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[AXAMPDesktopUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___65+[AXAMPDesktopUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___65+[AXAMPDesktopUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 96 -> 84
~ _accessibilityLocalizedString : 184 -> 172
```

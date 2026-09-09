## com.apple.systemuiserver

> `/System/Library/Accessibility/BundlesBase/com.apple.systemuiserver.axbundle/Versions/A/com.apple.systemuiserver`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x54c
+  __TEXT.__text: 0x4f8
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x260
   __TEXT.__objc_methlist: 0x74
Functions:
~ +[_MenuExtraViewAccessibility _accessibilityPerformValidations:] : 172 -> 160
~ -[_MenuExtraViewAccessibility _axTimeMachineMenuExtra] : 256 -> 244
~ -[_MenuExtraViewAccessibility accessibilityTitle] : 160 -> 148
~ -[_MenuExtraViewAccessibility accessibilityValue] : 272 -> 260
~ +[AXSystemUIServerGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___67+[AXSystemUIServerGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

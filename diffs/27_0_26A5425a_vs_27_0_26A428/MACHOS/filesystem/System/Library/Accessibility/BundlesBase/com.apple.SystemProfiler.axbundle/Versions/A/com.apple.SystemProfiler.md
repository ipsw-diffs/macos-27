## com.apple.SystemProfiler

> `/System/Library/Accessibility/BundlesBase/com.apple.SystemProfiler.axbundle/Versions/A/com.apple.SystemProfiler`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x2e8
+  __TEXT.__text: 0x2b8
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x160
   __TEXT.__objc_methlist: 0x5c
Functions:
~ -[NSWindowAccessibility_SystemInformation__AppKit accessibilityTitle] : 232 -> 220
~ +[AXSystemInformationGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___70+[AXSystemInformationGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

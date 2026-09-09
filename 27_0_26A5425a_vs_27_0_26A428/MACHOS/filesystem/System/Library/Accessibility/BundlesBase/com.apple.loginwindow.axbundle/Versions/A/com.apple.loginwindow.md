## com.apple.loginwindow

> `/System/Library/Accessibility/BundlesBase/com.apple.loginwindow.axbundle/Versions/A/com.apple.loginwindow`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x694
+  __TEXT.__text: 0x628
   __TEXT.__auth_stubs: 0xd0
   __TEXT.__objc_stubs: 0x2a0
   __TEXT.__objc_methlist: 0x10c

   __TEXT.__cstring: 0x1bc
   __TEXT.__objc_methname: 0x2df
   __TEXT.__objc_methtype: 0x36
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x260
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ +[LogoutUIWindowAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[LogoutUIWindowAccessibility accessibilityTitle] : 300 -> 288
~ -[NSWindowAccessibility__LoginWindow__AppKit accessibilityAttributeNames] : 148 -> 136
~ -[NSWindowAccessibility__LoginWindow__AppKit accessibilityAttributeValue:] : 180 -> 168
~ +[NSPanelAccessibility__LoginWindow__AppKit _accessibilityPerformValidations:] : 128 -> 116
~ +[AXLoginWindowGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___64+[AXLoginWindowGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___64+[AXLoginWindowGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 116 -> 104
~ _accessibilityLocalizedString : 184 -> 172
```

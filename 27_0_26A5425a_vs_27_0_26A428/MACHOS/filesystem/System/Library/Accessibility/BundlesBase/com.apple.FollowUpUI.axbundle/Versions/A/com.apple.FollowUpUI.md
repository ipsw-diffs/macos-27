## com.apple.FollowUpUI

> `/System/Library/Accessibility/BundlesBase/com.apple.FollowUpUI.axbundle/Versions/A/com.apple.FollowUpUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x4f4
+  __TEXT.__text: 0x4a0
   __TEXT.__auth_stubs: 0xa0
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__objc_methlist: 0xac
Functions:
~ +[FLUIBasicNotificationWindowControllerAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[FLUIBasicNotificationWindowControllerAccessibility _axcSelfAsWindowController] : 108 -> 96
~ +[FLUIHelperCodeWindowControllerAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[AXFollowUpUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXFollowUpUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___63+[AXFollowUpUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 96 -> 84
~ _accessibilityLocalizedString : 184 -> 172
```

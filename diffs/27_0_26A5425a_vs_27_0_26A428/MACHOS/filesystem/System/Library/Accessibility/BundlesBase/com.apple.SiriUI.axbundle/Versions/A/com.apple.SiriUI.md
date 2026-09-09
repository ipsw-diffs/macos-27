## com.apple.SiriUI

> `/System/Library/Accessibility/BundlesBase/com.apple.SiriUI.axbundle/Versions/A/com.apple.SiriUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x12e4
+  __TEXT.__text: 0x123c
   __TEXT.__auth_stubs: 0x160
   __TEXT.__objc_stubs: 0x480
   __TEXT.__objc_methlist: 0x3b0

   __TEXT.__objc_methtype: 0x54
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x14
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x140
   __DATA_CONST.__cfstring: 0x680
   __DATA_CONST.__objc_classlist: 0xa8
Functions:
~ -[SiriSharedUISystemAssistantExperienceContainerViewAccessibility accessibilityChildren] : 120 -> 108
~ -[SiriUITalkGestureTargetAccessibility accessibilityAttributeNames] : 168 -> 156
~ -[SiriUITalkGestureTargetAccessibility accessibilityAttributeValue:] : 148 -> 136
~ -[SiriUITextInputFieldCellAccessibility accessibilityAttributeNames] : 148 -> 136
~ -[SiriUITextInputFieldCellAccessibility accessibilityAttributeValue:] : 148 -> 136
~ +[SiriUISiriStatusViewAccessibility _accessibilityPerformValidations:] : 232 -> 220
~ +[AXSiriUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXSiriUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXSiriUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 256 -> 244
~ _accessibilityLocalizedString : 184 -> 172
~ +[SiriUISiriViewAccessibility _accessibilityPerformValidations:] : 264 -> 252
~ -[SiriUISiriViewAccessibility accessibilityAttributeNames] : 184 -> 172
~ -[SiriUISiriViewAccessibility accessibilityAttributeValue:] : 148 -> 136
~ -[SiriUISiriViewAccessibility accessibilityActionNames] : 168 -> 156
```

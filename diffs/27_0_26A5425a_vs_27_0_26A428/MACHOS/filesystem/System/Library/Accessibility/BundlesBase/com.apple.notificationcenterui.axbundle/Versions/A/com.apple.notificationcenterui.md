## com.apple.notificationcenterui

> `/System/Library/Accessibility/BundlesBase/com.apple.notificationcenterui.axbundle/Versions/A/com.apple.notificationcenterui`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x2130
+  __TEXT.__text: 0x2040
   __TEXT.__auth_stubs: 0x1c0
   __TEXT.__objc_stubs: 0x720
   __TEXT.__objc_methlist: 0x244

   __TEXT.__cstring: 0x890
   __TEXT.__objc_methname: 0x74a
   __TEXT.__objc_methtype: 0x44
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x118
   __DATA_CONST.__const: 0x1a0
   __DATA_CONST.__cfstring: 0x880
   __DATA_CONST.__objc_classlist: 0x68
Functions:
~ +[AccessibilityNodeAccessibility__NotificationCenterUI_SwiftUI _accessibilityPerformValidations:] : 228 -> 216
~ -[AccessibilityNodeAccessibility__NotificationCenterUI_SwiftUI accessibilityCustomActions] : 380 -> 368
~ +[AXNotificationCenterUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___73+[AXNotificationCenterUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___73+[AXNotificationCenterUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 192 -> 180
~ _accessibilityLocalizedString : 184 -> 172
~ +[ApplicationAccessibility _accessibilityPerformValidations:] : 636 -> 624
~ -[ApplicationAccessibility accessibilityWindowsAttribute] : 352 -> 340
~ -[ApplicationAccessibility accessibilityActionNames] : 200 -> 188
~ -[ApplicationAccessibility accessibilityParameterizedAttributeNames] : 164 -> 152
~ -[ApplicationAccessibility accessibilityAttributeValue:forParameter:] : 900 -> 888
~ ___69-[ApplicationAccessibility accessibilityAttributeValue:forParameter:]_block_invoke : 160 -> 148
~ -[ApplicationAccessibility accessibilityAttributeNames] : 164 -> 152
~ -[ApplicationAccessibility accessibilityAttributeValue:] : 188 -> 176
~ ___54-[ApplicationAccessibility _accessibilityToggleWindow]_block_invoke : 76 -> 64
~ -[ApplicationAccessibility _accessibilityWindowChooserItems] : 744 -> 732
~ ___60-[ApplicationAccessibility _accessibilityWindowChooserItems]_block_invoke : 104 -> 92
~ -[ApplicationAccessibility _accessibilityWidgetWindowForIdentifier:] : 648 -> 636
~ -[ApplicationAccessibility _accessibilityTotalNotificationCount] : 836 -> 824
~ +[WFWidgetConfigurationViewControllerAccessibility__NotificationCenterUI__WorkflowUIServices _accessibilityPerformValidations:] : 200 -> 188
```

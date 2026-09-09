## com.apple.securityinterface

> `/System/Library/Accessibility/BundlesBase/com.apple.securityinterface.axbundle/Versions/A/com.apple.securityinterface`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xc30
+  __TEXT.__text: 0xb70
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__objc_stubs: 0x3e0
   __TEXT.__objc_methlist: 0x160

   __TEXT.__cstring: 0x272
   __TEXT.__objc_methname: 0x400
   __TEXT.__objc_methtype: 0x36
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x300
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ +[SFEntropyBarViewAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[SFEntropyBarViewAccessibility accessibilityValueDescription] : 268 -> 256
~ +[SFPasswordAssistantInspectorControllerAccessibility _accessibilityPerformValidations:] : 304 -> 292
~ -[SFPasswordAssistantInspectorControllerAccessibility _axcInitSliderValue] : 180 -> 168
~ -[SFPasswordAssistantInspectorControllerAccessibility _axcInitChoicesComboIdentifier] : 128 -> 116
~ -[SFPasswordAssistantInspectorControllerAccessibility _axcPasswordAssistantPanel] : 164 -> 152
~ -[SFPasswordAssistantInspectorControllerAccessibility _axcPasswordAssistantView] : 108 -> 96
~ -[SFPasswordAssistantInspectorControllerAccessibility _axcController:] : 236 -> 224
~ +[SFPasswordAsstControllerAccessibility _accessibilityPerformValidations:] : 196 -> 184
~ -[SFPasswordAsstControllerAccessibility _axcLengthSlider] : 164 -> 152
~ -[SFPasswordAsstControllerAccessibility _axcLengthDisplayField] : 164 -> 152
~ -[SFPasswordAsstControllerAccessibility _axcChoicesCombo] : 164 -> 152
~ +[AXSecurityInterfaceGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___70+[AXSecurityInterfaceGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___70+[AXSecurityInterfaceGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 116 -> 104
~ _accessibilityLocalizedString : 184 -> 172
```

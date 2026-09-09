## com.apple.share.AirDrop.send

> `/System/Library/Accessibility/BundlesBase/com.apple.share.AirDrop.send.axbundle/Versions/A/com.apple.share.AirDrop.send`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x7d8
+  __TEXT.__text: 0x790
   __TEXT.__auth_stubs: 0xf0
   __TEXT.__objc_stubs: 0x300
   __TEXT.__objc_methlist: 0xc8

   __TEXT.__cstring: 0x175
   __TEXT.__objc_methname: 0x34c
   __TEXT.__objc_methtype: 0x2b
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x240
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ +[AirDropViewControllerAccessibility _accessibilityPerformValidations:] : 264 -> 252
~ +[SHKAirDropViewAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ +[AXAirDropShareKitPluginGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___74+[AXAirDropShareKitPluginGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___74+[AXAirDropShareKitPluginGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 96 -> 84
~ _accessibilityLocalizedString : 184 -> 172
```

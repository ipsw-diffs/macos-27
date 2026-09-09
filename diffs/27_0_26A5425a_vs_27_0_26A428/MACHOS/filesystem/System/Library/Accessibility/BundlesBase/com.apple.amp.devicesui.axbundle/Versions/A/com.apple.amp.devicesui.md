## com.apple.amp.devicesui

> `/System/Library/Accessibility/BundlesBase/com.apple.amp.devicesui.axbundle/Versions/A/com.apple.amp.devicesui`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x33c
+  __TEXT.__text: 0x300
   __TEXT.__auth_stubs: 0x70
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__objc_methlist: 0x74

   __TEXT.__cstring: 0xf9
   __TEXT.__objc_methname: 0x271
   __TEXT.__objc_methtype: 0x23
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0x80
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ +[DeviceNSImageViewAccessibility _accessibilityPerformValidations:] : 192 -> 180
~ -[DeviceNSImageViewAccessibility accessibilityLabel] : 124 -> 112
~ +[AXDeviceUIServiceGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___68+[AXDeviceUIServiceGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ _accessibilityLocalizedString : 184 -> 172
```

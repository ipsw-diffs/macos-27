## com.apple.AVKit

> `/System/Library/Accessibility/BundlesBase/com.apple.AVKit.axbundle/Versions/A/com.apple.AVKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x854
+  __TEXT.__text: 0x800
   __TEXT.__auth_stubs: 0xd0
   __TEXT.__objc_stubs: 0x2e0
   __TEXT.__objc_methlist: 0x150

   __TEXT.__cstring: 0x2cb
   __TEXT.__objc_methname: 0x377
   __TEXT.__objc_methtype: 0x31
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_classlist: 0x48
Functions:
~ -[AVTouchBarRecordingControlsViewControllerAccessibility _axcSelfAsViewController] : 108 -> 96
~ +[AVAuxiliaryControlsViewAccessibility _accessibilityPerformValidations:] : 144 -> 132
~ +[AVFloatingPlaybackControlsViewControllerAccessibility _accessibilityPerformValidations:] : 228 -> 216
~ +[AXAVKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___58+[AXAVKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___58+[AXAVKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 136 -> 124
~ _accessibilityLocalizedString : 184 -> 172
```

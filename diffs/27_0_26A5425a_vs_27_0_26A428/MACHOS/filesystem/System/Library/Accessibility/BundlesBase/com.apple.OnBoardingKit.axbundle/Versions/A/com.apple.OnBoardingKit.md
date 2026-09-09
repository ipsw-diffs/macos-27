## com.apple.OnBoardingKit

> `/System/Library/Accessibility/BundlesBase/com.apple.OnBoardingKit.axbundle/Versions/A/com.apple.OnBoardingKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x9e0
+  __TEXT.__text: 0x98c
   __TEXT.__auth_stubs: 0x100
   __TEXT.__objc_stubs: 0x400
   __TEXT.__objc_methlist: 0xa0

   __TEXT.__cstring: 0x115
   __TEXT.__objc_methname: 0x3d2
   __TEXT.__objc_methtype: 0x40
-  __TEXT.__unwind_info: 0x98
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__cfstring: 0x160
   __DATA_CONST.__objc_classlist: 0x18
Functions:
~ +[OBPrivacySplashViewAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ +[OBPrivacySplashViewAccessibility _axcRecurseThroughSubviews:performBlock:] : 236 -> 224
~ ___76+[OBPrivacySplashViewAccessibility _axcSetupAccessibilityForExistingClasses]_block_invoke : 100 -> 88
~ +[AXOnBoardingKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___66+[AXOnBoardingKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___66+[AXOnBoardingKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 72 -> 60
~ _accessibilityLocalizedString : 184 -> 172
```

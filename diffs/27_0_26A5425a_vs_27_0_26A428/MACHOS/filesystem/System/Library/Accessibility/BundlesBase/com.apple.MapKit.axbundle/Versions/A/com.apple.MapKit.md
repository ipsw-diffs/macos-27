## com.apple.MapKit

> `/System/Library/Accessibility/BundlesBase/com.apple.MapKit.axbundle/Versions/A/com.apple.MapKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0x27c4
+  __TEXT.__text: 0x2644
   __TEXT.__auth_stubs: 0x230
   __TEXT.__objc_stubs: 0x8e0
   __TEXT.__objc_methlist: 0x408

   __TEXT.__objc_methtype: 0x5d
   __TEXT.__const: 0x28
   __TEXT.__gcc_except_tab: 0xd0
-  __TEXT.__unwind_info: 0x1a0
+  __TEXT.__unwind_info: 0x1c0
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__cfstring: 0x780
   __DATA_CONST.__objc_classlist: 0xb0
Functions:
~ -[NSImageAccessibility__MapKit__AppKit __accessibilityDescriptionMapKit] : 276 -> 264
~ -[NSImageAccessibility__MapKit__AppKit accessibilityDescription] : 152 -> 140
~ +[MKMapViewAccessibility _accessibilityPerformValidations:] : 128 -> 116
~ -[MKMapViewAccessibility accessibilityChildrenInNavigationOrder] : 264 -> 252
~ -[MKMapViewAccessibility accessibilityCustomRotors] : 244 -> 232
~ -[MKMapViewAccessibility rotor:resultForSearchParameters:] : 632 -> 620
~ ___58-[MKMapViewAccessibility rotor:resultForSearchParameters:]_block_invoke : 176 -> 164
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ +[MKStarRatingViewAccessibility _accessibilityPerformValidations:] : 112 -> 100
~ -[MKStarRatingViewAccessibility accessibilityLabel] : 48 -> 36
~ -[MKPlaceInfoURLRowViewAccessibility _icon] : 240 -> 228
~ -[MKPlaceInfoPostalAddressRowViewAccessibility _icon] : 240 -> 228
~ -[MKPlaceInfoPhoneNumberViewAccessibility _icon] : 240 -> 228
~ +[AXMapKitGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___59+[AXMapKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___59+[AXMapKitGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 256 -> 244
~ _accessibilityLocalizedString : 184 -> 172
~ +[_MKModernCompassViewAccessibility _accessibilityPerformValidations:] : 212 -> 200
~ -[_MKModernCompassViewAccessibility accessibilityValue] : 52 -> 40
~ +[AXMapKitCustomZoomAction actionWithController:zoomIn:] : 312 -> 300
~ +[MKZoomControlAccessibility _accessibilityPerformValidations:] : 420 -> 408
~ ___72-[MKZoomControlAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke : 196 -> 184
~ __72-[MKZoomControlAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke.424 : 196 -> 184
~ +[MKAnnotationViewAccessibility _accessibilityPerformValidations:] : 236 -> 224
~ -[MKAnnotationViewAccessibility _axcCalloutView] : 316 -> 304
~ ___48-[MKAnnotationViewAccessibility _axcCalloutView]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[MKImageViewAccessibility accessibilityLabel] : 80 -> 68
~ -[MKImageViewAccessibility _axcImage] : 332 -> 320
~ ___37-[MKImageViewAccessibility _axcImage]_block_invoke : 80 -> 68
```

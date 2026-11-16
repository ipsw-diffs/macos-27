## InvertColorsManager

> `/System/iOSSupport/System/Library/AccessibilityBundles/InvertColorsManager.bundle/Contents/MacOS/InvertColorsManager`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-3245.8.14.0.0
-  __TEXT.__text: 0x168b8
-  __TEXT.__auth_stubs: 0x720
-  __TEXT.__objc_stubs: 0x22e0
-  __TEXT.__objc_methlist: 0x5bbc
-  __TEXT.__const: 0x78
+3245.8.23.0.0
+  __TEXT.__text: 0x16cf8
+  __TEXT.__auth_stubs: 0x710
+  __TEXT.__objc_stubs: 0x2380
+  __TEXT.__objc_methlist: 0x5c34
+  __TEXT.__const: 0x80
   __TEXT.__dlopen_cstrs: 0x6a
   __TEXT.__gcc_except_tab: 0x148
-  __TEXT.__objc_classname: 0x7737
-  __TEXT.__cstring: 0x65a8
-  __TEXT.__objc_methname: 0x241e
+  __TEXT.__objc_classname: 0x7791
+  __TEXT.__cstring: 0x6ac5
+  __TEXT.__objc_methname: 0x24c9
   __TEXT.__objc_methtype: 0x2af
-  __TEXT.__oslogstring: 0x76b
-  __TEXT.__unwind_info: 0xca0
+  __TEXT.__oslogstring: 0x7ee
+  __TEXT.__unwind_info: 0xcc0
   __DATA_CONST.__const: 0x7a0
-  __DATA_CONST.__cfstring: 0x6520
-  __DATA_CONST.__objc_classlist: 0x1448
+  __DATA_CONST.__cfstring: 0x65a0
+  __DATA_CONST.__objc_classlist: 0x1458
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_superrefs: 0x400
+  __DATA_CONST.__objc_superrefs: 0x408
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x3a0
+  __DATA_CONST.__auth_got: 0x398
   __DATA_CONST.__got: 0x188
-  __DATA.__objc_const: 0x19b48
-  __DATA.__objc_selrefs: 0xbb0
-  __DATA.__objc_data: 0xcad0
+  __DATA.__objc_const: 0x19c68
+  __DATA.__objc_selrefs: 0xbe0
+  __DATA.__objc_data: 0xcb70
   __DATA.__data: 0xc8
   __DATA.__bss: 0xd8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libAccessibility.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1469
-  Symbols:   1471
-  CStrings:  1635
+  Functions: 1478
+  Symbols:   1474
+  CStrings:  1646
 
Symbols:
+ _OBJC_CLASS_$_WKWebViewLegacyInvertColorsAccessibility
+ _OBJC_CLASS_$___WKWebViewLegacyInvertColorsAccessibility_super
+ _OBJC_METACLASS_$_WKWebViewLegacyInvertColorsAccessibility
+ _OBJC_METACLASS_$___WKWebViewLegacyInvertColorsAccessibility_super
- _AXInvertColorsDarkModeDetectionJavascript
CStrings:
+ "WKWebView %p effective page appearance: %ld, inverted: %d"
+ "WKWebViewLegacyInvertColorsAccessibility"
+ "WebKit lacks content inversion SPI, using legacy WKWebView invert colors"
+ "__WKWebViewLegacyInvertColorsAccessibility_super"
+ "_accessibilityPageIsLight"
+ "_effectivePageAppearance"
+ "_setContentInversionForAccessibility:"
+ "_webKitSupportsContentInversion"
+ "didChangeValueForKey:"
+ "function luminance(color) {  if (color.length == 4 && color[3] == 0) { return 1; } for (var k = 0; k < 3; k++) { var adjusted = 0;  var value = color[k] / 255;  if (value < 0.03928) {        value = value / 12.92;    } else {        value = (value + .055) / 1.055;        value = Math.pow(value, 2.4); } color[k] = value;   } return (color[0] * .2126) + (color[1] * .7152) + (color[2] * .0722); }\nfunction dm() { var supportedSchemes = document.head.querySelector(\"meta[name='supported-color-schemes']\");\nvar supportedSchemesDM = (supportedSchemes && supportedSchemes.content && supportedSchemes.content.includes('dark'));\nvar colorSchemes = document.head.querySelector(\"meta[name='color-scheme']\");\nvar colorSchemesDM = (supportedSchemes && supportedSchemes.content && supportedSchemes.content.includes('dark'));\nvar classListDM = document.documentElement.classList.contains('apple-mail-implicit-dark-support');\nvar bgColor = document.body && window.getComputedStyle(document.body).getPropertyValue('background-color');\nbgColor = bgColor.replace(/[^\\d,]/g, '').split(',');\nvar luma = bgColor ? luminance(bgColor) : .99;\nreturn (supportedSchemesDM || colorSchemesDM || classListDM || (luma < .3)) }\ndm();"
+ "instancesRespondToSelector:"
```

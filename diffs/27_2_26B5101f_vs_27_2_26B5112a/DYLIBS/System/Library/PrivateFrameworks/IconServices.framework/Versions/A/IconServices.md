## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/Versions/A/IconServices`

```diff

 793.1.10.0.0
-  __TEXT.__text: 0x81190
+  __TEXT.__text: 0x813e8
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa4
-  __TEXT.__objc_methlist: 0x79cc
-  __TEXT.__cstring: 0x55f9
+  __TEXT.__objc_methlist: 0x79fc
+  __TEXT.__cstring: 0x562a
   __TEXT.__const: 0x96b0
   __TEXT.__oslogstring: 0x4030
   __TEXT.__gcc_except_tab: 0x96c

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x6f0
-  __DATA_CONST.__objc_classlist: 0x5d0
+  __DATA_CONST.__objc_classlist: 0x5d8
   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x148
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3880
+  __DATA_CONST.__objc_selrefs: 0x3890
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x490
-  __DATA_CONST.__objc_arraydata: 0xb0
+  __DATA_CONST.__objc_arraydata: 0xc8
   __DATA_CONST.__got: 0x850
   __AUTH_CONST.__const: 0x1b68
-  __AUTH_CONST.__cfstring: 0x5fc0
-  __AUTH_CONST.__objc_const: 0x16cc0
+  __AUTH_CONST.__cfstring: 0x6000
+  __AUTH_CONST.__objc_const: 0x16d60
   __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__objc_intobj: 0x6c0
-  __AUTH_CONST.__objc_arrayobj: 0x108
+  __AUTH_CONST.__objc_intobj: 0x6f0
+  __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__auth_got: 0xb60
-  __AUTH.__objc_data: 0x550
+  __AUTH.__objc_data: 0x5a0
   __AUTH.__data: 0x8
   __DATA.__objc_ivar: 0x7a8
   __DATA.__data: 0x211c

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3074
-  Symbols:   7392
-  CStrings:  1302
+  Functions: 3077
+  Symbols:   7401
+  CStrings:  1305
 
Symbols:
+ -[ISDefaults isForceHomeAccessoryDeviceEnabled]
+ -[ISDeviceInfo isHomeAccessoryDevice]
+ -[ISHomeAccessoryAppRecipe iconSpecification]
+ _OBJC_CLASS_$_ISHomeAccessoryAppRecipe
+ _OBJC_METACLASS_$_ISHomeAccessoryAppRecipe
+ __OBJC_$_INSTANCE_METHODS_ISHomeAccessoryAppRecipe
+ __OBJC_CLASS_RO_$_ISHomeAccessoryAppRecipe
+ __OBJC_METACLASS_RO_$_ISHomeAccessoryAppRecipe
+ _objc_msgSend$isHomeAccessoryDevice
Functions:
+ -[ISHomeAccessoryAppRecipe iconSpecification]
~ +[ISRecipeInfo appRecipeForPlatform:descriptor:preferRichRecipe:] : 420 -> 556
~ ___38+[ISSymbol _variantOptionsToKeyPieces]_block_invoke : 844 -> 892
+ -[ISDefaults simulateTintableAppearance]
~ -[ISCompositingDescriptor CUINamedImageDeviceClass] : 324 -> 372
~ -[ISCompositingDescriptor encapsulationShape] : 364 -> 416
~ -[ISPlatformInfo supportsRequestingMultisizedImagesForPlatform:] : 160 -> 232
~ -[ISPlatformInfo supportsRequestingIconStacksForPlatform:] : 252 -> 316
~ -[ISDeviceInfo homeScreenIconSize] : 436 -> 492
+ -[ISDeviceInfo screenClass]
~ -[ISImageDescriptor continuousCornerRadius] : 196 -> 224
~ ___55-[CUICatalog(IconServicesAdditions) idiomsForPlatform:]_block_invoke : 168 -> 224
CStrings:
+ "force_accessory"
+ "homeaccessory"
+ "homeaccessory_wall"
```

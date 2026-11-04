## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/Versions/A/AppStoreComponents`

```diff

-27.1.12.0.0
-  __TEXT.__text: 0x6f2d4
-  __TEXT.__objc_methlist: 0x6f2c
-  __TEXT.__const: 0x19f4
-  __TEXT.__cstring: 0x34e6
-  __TEXT.__oslogstring: 0x2e1d
+27.2.7.0.0
+  __TEXT.__text: 0x6dbb0
+  __TEXT.__objc_methlist: 0x6d8c
+  __TEXT.__const: 0x1964
+  __TEXT.__cstring: 0x3476
+  __TEXT.__oslogstring: 0x2e5f
   __TEXT.__gcc_except_tab: 0x6c4
-  __TEXT.__swift5_typeref: 0x486
+  __TEXT.__swift5_typeref: 0x43c
   __TEXT.__swift5_capture: 0x1c8
-  __TEXT.__constg_swiftt: 0x788
-  __TEXT.__swift5_reflstr: 0xaa7
-  __TEXT.__swift5_fieldmd: 0x9d8
+  __TEXT.__constg_swiftt: 0x6fc
+  __TEXT.__swift5_reflstr: 0xab0
+  __TEXT.__swift5_fieldmd: 0x9ac
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__swift5_assocty: 0x1c8
-  __TEXT.__swift5_proto: 0x100
-  __TEXT.__swift5_types: 0xa8
+  __TEXT.__swift5_assocty: 0x1b0
+  __TEXT.__swift5_proto: 0xfc
+  __TEXT.__swift5_types: 0xa0
   __TEXT.__swift5_protos: 0xc
-  __TEXT.__unwind_info: 0x28b8
+  __TEXT.__unwind_info: 0x2810
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7b0
-  __DATA_CONST.__objc_classlist: 0x3e0
+  __DATA_CONST.__const: 0x798
+  __DATA_CONST.__objc_classlist: 0x3c8
   __DATA_CONST.__objc_catlist: 0x50
-  __DATA_CONST.__objc_protolist: 0xd8
+  __DATA_CONST.__objc_protolist: 0xd0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3230
-  __DATA_CONST.__objc_protorefs: 0x38
-  __DATA_CONST.__objc_superrefs: 0x368
+  __DATA_CONST.__objc_selrefs: 0x31e0
+  __DATA_CONST.__objc_protorefs: 0x30
+  __DATA_CONST.__objc_superrefs: 0x358
   __DATA_CONST.__objc_arraydata: 0x60
-  __DATA_CONST.__got: 0x798
-  __AUTH_CONST.__const: 0x2bc0
-  __AUTH_CONST.__cfstring: 0x4940
-  __AUTH_CONST.__objc_const: 0xcff0
+  __DATA_CONST.__got: 0x740
+  __AUTH_CONST.__const: 0x2ad0
+  __AUTH_CONST.__cfstring: 0x48c0
+  __AUTH_CONST.__objc_const: 0xcbf0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xb90
-  __AUTH.__objc_data: 0xb18
-  __AUTH.__data: 0x450
-  __DATA.__objc_ivar: 0x700
-  __DATA.__data: 0x1428
+  __AUTH_CONST.__auth_got: 0xaf8
+  __AUTH.__objc_data: 0xac8
+  __AUTH.__data: 0x340
+  __DATA.__objc_ivar: 0x6e4
+  __DATA.__data: 0x1380
   __DATA.__objc_stublist: 0x8
-  __DATA.__bss: 0x1f30
+  __DATA.__bss: 0x1ea0
   __DATA.__common: 0x28
-  __DATA_DIRTY.__objc_data: 0x1b80
+  __DATA_DIRTY.__objc_data: 0x1b30
   __DATA_DIRTY.__data: 0x2f8
-  __DATA_DIRTY.__bss: 0x350
+  __DATA_DIRTY.__bss: 0x340
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
-  - /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
   - /System/Library/PrivateFrameworks/AppState.framework/Versions/A/AppState
   - /System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices
   - /System/Library/PrivateFrameworks/AppleMediaServicesUIPaymentSheets.framework/Versions/A/AppleMediaServicesUIPaymentSheets

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3177
-  Symbols:   6270
-  CStrings:  898
+  Functions: 3121
+  Symbols:   6182
+  CStrings:  894
 
Symbols:
+ -[ASCLockupFetcher lockupFromMediaAPIResponse:kind:withContext:]
+ -[ASCMediaPlatform appPlatform]
+ -[ASCMediaPlatform initWithAppPlatform:deviceCornerRadiusFactor:]
+ -[ASCOfferButton glyphHeight]
+ _OBJC_IVAR_$_ASCMediaPlatform._appPlatform
+ __OBJC_$_INSTANCE_METHODS_ASCLockup(Ad|AgeRatingValue|BundleID|BuyParams|ContentDescriptors|DeveloperName|DisplayContext|ExtendedAttributes|Genre|Media|MiniProductPage|ProductVariants|SafariExtension|ShortName|ASCSignpostTags|SingleSignOn|ASCDeprecated)
+ ___64-[ASCLockupFetcher lockupFromMediaAPIResponse:kind:withContext:]_block_invoke
+ _objc_msgSend$appPlatform
+ _objc_msgSend$buildLockupFromMediaAPIResponse:kind:withContext:withReplyHandler:
+ _objc_msgSend$configurationWithPointSize:weight:
+ _objc_msgSend$doubleValue
+ _objc_msgSend$fontDescriptor
+ _objc_msgSend$lockupFromMediaAPIResponse:kind:withContext:
+ _objc_msgSend$offerIconTextLayoutForSize:titleBackgroundView:titleView:imageView:imageBaselineOffsetFromBottom:topPadding:
- +[ASCContentFetcher sharedFetcher]
- +[ASCLockupFeatureMetadata supportsSecureCoding]
- -[ASCContentFetcher .cxx_destruct]
- -[ASCContentFetcher connection]
- -[ASCContentFetcher contentFromMediaAPIResponse:contentType:]
- -[ASCContentFetcher contentWithIdentifier:contentType:profileData:]
- -[ASCContentFetcher initWithConnection:]
- -[ASCLockup(Metadata) metadata_chartGenreName]
- -[ASCLockup(Metadata) metadata_chartPosition]
- -[ASCLockup(Metadata) metadata_isComingSoon]
- -[ASCLockup(Metadata) metadata_isEditorsChoice]
- -[ASCLockup(Metadata) metadata_productRatingBadge]
- -[ASCLockup(Metadata) metadata_productRating]
- -[ASCLockupFeatureMetadata .cxx_destruct]
- -[ASCLockupFeatureMetadata chartGenreName]
- -[ASCLockupFeatureMetadata chartPosition]
- -[ASCLockupFeatureMetadata copyWithZone:]
- -[ASCLockupFeatureMetadata description]
- -[ASCLockupFeatureMetadata encodeWithCoder:]
- -[ASCLockupFeatureMetadata hash]
- -[ASCLockupFeatureMetadata initWithCoder:]
- -[ASCLockupFeatureMetadata initWithEditorsChoice:productRating:productRatingBadge:chartPosition:chartGenreName:comingSoon:]
- -[ASCLockupFeatureMetadata isComingSoon]
- -[ASCLockupFeatureMetadata isEditorsChoice]
- -[ASCLockupFeatureMetadata isEqual:]
- -[ASCLockupFeatureMetadata productRatingBadge]
- -[ASCLockupFeatureMetadata productRating]
- -[ASCLockupFetcher lockupFromMediaAPIResponse:withContext:]
- -[ASCMediaPlatform initWithDeviceCornerRadiusFactor:]
- -[ASCServicesConnection contentFetcherService]
- _ASCContentFetcherServiceGetInterface
- _ASCContentFetcherServiceGetInterface.interface
- _ASCContentFetcherServiceGetInterface.onceToken
- _ASCLockupContextMetadata
- _ASCLockupContextScreenshotsOnly
- _ASCLockupContextShortNameOnly
- _NSFontWeightSemibold
- _OBJC_CLASS_$_ASCContentFetcher
- _OBJC_CLASS_$_ASCLockupFeatureMetadata
- _OBJC_CLASS_$_NSData
- _OBJC_IVAR_$_ASCArtwork._isPortrait
- _OBJC_IVAR_$_ASCContentFetcher._connection
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._chartGenreName
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._chartPosition
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._isComingSoon
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._isEditorsChoice
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._productRating
- _OBJC_IVAR_$_ASCLockupFeatureMetadata._productRatingBadge
- _OBJC_METACLASS_$_ASCContentFetcher
- _OBJC_METACLASS_$_ASCLockupFeatureMetadata
- __DATA__TtC18AppStoreComponents13MediaPlatform
- __METACLASS_DATA__TtC18AppStoreComponents13MediaPlatform
- __OBJC_$_CLASS_METHODS_ASCContentFetcher
- __OBJC_$_CLASS_METHODS_ASCLockupFeatureMetadata
- __OBJC_$_CLASS_PROP_LIST_ASCContentFetcher
- __OBJC_$_CLASS_PROP_LIST_ASCLockupFeatureMetadata
- __OBJC_$_INSTANCE_METHODS_ASCContentFetcher
- __OBJC_$_INSTANCE_METHODS_ASCLockup(Ad|AgeRatingValue|BundleID|BuyParams|ContentDescriptors|DeveloperName|DisplayContext|ExtendedAttributes|Genre|Media|Metadata|MiniProductPage|ProductVariants|SafariExtension|ShortName|ASCSignpostTags|SingleSignOn|ASCDeprecated)
- __OBJC_$_INSTANCE_METHODS_ASCLockupFeatureMetadata
- __OBJC_$_INSTANCE_VARIABLES_ASCContentFetcher
- __OBJC_$_INSTANCE_VARIABLES_ASCLockupFeatureMetadata
- __OBJC_$_PROP_LIST_ASCContentFetcher
- __OBJC_$_PROP_LIST_ASCLockupFeatureMetadata
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ASCContentFetcherService
- __OBJC_$_PROTOCOL_METHOD_TYPES_ASCContentFetcherService
- __OBJC_$_PROTOCOL_REFS_ASCContentFetcherService
- __OBJC_CLASS_PROTOCOLS_$_ASCLockupFeatureMetadata
- __OBJC_CLASS_RO_$_ASCContentFetcher
- __OBJC_CLASS_RO_$_ASCLockupFeatureMetadata
- __OBJC_LABEL_PROTOCOL_$_ASCContentFetcherService
- __OBJC_METACLASS_RO_$_ASCContentFetcher
- __OBJC_METACLASS_RO_$_ASCLockupFeatureMetadata
- __OBJC_PROTOCOL_$_ASCContentFetcherService
- __OBJC_PROTOCOL_REFERENCE_$_ASCContentFetcherService
- ___34+[ASCContentFetcher sharedFetcher]_block_invoke
- ___46-[ASCServicesConnection contentFetcherService]_block_invoke
- ___59-[ASCLockupFetcher lockupFromMediaAPIResponse:withContext:]_block_invoke
- ___61-[ASCContentFetcher contentFromMediaAPIResponse:contentType:]_block_invoke
- ___67-[ASCContentFetcher contentWithIdentifier:contentType:profileData:]_block_invoke
- ___ASCContentFetcherServiceGetInterface_block_invoke
- ___block_descriptor_48_e8_32s40s_e54_"AMSMutablePromise"16?0"<ASCLockupFetcherService>"8l
- ___block_descriptor_48_e8_32s40s_e55_"AMSMutablePromise"16?0"<ASCContentFetcherService>"8l
- ___block_descriptor_56_e8_32s40s48s_e55_"AMSMutablePromise"16?0"<ASCContentFetcherService>"8l
- _associated conformance 18AppStoreComponents11OrdinalViewV7SwiftUI0E0AA4BodyAdEP_AdE
- _get_witness_table 7SwiftUI4TextVAA4ViewHPyHC
- _objc_msgSend$buildContentFromMediaAPIResponse:contentType:withReplyHandler:
- _objc_msgSend$buildLockupFromMediaAPIResponse:withContext:withReplyHandler:
- _objc_msgSend$chartGenreName
- _objc_msgSend$chartPosition
- _objc_msgSend$contentFetcherService
- _objc_msgSend$getContentFetcherServiceWithReplyHandler:
- _objc_msgSend$getContentWithIdentifier:contentType:profileData:withReplyHandler:
- _objc_msgSend$initWithEditorsChoice:productRating:productRatingBadge:chartPosition:chartGenreName:comingSoon:
- _objc_msgSend$isComingSoon
- _objc_msgSend$lockupFromMediaAPIResponse:withContext:
- _objc_msgSend$offerIconTextLayoutForSize:titleBackgroundView:titleView:imageView:topPadding:
- _symbolic $s7SwiftUI4ViewP
- _symbolic _____ 18AppStoreComponents11OrdinalViewV
- _symbolic _____ 18AppStoreComponents13MediaPlatformC
- _symbolic _____ 7SwiftUI4TextV
- _symbolic _____Sg 7SwiftUI4FontV6DesignO
- _symbolic _____y_____G 7SwiftUI12ScaledMetricV 12CoreGraphics7CGFloatV
CStrings:
+ "$"
+ "Could not decode ASCMediaPlatform because appPlatform was missing"
+ "appPlatform"
- "4"
- "@\"AMSMutablePromise\"16@?0@\"<ASCContentFetcherService>\"8"
- "chartGenreName"
- "chartPosition"
- "isComingSoon"
- "screenshotsOnly"
- "shortNameOnly"
```

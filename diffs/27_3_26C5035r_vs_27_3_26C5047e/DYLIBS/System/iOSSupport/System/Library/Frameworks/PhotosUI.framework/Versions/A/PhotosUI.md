## PhotosUI

> `/System/iOSSupport/System/Library/Frameworks/PhotosUI.framework/Versions/A/PhotosUI`

```diff

-920.8.100.0.0
-  __TEXT.__text: 0x4abf8
-  __TEXT.__objc_methlist: 0x46d4
-  __TEXT.__const: 0x3118
-  __TEXT.__constg_swiftt: 0xe04
-  __TEXT.__swift5_typeref: 0xd1a
-  __TEXT.__swift5_builtin: 0x168
-  __TEXT.__swift5_reflstr: 0xbe6
-  __TEXT.__swift5_fieldmd: 0xcc0
-  __TEXT.__swift5_assocty: 0x348
-  __TEXT.__swift5_proto: 0x1a0
-  __TEXT.__swift5_types: 0x128
-  __TEXT.__cstring: 0x503c
+920.12.210.0.0
+  __TEXT.__text: 0x4d2f8
+  __TEXT.__objc_methlist: 0x4824
+  __TEXT.__const: 0x2fe8
+  __TEXT.__constg_swiftt: 0xe5c
+  __TEXT.__swift5_typeref: 0xd66
+  __TEXT.__swift5_builtin: 0x140
+  __TEXT.__swift5_reflstr: 0xce6
+  __TEXT.__swift5_fieldmd: 0xd60
+  __TEXT.__swift5_assocty: 0x300
+  __TEXT.__swift5_proto: 0x184
+  __TEXT.__swift5_types: 0x124
+  __TEXT.__cstring: 0x52b2
   __TEXT.__oslogstring: 0x19de
-  __TEXT.__swift5_capture: 0x5a0
-  __TEXT.__swift_as_entry: 0x34
+  __TEXT.__swift5_capture: 0x608
+  __TEXT.__swift_as_entry: 0x38
   __TEXT.__swift_as_ret: 0xc
-  __TEXT.__swift_as_cont: 0x3c
+  __TEXT.__swift_as_cont: 0x40
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__gcc_except_tab: 0x2ac
-  __TEXT.__unwind_info: 0x2390
-  __TEXT.__eh_frame: 0x8d4
+  __TEXT.__unwind_info: 0x24c0
+  __TEXT.__eh_frame: 0x994
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe68
-  __DATA_CONST.__objc_classlist: 0x250
+  __DATA_CONST.__const: 0xf30
+  __DATA_CONST.__objc_classlist: 0x258
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x280
+  __DATA_CONST.__objc_protolist: 0x270
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x29b0
-  __DATA_CONST.__objc_protorefs: 0x108
-  __DATA_CONST.__objc_superrefs: 0x118
+  __DATA_CONST.__objc_selrefs: 0x2a38
+  __DATA_CONST.__objc_protorefs: 0x100
+  __DATA_CONST.__objc_superrefs: 0x120
   __DATA_CONST.__objc_arraydata: 0x28
-  __DATA_CONST.__got: 0x810
-  __AUTH_CONST.__const: 0x2398
-  __AUTH_CONST.__cfstring: 0x2560
-  __AUTH_CONST.__objc_const: 0x7dd0
+  __DATA_CONST.__got: 0x818
+  __AUTH_CONST.__const: 0x24f0
+  __AUTH_CONST.__cfstring: 0x25a0
+  __AUTH_CONST.__objc_const: 0x7fc8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0xc28
-  __AUTH.__objc_data: 0x1f60
-  __AUTH.__data: 0x740
-  __DATA.__objc_ivar: 0x3e4
-  __DATA.__data: 0x1f70
-  __DATA.__bss: 0x3040
+  __AUTH_CONST.__auth_got: 0xc38
+  __AUTH.__objc_data: 0x2050
+  __AUTH.__data: 0x730
+  __DATA.__objc_ivar: 0x3ec
+  __DATA.__data: 0x1f60
+  __DATA.__bss: 0x2cc0
   __DATA.__common: 0x121
   __DATA_DIRTY.__objc_data: 0x480
   __DATA_DIRTY.__data: 0xf8

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3203
-  Symbols:   4328
-  CStrings:  618
+  Functions: 3356
+  Symbols:   4393
+  CStrings:  639
 
Symbols:
+ +[PHPickerAspectRatio deviceAspectRatio]
+ +[PHPickerAspectRatio supportsSecureCoding]
+ +[PHPickerFilter landscapeAspectRatioFilter]
+ -[PHPickerAspectRatio _aspectRatio]
+ -[PHPickerAspectRatio _initWithAspectRatio:]
+ -[PHPickerAspectRatio copyWithZone:]
+ -[PHPickerAspectRatio encodeWithCoder:]
+ -[PHPickerAspectRatio hash]
+ -[PHPickerAspectRatio initWithAspectRatio:]
+ -[PHPickerAspectRatio initWithCoder:]
+ -[PHPickerAspectRatio init]
+ -[PHPickerAspectRatio isEqual:]
+ -[PHPickerConfiguration aspectRatio]
+ -[PHPickerConfiguration containerIdentifier]
+ -[PHPickerConfiguration primaryButtonType]
+ -[PHPickerConfiguration secondaryButtonType]
+ -[PHPickerConfiguration setAspectRatio:]
+ -[PHPickerConfiguration setContainerIdentifier:]
+ -[PHPickerConfiguration setPrimaryButtonType:]
+ -[PHPickerConfiguration setSecondaryButtonType:]
+ -[PHPickerResult requestThumbnailImageURLForPreferredSize:resultHandler:]
+ -[PHPickerSearchText prefersAutomaticFocus]
+ -[PHPickerSearchText setPrefersAutomaticFocus:]
+ -[PHPickerUpdateConfiguration containerIdentifier]
+ -[PHPickerUpdateConfiguration primaryButtonType]
+ -[PHPickerUpdateConfiguration secondaryButtonType]
+ -[PHPickerUpdateConfiguration setContainerIdentifier:]
+ -[PHPickerUpdateConfiguration setPrimaryButtonType:]
+ -[PHPickerUpdateConfiguration setSecondaryButtonType:]
+ GCC_except_table1082
+ GCC_except_table518
+ GCC_except_table528
+ GCC_except_table531
+ GCC_except_table533
+ GCC_except_table702
+ GCC_except_table799
+ GCC_except_table890
+ GCC_except_table895
+ GCC_except_table899
+ GCC_except_table903
+ _OBJC_CLASS_$_PHPickerAspectRatio
+ _OBJC_IVAR_$_PHPickerAspectRatio.__aspectRatio
+ _OBJC_IVAR_$_PHPickerConfiguration._aspectRatio
+ _OBJC_IVAR_$_PHPickerConfiguration._containerIdentifier
+ _OBJC_IVAR_$_PHPickerConfiguration._primaryButtonType
+ _OBJC_IVAR_$_PHPickerConfiguration._secondaryButtonType
+ _OBJC_IVAR_$_PHPickerSearchText._prefersAutomaticFocus
+ _OBJC_IVAR_$_PHPickerUpdateConfiguration._containerIdentifier
+ _OBJC_IVAR_$_PHPickerUpdateConfiguration._primaryButtonType
+ _OBJC_IVAR_$_PHPickerUpdateConfiguration._secondaryButtonType
+ _OBJC_METACLASS_$_PHPickerAspectRatio
+ _OUTLINED_FUNCTION_100
+ _OUTLINED_FUNCTION_88
+ _OUTLINED_FUNCTION_89
+ _OUTLINED_FUNCTION_90
+ _OUTLINED_FUNCTION_91
+ _OUTLINED_FUNCTION_92
+ _OUTLINED_FUNCTION_93
+ _OUTLINED_FUNCTION_94
+ _OUTLINED_FUNCTION_95
+ _OUTLINED_FUNCTION_96
+ _OUTLINED_FUNCTION_97
+ _OUTLINED_FUNCTION_98
+ _OUTLINED_FUNCTION_99
+ _PHPhotosUIErrorDomain
+ __INSTANCE_METHODS__TtC8PhotosUIP33_E2E20DF4EAC1FCE07E5336962A6E0BEF23_PHPickerOverlayStorage
+ __OBJC_$_CLASS_METHODS_PHPickerAspectRatio
+ __OBJC_$_CLASS_PROP_LIST_PHPickerAspectRatio
+ __OBJC_$_INSTANCE_METHODS_PHPickerAspectRatio
+ __OBJC_$_INSTANCE_VARIABLES_PHPickerAspectRatio
+ __OBJC_$_PROP_LIST_PHPickerAspectRatio
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PHPickerViewControllerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_PHPickerAspectRatio
+ __OBJC_CLASS_RO_$_PHPickerAspectRatio
+ __OBJC_METACLASS_RO_$_PHPickerAspectRatio
+ __PROTOCOLS__TtC8PhotosUIP33_E2E20DF4EAC1FCE07E5336962A6E0BEF23_PHPickerOverlayStorage
+ ___73-[PHPickerResult requestThumbnailImageURLForPreferredSize:resultHandler:]_block_invoke
+ ___swift_memcpy137_8
+ ___swift_memcpy608_8
+ __swiftEmptyDictionarySingleton
+ _associated conformance 8PhotosUI19PHPickerAspectRatioVSHAASQ
+ _dynamic_cast_existential_1_conditional
+ _objc_msgSend$_aspectRatio
+ _objc_msgSend$aspectRatio
+ _objc_msgSend$bundleWithIdentifier:
+ _objc_msgSend$containerIdentifier
+ _objc_msgSend$deviceAspectRatio
+ _objc_msgSend$initWithAspectRatio:
+ _objc_msgSend$landscapeAspectRatioFilter
+ _objc_msgSend$pickerDidPerformPrimaryAction:
+ _objc_msgSend$pickerDidPerformSecondaryAction:
+ _objc_msgSend$prefersAutomaticFocus
+ _objc_msgSend$primaryButtonType
+ _objc_msgSend$requestThumbnailImageURLForPreferredSize:resultHandler:
+ _objc_msgSend$secondaryButtonType
+ _objc_msgSend$setAspectRatio:
+ _objc_msgSend$setContainerIdentifier:
+ _objc_msgSend$setPrefersAutomaticFocus:
+ _objc_msgSend$setPrimaryButtonType:
+ _objc_msgSend$setSecondaryButtonType:
+ _swift_conformsToProtocol2
+ _symbolic SiSgSg
+ _symbolic So19PHPickerAspectRatioC
+ _symbolic _____ 8PhotosUI19PHPickerAspectRatioV
+ _symbolic _____ 8PhotosUI23_PHPickerOverlayStorage33_E2E20DF4EAC1FCE07E5336962A6E0BEFLLC15PrivateDelegateV
+ _symbolic _____Sg 8PhotosUI23_PHPickerOverlayStorage33_E2E20DF4EAC1FCE07E5336962A6E0BEFLLC15PrivateDelegateV
+ _symbolic _____yS2SG s18_DictionaryStorageC
+ _symbolic _____ySS_SSSgtG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
+ _symbolic ySo22PHPickerViewControllerCScMYcc
+ _symbolic yXlSgXw
+ _type_layout_string 8PhotosUI19PHPickerAspectRatioV
+ _type_layout_string 8PhotosUI23_PHPickerOverlayStorage33_E2E20DF4EAC1FCE07E5336962A6E0BEFLLC15PrivateDelegateV
- +[_PHPickerAspectRatio supportsSecureCoding]
- -[_PHPickerAspectRatio encodeWithCoder:]
- -[_PHPickerAspectRatio initWithCoder:]
- GCC_except_table1056
- GCC_except_table492
- GCC_except_table502
- GCC_except_table505
- GCC_except_table507
- GCC_except_table676
- GCC_except_table773
- GCC_except_table864
- GCC_except_table869
- GCC_except_table873
- GCC_except_table877
- _OBJC_IVAR_$_PHPickerConfiguration.__aspectRatio
- _OBJC_IVAR_$_PHPickerConfiguration.__containerIdentifier
- _OBJC_IVAR_$_PHPickerConfiguration.__primaryButtonType
- _OBJC_IVAR_$_PHPickerConfiguration.__secondaryButtonType
- _OBJC_IVAR_$_PHPickerUpdateConfiguration.__containerIdentifier
- _OBJC_IVAR_$_PHPickerUpdateConfiguration.__primaryButtonType
- _OBJC_IVAR_$_PHPickerUpdateConfiguration.__secondaryButtonType
- _PHLocalIdentifiersErrorKey
- __OBJC_$_INSTANCE_METHODS__TtC8PhotosUIP33_E2E20DF4EAC1FCE07E5336962A6E0BEF23_PHPickerOverlayStorage(PhotosUI)
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PHPickerViewControllerDelegate_Private
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_PHPickerViewControllerDelegate_Private
- __OBJC_$_PROTOCOL_METHOD_TYPES_PHPickerViewControllerDelegate_Private
- __OBJC_$_PROTOCOL_REFS_PHPickerViewControllerDelegate_Private
- __OBJC_CLASS_PROTOCOLS_$__TtC8PhotosUIP33_E2E20DF4EAC1FCE07E5336962A6E0BEF23_PHPickerOverlayStorage(PhotosUI)
- __OBJC_LABEL_PROTOCOL_$_PHPickerViewControllerDelegate_Private
- __OBJC_PROTOCOL_$_PHPickerViewControllerDelegate_Private
- ___74-[PHPickerResult _requestThumbnailImageURLForPreferredSize:resultHandler:]_block_invoke
- ___swift_memcpy144_8
- ___swift_memcpy632_8
- _associated conformance 8PhotosUI8PVSErrorO18SanitizedErrorCodeOSHAASQ
- _associated conformance So26_PHPickerPrimaryButtonTypeVSHSCSQ
- _associated conformance So28_PHPickerSecondaryButtonTypeVSHSCSQ
- _objc_msgSend$_primaryButtonType
- _objc_msgSend$_secondaryButtonType
- _objc_msgSend$_setContainerIdentifier:
- _objc_msgSend$_setPrimaryButtonType:
- _objc_msgSend$_setSecondaryButtonType:
- _objc_msgSend$set_containerIdentifier:
- _symbolic _____ 8PhotosUI8PVSErrorO18SanitizedErrorCodeO
- _symbolic _____ So26_PHPickerPrimaryButtonTypeV
- _symbolic _____ So28_PHPickerSecondaryButtonTypeV
- _symbolic _____Sg So26_PHPickerPrimaryButtonTypeV
- _symbolic _____Sg So28_PHPickerSecondaryButtonTypeV
- _symbolic _____ySSypG s17_NativeDictionaryV
CStrings:
+ "-[PHPickerAspectRatio initWithAspectRatio:]"
+ "-[PHPickerAspectRatio init]"
+ "-[PHPickerAspectRatio isEqual:]"
+ "-[PHPickerResult requestThumbnailImageURLForPreferredSize:resultHandler:]"
+ "PHOTOSUI_ERROR_ASSET_COLLECTION_CREATION_FAILED"
+ "PHOTOSUI_ERROR_ASSET_COLLECTION_NOT_FOUND"
+ "PHOTOSUI_ERROR_ASSET_COLLECTION_NOT_WRITABLE"
+ "PHOTOSUI_ERROR_ICLOUD_PHOTOS_NOT_ENABLED"
+ "PHOTOSUI_ERROR_SHARED_ALBUM_MIGRATION_IN_PROGRESS"
+ "PHPhotosUIErrorDomain"
+ "PHPickerSearchTextPrefersAutomaticFocusKey"
+ "S\""
+ "aA(3"
+ "collectionCreationFailed"
+ "collectionIsMigrating("
+ "collectionNotFound("
+ "collectionNotWritable("
+ "com.apple.PhotosUIPrivate"
+ "configuration.primaryButtonType >= 0"
+ "configuration.secondaryButtonType >= 0"
+ "iCloudPhotosNotEnabled"
+ "nilAssetCollectionType"
+ "nilPhotoKitObject("
+ "presenting the scene failed: "
+ "unavailableSystemPhotoLibrary"
+ "unknownAssetCollectionType"
+ "unsupportedPlatform"
- "-[PHPickerResult _requestThumbnailImageURLForPreferredSize:resultHandler:]"
- "QEg"
- "The target shared album is currently migrating. Operation not allowed."
- "User does not have permission to add content to the shared album with identifier: "
- "configuration._primaryButtonType >= 0"
- "configuration._secondaryButtonType >= 0"
```

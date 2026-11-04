## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/Versions/A/PhotosUI`

```diff

-916.58.114.0.0
-  __TEXT.__text: 0x511ac
-  __TEXT.__objc_methlist: 0x4d8c
-  __TEXT.__const: 0x3088
-  __TEXT.__oslogstring: 0x1135
-  __TEXT.__swift5_typeref: 0xe08
-  __TEXT.__swift5_fieldmd: 0xafc
+920.8.100.0.0
+  __TEXT.__text: 0x517c0
+  __TEXT.__objc_methlist: 0x4de4
+  __TEXT.__const: 0x30d8
   __TEXT.__constg_swiftt: 0xc34
+  __TEXT.__swift5_typeref: 0xe08
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__swift5_reflstr: 0xae1
+  __TEXT.__swift5_reflstr: 0xae6
+  __TEXT.__swift5_fieldmd: 0xafc
   __TEXT.__swift5_assocty: 0x348
-  __TEXT.__cstring: 0x5b75
-  __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_proto: 0x1a0
   __TEXT.__swift5_types: 0xf8
-  __TEXT.__swift5_mpenum: 0x8
+  __TEXT.__cstring: 0x5c4a
   __TEXT.__swift5_capture: 0x978
+  __TEXT.__oslogstring: 0x129f
   __TEXT.__swift_as_entry: 0x5c
-  __TEXT.__swift_as_cont: 0x54
   __TEXT.__swift_as_ret: 0x8
+  __TEXT.__swift_as_cont: 0x54
+  __TEXT.__swift5_protos: 0xc
+  __TEXT.__swift5_mpenum: 0x8
   __TEXT.__gcc_except_tab: 0x2cc
   __TEXT.__ustring: 0xd8
-  __TEXT.__unwind_info: 0x2588
+  __TEXT.__unwind_info: 0x25c8
   __TEXT.__eh_frame: 0xef8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x27c0
+  __DATA_CONST.__objc_selrefs: 0x27e0
   __DATA_CONST.__objc_protorefs: 0xf0
   __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__got: 0x670
   __AUTH_CONST.__const: 0x3550
-  __AUTH_CONST.__cfstring: 0x31a0
-  __AUTH_CONST.__objc_const: 0x9370
+  __AUTH_CONST.__cfstring: 0x3200
+  __AUTH_CONST.__objc_const: 0x9408
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0x8f0
+  __AUTH_CONST.__auth_got: 0x918
   __AUTH.__objc_data: 0x22d8
-  __AUTH.__data: 0x558
-  __DATA.__objc_ivar: 0x458
-  __DATA.__data: 0x1880
-  __DATA.__common: 0x178
+  __AUTH.__data: 0x560
+  __DATA.__objc_ivar: 0x464
+  __DATA.__data: 0x1870
   __DATA.__bss: 0x3310
+  __DATA.__common: 0x178
   __DATA_DIRTY.__objc_data: 0x430
   __DATA_DIRTY.__data: 0xe8
   __DATA_DIRTY.__bss: 0x200

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3493
-  Symbols:   4455
-  CStrings:  683
+  Functions: 3502
+  Symbols:   4467
+  CStrings:  688
 
Symbols:
+ -[PHPickerConfiguration _setTertiaryButtonType:]
+ -[PHPickerConfiguration _tertiaryButtonType]
+ -[PHPickerUpdateConfiguration _didSetTertiaryButtonType]
+ -[PHPickerUpdateConfiguration _setTertiaryButtonType:]
+ -[PHPickerUpdateConfiguration _tertiaryButtonType]
+ GCC_except_table1038
+ GCC_except_table1045
+ GCC_except_table1049
+ GCC_except_table1053
+ GCC_except_table176
+ GCC_except_table185
+ GCC_except_table3
+ GCC_except_table35
+ GCC_except_table574
+ GCC_except_table588
+ GCC_except_table596
+ GCC_except_table599
+ GCC_except_table745
+ GCC_except_table874
+ GCC_except_table9
+ _OBJC_IVAR_$_PHPickerConfiguration.__tertiaryButtonType
+ _OBJC_IVAR_$_PHPickerUpdateConfiguration.__didSetTertiaryButtonType
+ _OBJC_IVAR_$_PHPickerUpdateConfiguration.__tertiaryButtonType
+ _PLCurrentLibraryLogTag
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PHPickerViewControllerDelegate_Private
+ ___unnamed_6
+ _objc_msgSend$_pickerDidPerformTertiaryAction:
+ _objc_msgSend$_tertiaryButtonType
- GCC_except_table1170
- GCC_except_table1183
- GCC_except_table1188
- GCC_except_table1191
- GCC_except_table1271
- GCC_except_table148
- GCC_except_table157
- GCC_except_table261
- GCC_except_table288
- GCC_except_table357
- GCC_except_table554
- GCC_except_table561
- GCC_except_table569
- GCC_except_table573
- GCC_except_table773
- ___unnamed_5
CStrings:
+ "%{public}sCan't find item provider representation for the progress URL."
+ "%{public}sCan't find progress URL or its sandbox extension token."
+ "%{public}sCopied to URL (%@) (loadInPlaceFileRepresentationForTypeIdentifier:)"
+ "%{public}sCopying URL (%@) because (old SDK: %ld, explicit: %ld) (loadInPlaceFileRepresentationForTypeIdentifier:)"
+ "%{public}sCouldn't present cloud sync controls; view controller is nil."
+ "%{public}sError getting synchronous remote object proxy: %@"
+ "%{public}sIgnored progress updates for local progress (%@) because it's already cancelled."
+ "%{public}sNo matching local progress is found for remote progress (%@) with UUID (%@)."
+ "%{public}sPHPickerViewControllerDelegate doesn't respond to picker:didFinishPicking:"
+ "%{public}sPUPhotosFileProviderItemProvider: loadDataRepresentationForTypeIdentifier: %@"
+ "%{public}sPUPhotosFileProviderItemProvider: loadFileRepresentationForTypeIdentifier: %@"
+ "%{public}sPUPhotosFileProviderItemProvider: loadInPlaceFileRepresentationForTypeIdentifier: %@"
+ "%{public}sPUPhotosFileProviderItemProvider: loadObjectOfClass: %@"
+ "%{public}sPUPhotosFileProviderItemProviderFullyResolvingSymlinks resolved from %@ to %@"
+ "%{public}sPUPickerAssetMediaSubtypeFilter: invalid filter type: %ld"
+ "%{public}sPUPickerAssetMediaTypeFilter: invalid media type: %ld"
+ "%{public}sPUPickerAssetPlaybackStyleFilter: invalid playback style: %ld"
+ "%{public}sPUPickerCompoundFilter: invalid filter type: %ld"
+ "%{public}sPUPickerCompoundFilter: invalid subfilter: %@"
+ "%{public}sPUPickerCompoundFilter: invalid subfilters count: %lu"
+ "%{public}sPUPickerGroupsPeopleQuantityFilter: invalid member count range: [%ld, %ld]"
+ "%{public}sPUPickerItemIdentifiersFilter: invalid asset identifier count: %ld"
+ "%{public}sPUPickerOtherFilter: invalid filter type: %ld"
+ "%{public}sReceived invalid object (%@) or keypath (%@) for the progress context."
+ "%{public}sShowing picker unavailable UI (reason: %@) with error: %@"
+ "%{public}sShowing picker unavailable UI (updated) (reason: %@) with error: %@"
+ "%{public}sloadInPlaceFileRepresentationForTypeIdentifier: is not supported. Use loadFileRepresentationForTypeIdentifier: instead."
+ "%{public}slower selection limit is negative"
+ "%{public}sprimary button type is negative"
+ "%{public}ssecondary button type is negative"
+ "%{public}sselection limit is negative"
+ "%{public}stertiary button type is negative"
+ "PHPickerConfigurationCoderTertiaryButtonTypeKey"
+ "PHPickerUpdateConfigurationCoderDidSetTertiaryButtonTypeKey"
+ "PHPickerUpdateConfigurationCoderTertiaryButtonTypeKey"
+ "QEg"
+ "configuration._tertiaryButtonType >= 0"
- "Can't find item provider representation for the progress URL."
- "Can't find progress URL or its sandbox extension token."
- "Copied to URL (%@) (loadInPlaceFileRepresentationForTypeIdentifier:)"
- "Copying URL (%@) because (old SDK: %ld, explicit: %ld) (loadInPlaceFileRepresentationForTypeIdentifier:)"
- "Couldn't present cloud sync controls; view controller is nil."
- "Error getting synchronous remote object proxy: %@"
- "Ignored progress updates for local progress (%@) because it's already cancelled."
- "No matching local progress is found for remote progress (%@) with UUID (%@)."
- "PHPickerViewControllerDelegate doesn't respond to picker:didFinishPicking:"
- "PUPhotosFileProviderItemProvider: loadDataRepresentationForTypeIdentifier: %@"
- "PUPhotosFileProviderItemProvider: loadFileRepresentationForTypeIdentifier: %@"
- "PUPhotosFileProviderItemProvider: loadInPlaceFileRepresentationForTypeIdentifier: %@"
- "PUPhotosFileProviderItemProvider: loadObjectOfClass: %@"
- "PUPhotosFileProviderItemProviderFullyResolvingSymlinks resolved from %@ to %@"
- "PUPickerAssetMediaSubtypeFilter: invalid filter type: %ld"
- "PUPickerAssetMediaTypeFilter: invalid media type: %ld"
- "PUPickerAssetPlaybackStyleFilter: invalid playback style: %ld"
- "PUPickerCompoundFilter: invalid filter type: %ld"
- "PUPickerCompoundFilter: invalid subfilter: %@"
- "PUPickerCompoundFilter: invalid subfilters count: %lu"
- "PUPickerGroupsPeopleQuantityFilter: invalid member count range: [%ld, %ld]"
- "PUPickerItemIdentifiersFilter: invalid asset identifier count: %ld"
- "PUPickerOtherFilter: invalid filter type: %ld"
- "QEW"
- "Received invalid object (%@) or keypath (%@) for the progress context."
- "Showing picker unavailable UI (reason: %@) with error: %@"
- "Showing picker unavailable UI (updated) (reason: %@) with error: %@"
- "loadInPlaceFileRepresentationForTypeIdentifier: is not supported. Use loadFileRepresentationForTypeIdentifier: instead."
- "lower selection limit is negative"
- "primary button type is negative"
- "secondary button type is negative"
- "selection limit is negative"
```

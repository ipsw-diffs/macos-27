## com.apple.driver.IOImageLoader

> `com.apple.driver.IOImageLoader`

```diff

 375.3.0.0.0
   __TEXT.__cstring: 0x1f20
   __TEXT.__const: 0x9
-  __TEXT_EXEC.__text: 0x11db8
+  __TEXT_EXEC.__text: 0x11ff0
   __TEXT_EXEC.__auth_stubs: 0x330
   __DATA.__data: 0xc4
   __DATA.__common: 0x100
Functions:
~ __ZN20IOImageLoaderRequestD0Ev : 68 -> 72
~ __ZNK20IOImageLoaderRequest9MetaClass5allocEv : 104 -> 108
~ __ZN20IOImageLoaderRequest6detachEP9IOService : 160 -> 164
~ __ZN20IOImageLoaderRequest4freeEv : 152 -> 156
~ __ZN20IOImageLoaderRequest12withProviderEP9IOServiceP12OSDictionaryPKc : 276 -> 280
~ _GLOBAL__sub_I_IOImageLoaderRequest.cpp : 80 -> 84
~ __ZN28IOImageLoaderImageDictionary9MetaClassC1Ev : 72 -> 76
~ __ZN28IOImageLoaderImageDictionaryC2EPK11OSMetaClass : 52 -> 56
~ __ZN28IOImageLoaderImageDictionaryC1EPK11OSMetaClass : 52 -> 56
~ __ZN28IOImageLoaderImageDictionaryD0Ev : 68 -> 72
~ __ZN28IOImageLoaderImageDictionary9MetaClassC2Ev : 72 -> 76
~ __ZNK28IOImageLoaderImageDictionary9MetaClass5allocEv : 104 -> 108
~ __ZN28IOImageLoaderImageDictionaryC1Ev : 88 -> 92
~ __ZN28IOImageLoaderImageDictionaryC2Ev : 88 -> 92
~ __ZN28IOImageLoaderImageDictionary17doAttributesExistEPS_P8OSString : 164 -> 168
~ __ZN28IOImageLoaderImageDictionary17doAttributesExistEPS_PKc : 352 -> 356
~ __ZN28IOImageLoaderImageDictionary25doAllImagesHaveAttributesEPS_ : 292 -> 296
~ __ZN28IOImageLoaderImageDictionary13iterateImagesEPS_PKcPK11OSMetaClassPFbPK8OSStringS2_PK8OSObjectS5_PvSC_SC_SC_ESC_SC_SC_SC_ : 472 -> 476
~ __ZN28IOImageLoaderImageDictionary13getAttributesEPS_PK8OSString : 164 -> 168
~ __ZN28IOImageLoaderImageDictionary17isAttributeOfTypeEP12OSDictionaryPKcPK11OSMetaClass : 192 -> 196
~ __ZN28IOImageLoaderImageDictionary12getAttributeEP12OSDictionaryPKc : 168 -> 172
~ __ZN28IOImageLoaderImageDictionary36doAllImagesHaveAttributeOfObjectTypeEPS_PKcPK11OSMetaClassPFbPK8OSStringS2_PK8OSObjectS5_PvSC_SC_SC_ESC_SC_SC_SC_ : 428 -> 432
~ __ZN28IOImageLoaderImageDictionary30doAllImagesHaveUniqueAttributeEPS_PKc : 468 -> 472
~ __ZN28IOImageLoaderImageDictionary17isAttributeUniqueEPS_PKcPK8OSString : 188 -> 192
~ __ZN28IOImageLoaderImageDictionary12getAttributeEP12OSDictionaryPK8OSString : 164 -> 168
~ __ZN28IOImageLoaderImageDictionary15isImageRequiredEPS_PKc : 320 -> 324
~ __ZN28IOImageLoaderImageDictionary13getAttributesEPS_PKc : 196 -> 200
~ __ZN28IOImageLoaderImageDictionary15isImageRequiredEPS_PK8OSString : 164 -> 168
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithObjectEP12OSDictionaryPK8OSStringPK8OSObject : 180 -> 184
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithStringEP12OSDictionaryPK8OSStringPKc : 136 -> 140
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithStringEP12OSDictionaryPKcS3_ : 168 -> 172
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithStringEP12OSDictionaryPK8OSStringS4_ : 164 -> 168
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithStringEP12OSDictionaryPKcPK8OSString : 216 -> 220
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithNumberEP12OSDictionaryPK8OSStringy : 228 -> 232
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithNumberEP12OSDictionaryPKcy : 176 -> 180
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithNumberEP12OSDictionaryPK8OSStringPK8OSNumber : 316 -> 320
~ __ZN28IOImageLoaderImageDictionary22setAttributeWithNumberEP12OSDictionaryPKcPK8OSNumber : 308 -> 312
~ __ZN28IOImageLoaderImageDictionary23setAttributeWithBooleanEP12OSDictionaryPK8OSStringb : 208 -> 212
~ __ZN28IOImageLoaderImageDictionary23setAttributeWithBooleanEP12OSDictionaryPKcb : 156 -> 160
~ __ZN28IOImageLoaderImageDictionary23setAttributeWithBooleanEP12OSDictionaryPK8OSStringPK9OSBoolean : 268 -> 272
~ __ZN28IOImageLoaderImageDictionary23setAttributeWithBooleanEP12OSDictionaryPKcPK9OSBoolean : 220 -> 224
~ __ZN28IOImageLoaderImageDictionary19countAttributesWithEPS_PKcS2_ : 460 -> 464
~ __ZN28IOImageLoaderImageDictionary27getImageFromUniqueAttributeEPS_PKcS2_ : 496 -> 500
~ __ZN28IOImageLoaderImageDictionary27getImageFromUniqueAttributeEPS_PKcPK8OSString : 188 -> 192
~ __ZN28IOImageLoaderImageDictionary32getAttributesFromUniqueAttributeEPS_PKc : 140 -> 144
~ __ZN28IOImageLoaderImageDictionary27getImageFromUniqueImagetypeEPS_PK8OSString : 164 -> 168
~ _GLOBAL__sub_I_IOImageLoaderImageDictionary.cpp : 80 -> 84
~ __ZN22IOImageLoaderDatastore9MetaClassC1Ev : 72 -> 76
~ __ZN22IOImageLoaderDatastoreC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOImageLoaderDatastoreC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOImageLoaderDatastoreD0Ev : 68 -> 72
~ __ZN22IOImageLoaderDatastore9MetaClassC2Ev : 72 -> 76
~ __ZN22IOImageLoaderHashstore9MetaClassC1Ev : 72 -> 76
~ __ZN22IOImageLoaderHashstoreC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOImageLoaderHashstoreC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOImageLoaderHashstoreD0Ev : 68 -> 72
~ __ZN22IOImageLoaderHashstore9MetaClassC2Ev : 72 -> 76
~ __ZN22IOImageLoaderDatastore5startEP9IOService : 156 -> 160
~ __ZN22IOImageLoaderDatastore16requestImageLoadEP12OSDictionaryj : 480 -> 484
~ __ZN22IOImageLoaderDatastore18requestImageVerifyEP12OSDictionaryj : 468 -> 472
~ _GLOBAL__sub_I_IOImageLoaderDatastore.cpp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ __ZN17IOImageDescriptor9MetaClassC1Ev : 72 -> 76
~ __ZN17IOImageDescriptorC2EPK11OSMetaClass : 52 -> 56
~ __ZN17IOImageDescriptor9MetaClassC2Ev : 72 -> 76
~ _GLOBAL__sub_I_IOImageLoaderDescriptor.cpp : 80 -> 84
~ __ZN28IOImageLoaderDatastoreHelper32getImageInformationWithImageNameEP40IOImageLoaderDatastoreImageInformation_sPK29IOImageLoaderDatastoreIndex_sPKcj : 412 -> 416
~ __ZN28IOImageLoaderDatastoreHelper29getImageInformationWithDIGESTEP40IOImageLoaderDatastoreImageInformation_sPK29IOImageLoaderDatastoreIndex_sPKhj : 988 -> 992
~ __ZN28IOImageLoaderDatastoreHelper26getImageInformationWithSHAEP40IOImageLoaderDatastoreImageInformation_sPK29IOImageLoaderDatastoreIndex_sPKhj : 1092 -> 1096
~ __ZN28IOImageLoaderDatastoreHelper12displayIndexEPK29IOImageLoaderDatastoreIndex_s : 1168 -> 1172
~ __ZN28IOImageLoaderDatastoreHelper12publishIndexEPK9IOServicePK29IOImageLoaderDatastoreIndex_sb : 1388 -> 1392
~ __ZN28IOImageLoaderDatastoreHelper16requestImageLoadEPK29IOImageLoaderDatastoreIndex_sPKcP12OSDictionaryj : 344 -> 348
~ __ZL49_setImagesizeFromDatastoreImageDictionaryCallbackPK8OSStringPKcPK8OSObjectPK11OSMetaClassPvSA_SA_SA_ : 484 -> 488
~ __ZN28IOImageLoaderDatastoreHelper18requestImageVerifyEPK29IOImageLoaderDatastoreIndex_sPKcP12OSDictionaryj : 304 -> 308
~ __ZN23IOImageLoaderUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN23IOImageLoaderUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IOImageLoaderUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IOImageLoaderUserClientD0Ev : 68 -> 72
~ __ZN23IOImageLoaderUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK23IOImageLoaderUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN23IOImageLoaderUserClientC1Ev : 88 -> 92
~ __ZN23IOImageLoaderUserClientC2Ev : 88 -> 92
~ __ZN23IOImageLoaderUserClient14userMethodOpenEPS_PvP25IOExternalMethodArguments : 404 -> 408
~ __ZN23IOImageLoaderUserClient15userMethodCloseEPS_PvP25IOExternalMethodArguments : 208 -> 212
~ __ZN23IOImageLoaderUserClient24userMethodPrepareMappingEPS_PvP25IOExternalMethodArguments : 2124 -> 2128
~ __ZN23IOImageLoaderUserClient25userMethodCompleteMappingEPS_PvP25IOExternalMethodArguments : 1428 -> 1432
~ __ZN23IOImageLoaderUserClient25userMethodNotifyImageLoadEPS_PvP25IOExternalMethodArguments : 208 -> 212
~ __ZN23IOImageLoaderUserClient26userMethodRequestImageLoadEPS_PvP25IOExternalMethodArguments : 1404 -> 1408
~ __ZN23IOImageLoaderUserClient6detachEP9IOService : 404 -> 408
~ __ZN23IOImageLoaderUserClient11clientCloseEv : 416 -> 420
~ __ZN23IOImageLoaderUserClient17withIOImageLoaderEP13IOImageLoaderP4taskPvjP12OSDictionary : 832 -> 836
~ __ZN23IOImageLoaderUserClient5startEP9IOService : 112 -> 116
~ __ZN23IOImageLoaderUserClient4stopEP9IOService : 124 -> 128
~ __ZN23IOImageLoaderUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 396 -> 400
~ __ZN23IOImageLoaderUserClient19externalMethodGatedEPv : 1064 -> 1068
~ __ZN23IOImageLoaderUserClient12mapArgumentsEP25IOExternalMethodArgumentsPP11IOMemoryMapPPvPmS6_S7_b : 796 -> 800
~ __ZN23IOImageLoaderUserClient14unmapArgumentsEP25IOExternalMethodArgumentsPP11IOMemoryMapPPvS6_mb : 168 -> 172
~ _GLOBAL__sub_I_IOImageLoaderUserClient.cpp : 80 -> 84
~ __ZN13IOImageLoader9MetaClassC1Ev : 72 -> 76
~ __ZN13IOImageLoaderC2EPK11OSMetaClass : 52 -> 56
~ __ZN13IOImageLoaderC1EPK11OSMetaClass : 52 -> 56
~ __ZN13IOImageLoaderD0Ev : 68 -> 72
~ __ZN13IOImageLoader9MetaClassC2Ev : 72 -> 76
~ __ZNK13IOImageLoader9MetaClass5allocEv : 104 -> 108
~ __ZN13IOImageLoaderC1Ev : 88 -> 92
~ __ZN13IOImageLoaderC2Ev : 88 -> 92
~ __ZN13IOImageLoader5startEP9IOService : 156 -> 160
~ __ZN13IOImageLoader4freeEv : 240 -> 244
~ __ZN13IOImageLoader16initWithProviderEP9IOServiceR28IOImageDescriptorCallbacks_sPKc : 904 -> 908
~ __ZN13IOImageLoader31datastoreNotifierPublishHandlerEPvP9IOServiceP10IONotifier : 2092 -> 2096
~ __ZN13IOImageLoader34datastoreNotifierTerminatedHandlerEPvP9IOServiceP10IONotifier : 1556 -> 1560
~ __ZN13IOImageLoader31hashstoreNotifierPublishHandlerEPvP9IOServiceP10IONotifier : 2092 -> 2096
~ __ZN13IOImageLoader34hashstoreNotifierTerminatedHandlerEPvP9IOServiceP10IONotifier : 1556 -> 1560
~ __ZN13IOImageLoader12withProviderEP9IOServiceR28IOImageDescriptorCallbacks_sPKc : 348 -> 352
~ __ZN13IOImageLoader13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 280 -> 284
~ __ZN13IOImageLoader16requestImageLoadEP12OSDictionaryj : 1704 -> 1708
~ __ZN13IOImageLoader12isNetbootingEv : 612 -> 616
~ __ZN13IOImageLoader10isBootBaseEv : 784 -> 788
~ __ZN13IOImageLoader16loadNetbootImageEP12OSDictionaryj : 3560 -> 3564
~ __ZN13IOImageLoader13displayObjectEPKciPK8OSObject : 2508 -> 2512
~ __ZN13IOImageLoader18requestImageVerifyEP12OSDictionaryj : 1772 -> 1776
~ __ZN13IOImageLoader18processImageVerifyEP12OSDictionaryj : 2592 -> 2596
~ __ZN13IOImageLoader36doAllImagesHaveImageSizeRequirementsEP12OSDictionary : 280 -> 284
~ __ZN13IOImageLoader16prepareImageLoadEP4taskP12OSDictionary : 3432 -> 3436
~ __ZN13IOImageLoader17completeImageLoadEP4taskP12OSDictionary : 784 -> 788
~ __ZN13IOImageLoader15notifyImageLoadEP12OSDictionaryi : 228 -> 232
~ __ZN13IOImageLoader45copyImageFromDatastoreToImageDictionaryBufferEP12OSDictionary : 928 -> 932
~ __ZL54_copyImageFromDatastoreToImageDictionaryBufferCallbackPK8OSStringPKcPK8OSObjectPK11OSMetaClassPvSA_SA_SA_ : 2048 -> 2052
~ __ZN13IOImageLoader29requestImageLoadFromDatastoreEP12OSDictionary : 1864 -> 1868
~ __ZN13IOImageLoader14checkCSRAccessEv : 144 -> 148
~ __ZN13IOImageLoader29checkSHAForImageFromDatastoreEPKcjPKvy : 152 -> 156
~ __ZN13IOImageLoader36datastoreNotifierPublishHandlerGatedEPvP9IOServiceP10IONotifier : 484 -> 488
~ __ZN13IOImageLoader39datastoreNotifierTerminatedHandlerGatedEPvP9IOServiceP10IONotifier : 480 -> 484
~ __ZN13IOImageLoader10uncompressEPKhPmS1_m : 428 -> 432
~ __ZN13IOImageLoader6sha256EPhPKhj : 408 -> 412
~ __ZN13IOImageLoader3logEPKcz : 284 -> 288
~ __ZN13IOImageLoader28checkSHAForImageWithStoreSetEP5OSSetPKcjPKvy : 2884 -> 2888
~ __ZN13IOImageLoader29checkSHAForImageFromDatastoreEP8OSStringjPKvy : 160 -> 164
~ __ZN13IOImageLoader36hashstoreNotifierPublishHandlerGatedEPvP9IOServiceP10IONotifier : 484 -> 488
~ __ZN13IOImageLoader39hashstoreNotifierTerminatedHandlerGatedEPvP9IOServiceP10IONotifier : 480 -> 484
~ __ZL7z_allocPvjj : 88 -> 92
~ _GLOBAL__sub_I_IOImageLoader.cpp : 80 -> 84
```

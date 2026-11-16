## libobjc.A.dylib

> `/usr/lib/libobjc.A.dylib`

```diff

 973.2.0.0.0
-  __TEXT.__text: 0x39210
+  __TEXT.__text: 0x39190
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0x5ec
   __TEXT.__const: 0x4130
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ _map_images : 256 -> 260
~ _map_images_nolock : 9088 -> 9092
~ __ZL18__sel_registerNamePKcbb : 372 -> 380
~ _NXNextHashState : 128 -> 136
~ __ZL11getProtocolPKc : 148 -> 140
~ ____ZN10objc_class36setInstancesRequireRawIsaRecursivelyEb_block_invoke : 124 -> 116
~ _objc_release_x28 : 144 -> 152
~ __objc_rootDealloc : 76 -> 84
~ _objc_destructInstance : 68 -> 60
~ _load_images : 1588 -> 1584
~ __ZL19schedule_class_loadP10objc_class : 328 -> 332
~ _objc_autoreleasePoolPop : 380 -> 388
~ _objc_lookUpClass : 16 -> 24
~ _objc_setUncaughtExceptionHandler : 92 -> 84
~ _objc_setEnumerationMutationHandler : 24 -> 16
~ +[NSObject self] : 4 -> 12
~ _objc_initializeClassPair : 320 -> 312
~ __ZL14empty_getClassPKcPP10objc_class : 20 -> 12
~ _objc_registerClassPair : 540 -> 548
~ _NXMapInsert : 108 -> 100
~ _class_setVersion : 292 -> 284
~ +[NSObject new] : 72 -> 80
~ __objc_rootAllocWithZone : 268 -> 276
~ -[NSObject init] : 16 -> 8
~ _objc_getClass : 20 -> 12
~ _class_respondsToSelector_inst : 212 -> 204
~ __ZL20resolveMethod_lockedP11objc_objectP13objc_selectorP10objc_classi : 824 -> 832
~ -[NSObject isKindOfClass:] : 116 -> 124
~ _class_getName : 32 -> 24
~ +[NSObject superclass] : 40 -> 48
~ __ZN4objc12DenseMapInfoIPKcE7isEqualERKS2_S5_ : 96 -> 104
~ _class_getClassMethod : 72 -> 64
~ _class_getInstanceMethod : 292 -> 284
~ +[NSObject resolveClassMethod:] : 20 -> 12
~ _class_getProperty : 460 -> 452
~ -[NSObject conformsToProtocol:] : 132 -> 124
~ _class_getVersion : 140 -> 132
~ +[NSObject respondsToSelector:] : 20 -> 28
~ _objc_sync_enter : 44 -> 40
~ __ZL11fetch_cacheb : 272 -> 276
~ __objc_getClassForTag : 72 -> 68
~ _objc_sync_exit : 192 -> 196
~ _method_getImplementation : 48 -> 40
~ _method_getArgumentType : 200 -> 204
~ __ZL13SkipFirstTypePKc : 208 -> 212
~ _class_addMethod : 252 -> 244
~ _class_getInstanceVariable : 20 -> 28
~ __ZL7getIvarP10objc_classPKc : 200 -> 192
~ _method_getNumberOfArguments : 176 -> 168
~ _method_getName : 160 -> 152
~ _objc_retainAutorelease : 40 -> 32
~ __ZL32getExtendedTypesIndexesForMethodP10protocol_tPK8method_tbbRjS4_ : 172 -> 164
~ +[NSObject hash] : 16 -> 8
~ __ZL25protocol_getMethod_nolockP10protocol_tP13objc_selectorbbb : 280 -> 276
~ _objc_setProperty_atomic_copy : 196 -> 200
~ _objc_removeAssociatedObjects : 48 -> 44
~ _objc_copyStruct : 176 -> 188
~ _object_cxxConstructFromClass : 320 -> 312
~ _lookupMethodInClassAndLoadCache : 296 -> 304
~ _objc_unsafeClaimAutoreleasedReturnValue : 144 -> 136
~ __ZL27internal_class_getImageNameP10objc_classPPKc : 56 -> 64
~ -[NSObject methodForSelector:] : 76 -> 68
~ _objc_getAssociatedObject : 356 -> 364
~ ___getPreoptimizedClass_block_invoke : 32 -> 36
~ _objc_setProperty_nonatomic_copy : 112 -> 108
~ __ZN19AutoreleasePoolPage4killEv : 200 -> 208
~ _objc_getProtocol : 192 -> 184
~ _object_getClassName : 156 -> 148
~ _sel_getUid : 20 -> 12
~ _objc_destroyWeak : 260 -> 268
~ _method_getDescription : 60 -> 68
~ __ZL27_allocateTrampolinesAndDatav : 516 -> 520
~ _objc_setProperty_nonatomic : 120 -> 116
~ +[NSObject copyWithZone:] : 8 -> 16
~ _objc_setAssociatedObject : 1580 -> 1572
~ _class_getInstanceSize : 92 -> 84
~ _objc_constructInstance : 208 -> 200
~ +[NSObject methodForSelector:] : 76 -> 68
~ _class_copyMethodList : 3932 -> 3924
~ -[NSObject self] : 8 -> 12
~ __ZL12SubtypeUntilPKcc : 152 -> 148
~ __ZL9readClassP10objc_classbb : 1436 -> 1444
~ __Z29copyClassNamesForImage_nolockP11header_infoPj : 212 -> 204
~ _NXMapKeyCopyingInsert : 260 -> 252
~ _ivar_getOffset : 20 -> 28
~ _method_getReturnType : 164 -> 156
~ _objc_sync_nil : 16 -> 8
~ -[NSObject isFault] : 8 -> 16
~ _method_setImplementation : 440 -> 448
~ __ZL25_method_setImplementationP10objc_classP8method_tPFvvE : 348 -> 356
~ _method_exchangeImplementations : 860 -> 852
~ +[NSObject release] : 8 -> 16
~ _property_copyAttributeList : 412 -> 404
~ __objc_rootIsDeallocating : 44 -> 48
~ -[Protocol isEqual:] : 168 -> 172
~ __ZL27protocol_getProperty_nolockP10protocol_tPKcbb : 304 -> 312
~ +[NSObject isMemberOfClass:] : 20 -> 28
~ _sel_isEqual : 12 -> 20
~ _objc_moveWeak : 264 -> 268
~ _objc_copyCppObjectAtomic : 140 -> 136
~ __class_getIvarMemoryManagement : 80 -> 88
~ __ZL17realizeAllClassesv : 508 -> 500
~ ____ZL33objc_copyRealizedClassList_nolockPj_block_invoke : 36 -> 28
~ _class_addProtocol : 340 -> 348
~ __ZL12_NXMapRehashP11_NXMapTable : 232 -> 224
~ _objc_setHook_getClass : 160 -> 172
~ _objc_addLoadImageFunc : 288 -> 292
~ _class_replaceMethod : 320 -> 312
~ _objc_opt_self : 40 -> 48
~ _objc_setHook_getImageName : 168 -> 160
~ _objc_opt_class : 152 -> 144
~ _objc_readClassPair : 604 -> 612
~ __objc_flush_caches : 476 -> 484
~ _objc_copyImageNames : 440 -> 448
~ __ZL16scanMangledFieldRPKcS0_S1_Ri : 156 -> 160
~ __objc_atfork_prepare : 820 -> 816
~ __objc_atfork_parent : 740 -> 748
~ _property_copyAttributeValue : 256 -> 264
~ __ZL11_mapPtrHashP11_NXMapTablePKv : 8 -> 16
~ _objc_registerProtocol : 336 -> 328
~ __ZL16addRemappedClassP10objc_classS0_ : 456 -> 448
~ _class_replaceMethodsBulk : 344 -> 336
~ __ZL14_mapPtrIsEqualP11_NXMapTablePKvS2_ : 24 -> 16
~ __category_getLoadMethod : 1556 -> 1548
~ _weak_unregister_no_lock : 500 -> 492
~ __ZN10objc_class13demangledNameEb : 752 -> 744
~ _NXPtrIsEqual : 12 -> 20
~ _class_getIvarLayout : 64 -> 56
~ +[NSObject isAncestorOfObject:] : 120 -> 128
~ _class_getWeakIvarLayout : 48 -> 40
~ __ZL18fetch_handler_listb : 248 -> 256
~ _objc_getClassList : 204 -> 196
~ __ZL22load_categories_nolockP11header_info : 456 -> 452
~ _unmap_image : 1736 -> 1732
~ __ZL13remapClassRefPP10objc_classjbU13block_pointerFvjE : 492 -> 484
~ __ZN10objc_class14nameForLoggingEv : 396 -> 404
~ __ZL10free_classP10objc_class : 1508 -> 1516
~ __ZNK8method_t3impEb : 292 -> 300
~ __method_setImplementationRawUnsafe : 224 -> 232
~ __ZN8method_t6setImpEPFvvE : 368 -> 360
~ ___copy_helper_block_e8_32c43_ZTSKZ30method_exchangeImplementationsE3$_0 : 24 -> 16
~ __ZN15entsize_list_ttI8method_t13method_list_tLj4294901763ENS0_16pointer_modifierEE3endEv : 108 -> 100
~ _protocol_addProperty : 616 -> 624
~ ___copy_helper_block_e8_32c49_ZTSKZL33objc_copyRealizedClassList_nolockPjE3$_1 : 24 -> 16
~ __class_setCustomDeallocInitiation : 288 -> 280
~ __ZL35foreach_realized_class_and_subclassP10objc_classU13block_pointerFbS0_E : 184 -> 176
~ _objc_copyProtocolList : 1044 -> 1052
~ __ZNK10class_rw_t7methodsEv : 192 -> 200
~ _objc_copyImageHeaders : 428 -> 436
~ __ZN10class_rw_t16extAllocIfNeededEv : 72 -> 64
~ _objc_debug_class_getNameRaw : 144 -> 136
~ __ZL35realizeAndInitializeIfNeeded_lockedP11objc_objectP10objc_classb : 192 -> 184
~ _gdb_object_getClass : 140 -> 132
~ ___copy_helper_block_e8_32c64_ZTSKZN10objc_class36setInstancesRequireRawIsaRecursivelyEbE3$_0 : 12 -> 20
~ _objc_setHook_lazyClassNamer : 164 -> 172
~ __ZL24make_ro_writeable_nolockP10objc_class : 108 -> 100
~ _class_setIvarLayout : 440 -> 448
~ __ZL24make_ro_writeable_nolockP10class_rw_t : 156 -> 148
~ __ZL43_class_conformsToProtocol_unrealized_nolockP10objc_classP8Protocol : 732 -> 740
~ __ZN10objc_class15setInstanceSizeEj : 120 -> 112
~ _objc_disposeClassPair : 532 -> 540
~ __ZL13getChildClassP10objc_classM14metaclass_rw_tS0_ : 148 -> 140
~ __objc_getFreedObjectClass : 20 -> 12
~ ___copy_helper_block_e8_32c67_ZTSKZL25_method_setImplementationP10objc_classP8method_tPFvvEE3$_0 : 20 -> 12
~ __ZNSt3__16vectorIPK14mach_header_64NS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 208 -> 216
~ __ZL22getMethodFromListArrayIPP13method_list_tEP8method_tT_jP13objc_selector : 1484 -> 1476
~ __ZN4objc7Scanner13isSwiftObjectEP10objc_class : 104 -> 96
~ __ZL27getClassFromNamedClassTablePKc : 124 -> 116
~ ___copy_helper_block_e8_32c43_ZTSKZL13setSuperclassP10objc_classS0_E3$_1 : 12 -> 4
~ __ZNK13list_array_ttI10property_t15property_list_t6RawPtrE8validateEv : 592 -> 600
~ __objc_sync_enter_kind : 120 -> 116
~ __objc_patch_root_of_class : 552 -> 548
~ _objc_msgSend_thunk : 4 -> 8
~ __ZN17loadImageCallbackaSERKS_ : 144 -> 140
~ __ZNK4objc12DenseMapBaseINS_8DenseMapIPK8method_tP23objc_method_descriptionNS_17DenseMapValueInfoIS6_EENS_12DenseMapInfoIS4_EENS_6detail12DenseMapPairIS4_S6_EEEES4_S6_S8_SA_SD_E22FatalCorruptHashTablesEPKSD_j : 88 -> 96
~ __Z26objc_defaultForwardHandlerP11objc_objectP13objc_selector : 104 -> 116
~ __ZNK4objc12DenseMapBaseINS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S4_EEEES3_S4_S6_S8_SB_E22FatalCorruptHashTablesEPKSB_j : 96 -> 92
```

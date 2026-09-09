## CoreData

> `/System/Library/Frameworks/CoreData.framework/Versions/A/CoreData`

```diff

 1629.1.0.0.0
-  __TEXT.__text: 0x38edb4
+  __TEXT.__text: 0x38eff0
   __TEXT.__objc_methlist: 0x10cd0
   __TEXT.__const: 0x2e20
   __TEXT.__cstring: 0x3d4d2
Functions:
~ __PFRawFastIndexForKnownKey : 1212 -> 1224
~ __newFetchedRowsForRequest : 8568 -> 8544
~ _newFetchedRowsForFetchPlan_MT : 9344 -> 9256
~ -[_PFContextMapTable getAllObjects:] : 300 -> 308
~ -[NSEntityDescription(_NSInternalMethods) attributeKeys] : 164 -> 160
~ +[_NSXPCStoreUtilities _decodeResultSetData:forFetchRequest:options:store:context:rowCacheRows:error:] : 10220 -> 10552
~ -[NSManagedObjectContext(_NSInternalNotificationHandling) _processChangedStoreConfigurationNotification:] : 2792 -> 2776
~ -[NSManagedObject diffOrderedSets:::::::] : 2104 -> 2096
~ -[NSEntityDescription(_NSInternalMethods) toManyRelationshipKeys] : 472 -> 476
~ -[NSEntityDescription(_NSInternalMethods) toOneRelationshipKeys] : 476 -> 480
~ -[NSEntityDescription(_NSInternalMethods) _newSnowLeopardStyleDictionaryContainingPropertiesOfType:] : 236 -> 232
~ __PFRawFastIndexForKnownCString : 192 -> 204
~ __PFPopulateRowSnapshotFromFetchedRow : 4580 -> 4648
~ __prepareBufferedDictionaryResult : 1520 -> 1524
~ _$sSD8CoreDataSSRszypRs_rlE8setValue_15atParsedKeyPathyyp_SaySSGtF : 1484 -> 1488
~ _$s8CoreData13CDSwiftResultV5indexAC5ValueOSgSi_tcis : 5892 -> 5896
~ _$s8CoreData13CDSwiftResultV19makeMappingStrategy3for18includeSubentitiesAA09KnownKeysK15TypesDictionaryC0fG0CSo19NSEntityDescriptionC_SbtFZ20collectAllPropertiesL_4fromSDySSSo010NSPropertyP0CGAL_tF : 2220 -> 2240
~ _$s8CoreData24precomputeColumnMetadata4plan15mappingStrategySayAA0dE0VGSo15FetchEntityPlanaz_AA09KnownKeysL15TypesDictionaryC07MappingH0CtF : 3580 -> 3612
~ _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtFys4SpanVySo0qwV0aGXEfU_ : 10488 -> 10492
~ _$s8CoreData09KnownKeysC15TypesDictionaryC15MappingStrategyC07keysAnyE8MetadataAESaySS_ypXpxtG_tclufcAA25CDSwiftResultPropertyKindO_Tg5 : 3964 -> 3976
~ _$s8CoreData13CDSwiftResultV4make9resultSet14requestContext15objectIDFactorySayAA01_cD0CGSpySo05FetchdG0aG_So017NSSQLFetchRequestI0CSo17NSManagedObjectIDCs5Int64VcSo11NSSQLEntityCcSgtFZTf4nnnd_n : 5744 -> 5752
~ _$s8CoreData06NSCoreB22CodableAdapterRegistryC8register7adapteryAA0cbdE7Factory_p_tFySDySSAaF_pGzYbXEfU_ : 780 -> 788
~ _$sSDyq_Sgxciss11AnyHashableV_ypTg5 : 1224 -> 1228
~ _$sSDyq_SgxcisSS_So12NSExpressionCTg5 : 1168 -> 1180
~ _$sSo31NSCoreDataCoreSpotlightDelegateC0cB0E21IndexDidUpdateMessageV04makeI0yAESg10Foundation12NotificationVFZ : 480 -> 488
~ _$s8CoreData28prefetchSwiftResultsViaStoreyySo7NSArrayC_ADSo22NSManagedObjectContextCtFyyXEfU_ : 6984 -> 6976
~ _$s8CoreData24fulfillSwiftToManyFaultsyySayAA14_CDSwiftResultCG_S2SAEtF : 3972 -> 3964
~ _$s8CoreData018fulfillSwiftManyToE6FaultsyySayAA14_CDSwiftResultCG_SSSDySo17NSManagedObjectIDCSayAGGGAEtF : 2824 -> 2832
~ _$s8CoreData23fulfillSwiftToOneFaultsyySayAA14_CDSwiftResultCG_SSAEtF : 2736 -> 2744
~ _$s8CoreData42fulfillSwiftToManyFaultsWithVirtualInverseyySayAA14_CDSwiftResultCG_S2SAEtF : 2420 -> 2428
~ _$s8CoreData038newDestinationOIDsForToManyWithInverseG3One33_CD39D8E76975166D59535179C10A3A85LLySDySo17NSManagedObjectIDCSayAEGGSo24NSSQLFetchRequestContextC_AFSo07NSSQLToK0CtF : 2868 -> 2872
~ _$s8CoreData29executePrefetchAsSwiftResults33_CD39D8E76975166D59535179C10A3A85LL5fetch21substitutionVariables14requestContextSayAA14_CDSwiftResultCGSo21NSCachingFetchRequestC_SDySSSo12NSExpressionCGSo010NSSQLFetchxS0CtF : 956 -> 960
~ _$sSTsE7flatMapySay7ElementQyd__Gqd__ABQzKXEKSTRd__lFSD6ValuesVySo17NSManagedObjectIDCSayAIG_G_AJTg5095$s8CoreData23prefetchForSwiftResultsyySo7NSArrayC_So24NSSQLFetchRequestContextCtFyyXEfU_SaySo17eF12IDCGAIXEfU1_Tf1cn_n : 884 -> 868
~ _$s8CoreData34populateToManyFaultForRelationship33_CD39D8E76975166D59535179C10A3A85LL7results10sourceOIDs7relName12relationship0S6Entity14requestContextySayAA14_CDSwiftResultCG_SaySo17NSManagedObjectIDCGSSSo25NSRelationshipDescriptionCSo19NSEntityDescriptionCSo017NSSQLFetchRequestX0CtF : 4296 -> 4288
~ _$s8CoreData26extractToManyFaultMappingsySo12NSDictionaryCSo7NSArrayC_So24NSSQLFetchRequestContextCtF : 3532 -> 3540
~ _$s8CoreData09KnownKeysC15TypesDictionaryC15MappingStrategyC07keysAnyE0AESaySS_ypXptG_tcfc : 2832 -> 2816
~ _$s8CoreData09KnownKeysC15TypesDictionaryC15MappingStrategyC07keysAnyE8MetadataAESaySS_ypXpxtG_tclufc : 4432 -> 4440
~ _$ss17_NativeDictionaryV4copyyyFABySSq_GSSRszr0_lIetMl_Tp5 : 648 -> 656
~ _$sSo28NSPersistentStoreCoordinatorC8CoreDataE22StoresDidChangeMessageV04makeI0yAESg10Foundation12NotificationVFZTm : 2296 -> 2308
~ _$sSo28NSPersistentStoreCoordinatorC8CoreDataE22StoresDidChangeMessageV16makeNotificationy10Foundation0K0VAEFZTm : 3032 -> 3040
~ _$sSo28NSPersistentStoreCoordinatorC8CoreDataE19RemoteChangeMessageV04makeH0yAESg10Foundation12NotificationVFZ : 1344 -> 1356
~ _$sSo28NSPersistentStoreCoordinatorC8CoreDataE19RemoteChangeMessageV16makeNotificationy10Foundation0J0VAEFZ : 1432 -> 1420
~ _$sSo29NSPersistentCloudKitContainerC8CoreDataE19EventChangedMessageV04makeI0yAESg10Foundation12NotificationVFZ : 284 -> 288
~ _$s10Foundation10CocoaErrorV8CoreDataE13validationKeySSSgvg : 220 -> 224
~ _$s10Foundation10CocoaErrorV8CoreDataE19validationPredicateSo11NSPredicateCSgvg : 216 -> 220
~ _$s10Foundation10CocoaErrorV8CoreDataE16validationObjectypSgvgTm : 192 -> 196
~ _$s10Foundation10CocoaErrorV8CoreDataE14affectedStoresSayyXlGSgvgTm : 240 -> 244
~ _$sSo22NSManagedObjectContextC8CoreDataE14DidSaveMessageV04makeH0yAESg10Foundation12NotificationVFZ : 7692 -> 7712
~ _$sSo22NSManagedObjectContextC8CoreDataE23ObjectsDidChangeMessageV04makeI0yAESg10Foundation12NotificationVFZ : 11216 -> 11240
~ _$sSo22NSManagedObjectContextC8CoreDataE07DidSaveB10IDsMessageV04makeI0yAESg10Foundation12NotificationVFZ : 12704 -> 12736
~ _$sSo22NSManagedObjectContextC8CoreDataE07DidSaveB10IDsMessageV16makeNotificationy10Foundation0K0VAEFZTm : 5408 -> 5420
~ _$sSo22NSManagedObjectContextC8CoreDataE07DidSaveB15IDsAsyncMessageV04makeJ0yAESg10Foundation12NotificationVFZTm : 12464 -> 12492
```

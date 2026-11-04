## CoreData

> `/System/Library/Frameworks/CoreData.framework/Versions/A/CoreData`

```diff

-1634.0.0.0.0
-  __TEXT.__text: 0x389648
-  __TEXT.__objc_methlist: 0x10d30
+1635.0.0.0.0
+  __TEXT.__text: 0x38fe2c
+  __TEXT.__objc_methlist: 0x10df0
   __TEXT.__const: 0x2e50
-  __TEXT.__cstring: 0x3d684
+  __TEXT.__cstring: 0x3dd59
   __TEXT.__swift5_typeref: 0x12e8
   __TEXT.__constg_swiftt: 0x9d8
   __TEXT.__swift5_reflstr: 0x7e3

   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x2c
-  __TEXT.__oslogstring: 0x36d2f
-  __TEXT.__gcc_except_tab: 0x1aa68
-  __TEXT.__unwind_info: 0x8e60
+  __TEXT.__oslogstring: 0x37b9a
+  __TEXT.__gcc_except_tab: 0x1b004
+  __TEXT.__unwind_info: 0x8f80
   __TEXT.__eh_frame: 0x9d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x13a8
-  __DATA_CONST.__objc_classlist: 0xf08
+  __DATA_CONST.__const: 0x13f0
+  __DATA_CONST.__objc_classlist: 0xf10
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x64d0
+  __DATA_CONST.__objc_selrefs: 0x6540
   __DATA_CONST.__objc_protorefs: 0x38
-  __DATA_CONST.__objc_superrefs: 0xbf8
-  __DATA_CONST.__objc_arraydata: 0x8920
+  __DATA_CONST.__objc_superrefs: 0xc00
+  __DATA_CONST.__objc_arraydata: 0x8930
   __DATA_CONST.__got: 0xcf0
-  __AUTH_CONST.__const: 0x6b10
-  __AUTH_CONST.__cfstring: 0x20b80
-  __AUTH_CONST.__objc_const: 0x26370
+  __AUTH_CONST.__const: 0x6cc0
+  __AUTH_CONST.__cfstring: 0x20dc0
+  __AUTH_CONST.__objc_const: 0x26530
   __AUTH_CONST.__objc_dictobj: 0x26c0
-  __AUTH_CONST.__objc_arrayobj: 0x8fb8
+  __AUTH_CONST.__objc_arrayobj: 0x8fd0
   __AUTH_CONST.__objc_intobj: 0x570
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1648
-  __AUTH.__objc_data: 0x2fb8
-  __AUTH.__data: 0x1d8
-  __DATA.__objc_ivar: 0x18c8
+  __AUTH.__objc_data: 0x3008
+  __AUTH.__data: 0x1e8
+  __DATA.__objc_ivar: 0x18e0
   __DATA.__data: 0x16c0
-  __DATA.__bss: 0x16c8
+  __DATA.__bss: 0x16d8
   __DATA.__common: 0x488
-  __DATA_DIRTY.__objc_ivar: 0x520
+  __DATA_DIRTY.__objc_ivar: 0x524
   __DATA_DIRTY.__objc_data: 0x68c8
   __DATA_DIRTY.__data: 0x598
   __DATA_DIRTY.__common: 0x180
-  __DATA_DIRTY.__bss: 0x718
+  __DATA_DIRTY.__bss: 0x730
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9272
-  Symbols:   20077
-  CStrings:  8473
+  Functions: 9329
+  Symbols:   20161
+  CStrings:  8546
 
Symbols:
+ +[NSPersistentCloudKitContainer decodeAudienceIdentifiersOnShare:error:]
+ +[PFCloudKitSerializer getValueFromRecord:forKey:isEncrypted:]
+ -[NSCloudKitMirroringDelegate _finishedDeletingShareRecordForRequest:context:withDeletedRecordIDs:error:]
+ -[NSCloudKitMirroringDelegate _performStopShareRequest:]
+ -[NSCloudKitMirroringDelegateOptions setUseManagedSharing:]
+ -[NSCloudKitMirroringDelegateOptions useManagedSharing]
+ -[NSCloudKitMirroringStopSharingRequest copyWithZone:]
+ -[NSCloudKitMirroringStopSharingRequest dealloc]
+ -[NSCloudKitMirroringStopSharingRequest initWithOptions:completionBlock:]
+ -[NSCloudKitMirroringStopSharingRequest setZonesToStopSharing:]
+ -[NSCloudKitMirroringStopSharingRequest zonesToStopSharing]
+ -[NSPersistentCloudKitContainer _doPurgeForObjectsAndRecordsInZoneWithID:inPersistentStore:withContext:error:]
+ -[NSPersistentCloudKitContainer _shareManagedObjects:toShare:orZoneWithID:forAudiences:completion:]
+ -[NSPersistentCloudKitContainer shareManagedObjects:toRecordZoneWithID:forAudiences:completion:]
+ -[NSPersistentCloudKitContainer stopSharingObjectsInSharedZoneWithID:completion:]
+ -[NSPersistentCloudKitContainerOptions setUseManagedSharing:]
+ -[NSPersistentCloudKitContainerOptions useManagedSharing]
+ -[PFCloudKitArchivingUtilities decodeAudienceIDs:error:]
+ -[PFCloudKitArchivingUtilities encodeAudienceIDs:error:]
+ -[PFCloudKitContainerProvider createShareManagerForContainer:]
+ -[PFCloudKitExporter _setUpShare:withManager:archivingUtilities:]
+ -[PFCloudKitExporter updateManagedSharesIfNecessary]
+ -[PFCloudKitSerializer setValue:forKey:onRecord:]
+ -[PFCloudKitSetupAssistant shareManager]
+ GCC_except_table93
+ _CloudKitSharingManagementCKSMAudienceIdentifierFunction
+ _CloudKitSharingManagementCKSMShareManagerFunction
+ _LoadCloudKitSharingManagement.frameworkLibrary
+ _NSPersistentCloudKitContainerUsesManagedSharingKey
+ _OBJC_CLASS_$_NSCloudKitMirroringStopSharingRequest
+ _OBJC_IVAR_$_NSCloudKitMirroringDelegate._shareManager
+ _OBJC_IVAR_$_NSCloudKitMirroringDelegateOptions._useManagedSharing
+ _OBJC_IVAR_$_NSCloudKitMirroringRequestManager._pendingStopShareRequest
+ _OBJC_IVAR_$_NSCloudKitMirroringStopSharingRequest._zonesToStopSharing
+ _OBJC_IVAR_$_NSPersistentCloudKitContainerOptions._useManagedSharing
+ _OBJC_IVAR_$_PFCloudKitSetupAssistant._shareManager
+ _OBJC_METACLASS_$_NSCloudKitMirroringStopSharingRequest
+ __OBJC_$_INSTANCE_METHODS_NSCloudKitMirroringStopSharingRequest
+ __OBJC_$_INSTANCE_VARIABLES_NSCloudKitMirroringStopSharingRequest
+ __OBJC_$_PROP_LIST_NSCloudKitMirroringStopSharingRequest
+ __OBJC_CLASS_RO_$_NSCloudKitMirroringStopSharingRequest
+ __OBJC_METACLASS_RO_$_NSCloudKitMirroringStopSharingRequest
+ ___105-[NSCloudKitMirroringDelegate _finishedDeletingShareRecordForRequest:context:withDeletedRecordIDs:error:]_block_invoke
+ ___52-[PFCloudKitExporter updateManagedSharesIfNecessary]_block_invoke
+ ___52-[PFCloudKitExporter updateManagedSharesIfNecessary]_block_invoke_2
+ ___56-[NSCloudKitMirroringDelegate _performStopShareRequest:]_block_invoke
+ ___56-[NSCloudKitMirroringDelegate _performStopShareRequest:]_block_invoke_2
+ ___56-[NSCloudKitMirroringDelegate _performStopShareRequest:]_block_invoke_3
+ ___60-[NSCloudKitMirroringDelegate _performMetadataResetRequest:]_block_invoke_2
+ ___60-[PFCloudKitExporter _stopSharingSharesInZones:withManager:]_block_invoke
+ ___62-[PFCloudKitExporter _setUpShareFinishedWithShare:setUpError:]_block_invoke
+ ___62-[PFCloudKitExporter _setUpShareFinishedWithShare:setUpError:]_block_invoke_2
+ ___65-[PFCloudKitExporter _setUpShare:withManager:archivingUtilities:]_block_invoke
+ ___65-[PFCloudKitExporter _setUpShare:withManager:archivingUtilities:]_block_invoke_2
+ ___81-[NSPersistentCloudKitContainer stopSharingObjectsInSharedZoneWithID:completion:]_block_invoke
+ ___95-[NSPersistentCloudKitContainer _doStopShareForZoneWithID:inPersistentStore:withContext:error:]_block_invoke
+ ___99-[NSPersistentCloudKitContainer _shareManagedObjects:toShare:orZoneWithID:forAudiences:completion:]_block_invoke
+ ___LoadCloudKitSharingManagement_block_invoke
+ ___block_descriptor_112_e8_32o40o48o56o64r72r80r88r96r104r_e5_v8?0l
+ ___block_descriptor_113_e8_32o40o48o56o64o72o80r88r96r_e32_v16?0"NSManagedObjectContext"8l
+ ___block_descriptor_32_e36_v24?0"CKRecordZoneID"8"NSError"16l
+ ___block_descriptor_32_e41_v32?0"NSArray"8"NSArray"16"NSError"24l
+ ___block_descriptor_40_e8_32w_e29_v24?0"CKShare"8"NSError"16l
+ ___block_descriptor_56_e8_32o40o48w_e36_v24?0"CKRecordZoneID"8"NSError"16l
+ ___block_descriptor_72_e8_32o40o48o56o64w_e41_v32?0"NSArray"8"NSArray"16"NSError"24l
+ ___block_descriptor_72_e8_32o40o48o56r64r_e41_v32?0"NSArray"8"NSArray"16"NSError"24l
+ ___block_descriptor_88_e8_32o40o48o56o64o72o80o_e5_v8?0l
+ ___block_descriptor_96_e8_32o40o48r56r64r72r80r88r_e5_v8?0l
+ ___copy_helper_block_e8_32o40o48o56o64o72o80o
+ ___copy_helper_block_e8_32o40o48o56o64r72r80r88r96r104r
+ ___copy_helper_block_e8_32o40o48r56r64r72r80r88r
+ ___destroy_helper_block_e8_32o40o48o56o64o72o80o
+ ___destroy_helper_block_e8_32o40o48o56o64r72r80r88r96r104r
+ ___destroy_helper_block_e8_32o40o48r56r64r72r80r88r
+ _getCloudKitSharingManagementCKSMAudienceIdentifierClass
+ _getCloudKitSharingManagementCKSMShareManagerClass
+ _initCloudKitSharingManagementCKSMAudienceIdentifier
+ _initCloudKitSharingManagementCKSMShareManager
+ _objc_msgSend$createShareManagerForContainer:
+ _objc_msgSend$getValueFromRecord:forKey:isEncrypted:
+ _objc_msgSend$recordChangeTag
+ _objc_msgSend$setZonesToStopSharing:
+ _objc_msgSend$setupShareWithRecordZoneID:audiences:qualityOfService:retryOnFailure:completionHandler:
+ _objc_msgSend$shareManager
+ _objc_msgSend$stopShareWithRecordZoneID:qualityOfService:completionHandler:
+ _objc_msgSend$useManagedSharing
+ _objc_msgSend$valuesByKey
+ _objc_msgSend$zonesToStopSharing
- GCC_except_table130
- GCC_except_table132
- ___72-[NSPersistentCloudKitContainer shareManagedObjects:toShare:completion:]_block_invoke
- ___block_descriptor_104_e8_32o40o48o56o64o72r80r88r_e32_v16?0"NSManagedObjectContext"8l
CStrings:
+ " useManagedSharing:%@"
+ "### Failed to Soft Link: /System/Library/PrivateFrameworks/CloudKitSharingManagement.framework/CloudKitSharingManagement\n%s"
+ "-[NSCloudKitMirroringDelegate _performMetadataResetRequest:]_block_invoke_2"
+ "-[NSCloudKitMirroringDelegate _performResetZoneRequest:]_block_invoke_3"
+ "-[NSCloudKitMirroringDelegate _performStopShareRequest:]_block_invoke"
+ "-[NSPersistentCloudKitContainer _shareManagedObjects:toShare:orZoneWithID:forAudiences:completion:]"
+ "-[NSPersistentCloudKitContainer _shareManagedObjects:toShare:orZoneWithID:forAudiences:completion:]_block_invoke"
+ "-[NSPersistentCloudKitContainer shareManagedObjects:toRecordZoneWithID:forAudiences:completion:] cannot be used unless 'NSPersistentCloudKitContainerOptions.useManagedSharing' is set."
+ "-[PFCloudKitExporter _setUpShare:withManager:archivingUtilities:]"
+ "-[PFCloudKitExporter _setUpShare:withManager:archivingUtilities:]_block_invoke_2"
+ "-[PFCloudKitExporter _setUpShareFinishedWithShare:setUpError:]"
+ "-[PFCloudKitExporter updateManagedSharesIfNecessary]_block_invoke"
+ "-[PFCloudKitExporter updateManagedSharesIfNecessary]_block_invoke_2"
+ "-[PFCloudKitSchemaGenerator newRepresentativeRecords:]_block_invoke_2"
+ "/System/Library/PrivateFrameworks/CloudKitSharingManagement.framework/CloudKitSharingManagement"
+ "CD_audienceIDs"
+ "CD_audienceIDs_ckAsset"
+ "CD_usesManagedSharing"
+ "CKSMAudienceIdentifier"
+ "CKSMShareManager"
+ "CoreData+CloudKit: %s(%d): %@: Asked to stop sharing zone: %@"
+ "CoreData+CloudKit: %s(%d): %@: Asking share manager to update share: %@"
+ "CoreData+CloudKit: %s(%d): %@: Exporting unsaved managed share: %@"
+ "CoreData+CloudKit: %s(%d): %@: Failed to generate a representative record for this managed object: %@\n%@"
+ "CoreData+CloudKit: %s(%d): %@: Failed to update share '%@' due to error: %@"
+ "CoreData+CloudKit: %s(%d): %@: Fatal exception trying to update managed shares: %@"
+ "CoreData+CloudKit: %s(%d): %@: Finished export of unsaved managed share: %@\n%@"
+ "CoreData+CloudKit: %s(%d): %@: Share manager finished updating share: %@"
+ "CoreData: A share is marked for mutation and using managed sharing but has lost its audience. This needs client recovery to re-assign the audience. %@"
+ "CoreData: Both of these should not be set. shareToStart has primacy."
+ "CoreData: Can only stop sharing one zone at a time with managed sharing."
+ "CoreData: CloudKit Stop Share"
+ "CoreData: Failed: %@"
+ "CoreData: Illegal stop sharing request, no zones were specified. %@"
+ "CoreData: Modify record zones operation succeeded but did not delete the schema generator's zone? %@\n%@"
+ "CoreData: Modify record zones operation succeeded but did not save the schema generator's zone? %@\n%@"
+ "CoreData: Persistent store has no mirroring delegate, this should have been validated before invoking this method: %@"
+ "CoreData: Should handle success and errors here."
+ "CoreData: This is weird... why are both the share and zoneID set? One should be set for managed shares and the other for traditional calls to shareManagedObjects..."
+ "CoreData: This needs to be merged with the pending request (zoneIDs need to be combined so that multiple stop share requestes are made, also... test that..."
+ "CoreData: This should have been set."
+ "CoreData: When did the schema generator start making more than one shared zone? %@\n%@"
+ "CoreData: Why are we here. This metadata was returned but not dirty? %@"
+ "CoreData: Woohoo. Update the metadata and nuke the encoded share blob."
+ "CoreData: Wtf... saved more than one record for a single record? %@"
+ "CoreData: fault: A share is marked for mutation and using managed sharing but has lost its audience. This needs client recovery to re-assign the audience. %@\n"
+ "CoreData: fault: Both of these should not be set. shareToStart has primacy.\n"
+ "CoreData: fault: Can only stop sharing one zone at a time with managed sharing.\n"
+ "CoreData: fault: Failed: %@\n"
+ "CoreData: fault: Illegal stop sharing request, no zones were specified. %@\n"
+ "CoreData: fault: Modify record zones operation succeeded but did not delete the schema generator's zone? %@\n%@\n"
+ "CoreData: fault: Modify record zones operation succeeded but did not save the schema generator's zone? %@\n%@\n"
+ "CoreData: fault: Persistent store has no mirroring delegate, this should have been validated before invoking this method: %@\n"
+ "CoreData: fault: Should handle success and errors here.\n"
+ "CoreData: fault: This is weird... why are both the share and zoneID set? One should be set for managed shares and the other for traditional calls to shareManagedObjects...\n"
+ "CoreData: fault: This needs to be merged with the pending request (zoneIDs need to be combined so that multiple stop share requestes are made, also... test that...\n"
+ "CoreData: fault: This should have been set.\n"
+ "CoreData: fault: When did the schema generator start making more than one shared zone? %@\n%@\n"
+ "CoreData: fault: Why are we here. This metadata was returned but not dirty? %@\n"
+ "CoreData: fault: Woohoo. Update the metadata and nuke the encoded share blob.\n"
+ "CoreData: fault: Wtf... saved more than one record for a single record? %@\n"
+ "Managed sharing cannot be used with the public database (it does not support custom zones, or sharing)."
+ "Mismatch on the value store for %@"
+ "This 'NSPersistentCloudKitContainer' has been configured to use managed shares but -[NSPersistentCloudKitContainer %@] was called with an empty audience identifier array."
+ "This request tried to save a single share but received multiple records back in response."
+ "Zone-StopShare-Export"
+ "com.apple.coredata.cloudkit.share.stop"
+ "com.apple.coredata.schemagenerator.zone"
+ "managedObjectIDs"
+ "operationID"
+ "options"
+ "savedRecords"
+ "sharedZoneID"
+ "v24@?0@\"CKRecordZoneID\"8@\"NSError\"16"
+ "v24@?0@\"CKShare\"8@\"NSError\"16"
- "-[NSPersistentCloudKitContainer shareManagedObjects:toShare:completion:]"
- "-[NSPersistentCloudKitContainer shareManagedObjects:toShare:completion:]_block_invoke"
```

## photolibraryd

> `/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/Versions/A/Support/photolibraryd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__data`

```diff

 911.0.134.0.0
-  __TEXT.__text: 0x1fc60
-  __TEXT.__auth_stubs: 0x9d0
-  __TEXT.__objc_stubs: 0x57a0
-  __TEXT.__objc_methlist: 0x10dc
+  __TEXT.__text: 0x21e70
+  __TEXT.__auth_stubs: 0xa50
+  __TEXT.__objc_stubs: 0x5e60
+  __TEXT.__objc_methlist: 0x124c
   __TEXT.__dlopen_cstrs: 0xc5
-  __TEXT.__const: 0x168
-  __TEXT.__gcc_except_tab: 0x8f8
-  __TEXT.__objc_classname: 0x781
-  __TEXT.__objc_methname: 0x63ae
-  __TEXT.__objc_methtype: 0xb9f
-  __TEXT.__oslogstring: 0x4188
-  __TEXT.__cstring: 0x1fa2
+  __TEXT.__const: 0x188
+  __TEXT.__gcc_except_tab: 0xa54
+  __TEXT.__objc_classname: 0x7c4
+  __TEXT.__objc_methname: 0x6b12
+  __TEXT.__objc_methtype: 0xc18
+  __TEXT.__oslogstring: 0x45df
+  __TEXT.__cstring: 0x22b5
   __TEXT.metaschema: 0xc000
-  __TEXT.__unwind_info: 0x668
-  __DATA_CONST.__const: 0x1270
-  __DATA_CONST.__cfstring: 0x1040
-  __DATA_CONST.__objc_classlist: 0x178
+  __TEXT.__unwind_info: 0x850
+  __DATA_CONST.__const: 0x1330
+  __DATA_CONST.__cfstring: 0x12a0
+  __DATA_CONST.__objc_classlist: 0x188
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x68
-  __DATA_CONST.__objc_intobj: 0xd8
-  __DATA_CONST.__objc_arraydata: 0x60
-  __DATA_CONST.__objc_arrayobj: 0x48
+  __DATA_CONST.__objc_intobj: 0x108
+  __DATA_CONST.__objc_arraydata: 0x70
+  __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x4f8
-  __DATA_CONST.__got: 0x7a8
-  __DATA.__objc_const: 0x3168
-  __DATA.__objc_selrefs: 0x17f0
-  __DATA.__objc_ivar: 0xa8
-  __DATA.__objc_data: 0xeb0
+  __DATA_CONST.__auth_got: 0x538
+  __DATA_CONST.__got: 0x818
+  __DATA.__objc_const: 0x34c0
+  __DATA.__objc_selrefs: 0x19a0
+  __DATA.__objc_ivar: 0xd4
+  __DATA.__objc_data: 0xf50
   __DATA.__data: 0x420
   __DATA.__bss: 0x51
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 450
-  Symbols:   415
-  CStrings:  1472
+  Functions: 490
+  Symbols:   437
+  CStrings:  1586
 
Symbols:
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_NSManagedObjectID
+ _OBJC_CLASS_$_NSSortDescriptor
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_CLASS_$_PAImageConversionServiceClient
+ _OBJC_CLASS_$_PAMediaConversionServiceResourceURLCollection
+ _OBJC_CLASS_$_PLDiagnostics
+ _OBJC_CLASS_$_PLResourceLocalAvailabilityRequestOptions
+ _PAMediaConversionIsProvenanceProcessingTimeoutError
+ _PAMediaConversionResourceRoleProvenanceUnprocessed
+ _PAMediaConversionServiceErrorDomain
+ _PAMediaConversionServiceJobIdentifierKey
+ _PAMediaConversionServiceOptionIsContentProvenanceDryRunKey
+ _PAMediaConversionServiceOptionRequestReasonKey
+ _PAMediaConversionServiceProvenanceDiagnosticsRequestedKey
+ _PLCoreAnalyticsProvenanceSummaryEvent
+ _dispatch_block_cancel
+ _objc_opt_isKindOfClass
+ _objc_opt_new
+ _objc_setProperty_nonatomic_copy
+ _objc_sync_enter
+ _objc_sync_exit
CStrings:
+ "%K >= %@"
+ "@\"NSManagedObjectID\""
+ "@\"NSProgress\""
+ "@\"NSURL\""
+ "B40@0:8@16@24d32"
+ "B44@0:8@16@24@32B40"
+ "PLProvenanceMaintenanceAsset"
+ "PLProvenanceProcessingMaintenanceTask"
+ "PLProvenanceProcessingMaintenanceTask-%@"
+ "Provenance Maintenance: Asset %{public}@ cancelled; not advancing resume marker"
+ "Provenance Maintenance: Asset fetch failed: %@"
+ "Provenance Maintenance: Cancel requested"
+ "Provenance Maintenance: Download wait timed out for asset %{public}@"
+ "Provenance Maintenance: Downloading resource for asset %{public}@ (dedicatedProvenance=%@)"
+ "Provenance Maintenance: Failed to download resource for asset %{public}@: %@"
+ "Provenance Maintenance: Failed to write TTR resume marker: %@"
+ "Provenance Maintenance: Failed to write last-processed resume marker: %@"
+ "Provenance Maintenance: Library shutting down; stopping loop"
+ "Provenance Maintenance: No assets to process"
+ "Provenance Maintenance: Starting loop with %tu assets"
+ "Provenance Maintenance: Submitting asset %{public}@ (suppressTTR=%@, dedicatedProvenance=%@)"
+ "Provenance Maintenance: TTR filed for asset %{public}@ (outcome=%@); halting maintenance loop"
+ "Provenance Maintenance: Task cancelled; stopping loop"
+ "Provenance Maintenance: Timed out after %.0fs waiting for in-flight work; cancelling"
+ "Provenance Maintenance: Wall-time budget (%.0fs) exceeded; cancelling in-flight work"
+ "Provenance maintenance: CIP server returned diagnosticsRequested=YES for requestID=%@ (assetUUID=%@)."
+ "Provenance maintenance: requestID=%@ timed out after 6 minutes (assetUUID=%@)."
+ "ProvenanceMaintenance.ResumeMarkerForLastAssetWithCompletedServerDiagnosticsTTR"
+ "ProvenanceMaintenance.ResumeMarkerForLastProcessedAsset"
+ "Q60@0:8@16@24@32@40@48B56"
+ "T@\"NSManagedObjectID\",&,N,V_objectID"
+ "T@\"NSManagedObjectID\",&,N,V_resourceObjectID"
+ "T@\"NSString\",C,N,V_uuid"
+ "T@\"NSURL\",&,N,V_url"
+ "TB,N,V_hasDedicatedProvenanceResource"
+ "TB,N,V_suppressTTR"
+ "URIRepresentation"
+ "URLWithString:"
+ "UUID"
+ "UUIDString"
+ "[Provenance] PCC request exceeded 6 minute timeout"
+ "[Provenance] server requested diagnostics"
+ "_advanceResumeMarkersForAssetObjectID:serverDiagnosticsTTRFired:"
+ "_appPrivateData"
+ "_budgetWatchdog"
+ "_buildSourceCollectionForAsset:resourceURL:"
+ "_downloadResourceForAsset:"
+ "_fetchAssets"
+ "_fetchAssetsUsingAppPrivateData:managedObjectContext:"
+ "_fileTTRIfNeededForAsset:jobIdentifier:resourceURL:result:error:suppressTTR:"
+ "_flushPendingResumeMarkers"
+ "_hasDedicatedProvenanceResource"
+ "_inFlightProgress"
+ "_installBudgetWatchdog"
+ "_objectID"
+ "_pendingResumeMarkerForLastAssetWithCompletedServerDiagnosticsTTR"
+ "_pendingResumeMarkerForLastProcessedAsset"
+ "_processAsset:withClient:"
+ "_publishInFlightProgress:andWait:timeoutSeconds:"
+ "_removeBudgetWatchdog"
+ "_resourceObjectID"
+ "_runConversionForAsset:client:resourceURL:suppressTTR:"
+ "_stopped"
+ "_suppressTTR"
+ "_url"
+ "_uuid"
+ "absoluteString"
+ "arrayWithCapacity:"
+ "collectionWithMainResourceURL:"
+ "compare:"
+ "dateCreated"
+ "diagnosticsRequested"
+ "existingObjectWithID:error:"
+ "fileURL"
+ "fileURLWithPath:"
+ "hasDedicatedProvenanceResource"
+ "heic"
+ "isCancelled"
+ "isLocallyAvailable"
+ "libraryStatsCoreAnalyticsProvenanceKey"
+ "makeResourceLocallyAvailableWithOptions:completion:"
+ "managedObjectIDForURIRepresentation:"
+ "persistedOriginalImageResource"
+ "persistedProvenanceResource"
+ "powderState"
+ "predicateWithValue:"
+ "processContentProvenanceForSourceURLCollection:destinationURL:options:completionHandler:"
+ "provenance processing timed out"
+ "provenance-maintenance-%@.%@"
+ "resourceObjectID"
+ "self > %@"
+ "serverDiagnostics"
+ "setFetchLimit:"
+ "setHasDedicatedProvenanceResource:"
+ "setNetworkAccessAllowed:"
+ "setObjectID:"
+ "setResourceObjectID:"
+ "setResourceURL:forRole:"
+ "setSortDescriptors:"
+ "setSuppressTTR:"
+ "setTaskIdentifier:"
+ "setUrl:"
+ "setUuid:"
+ "setValue:forKey:error:"
+ "sortDescriptorWithKey:ascending:"
+ "stringByAppendingPathComponent:"
+ "suppressTTR"
+ "tapToRadarWithTitle:description:radarComponent:isUserInitiated:displayReason:attachments:"
+ "the provenance server requested diagnostics"
+ "timeout"
+ "url"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
+ "v24@?0@\"PAMediaConversionServiceContentProvenanceProcessingResult\"8@\"NSError\"16"
+ "v28@0:8@16B24"
```

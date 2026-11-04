## CoreRoutine

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/Versions/A/CoreRoutine`

```diff

-1123.0.3.0.0
-  __TEXT.__text: 0x6e740
-  __TEXT.__objc_methlist: 0x8474
-  __TEXT.__const: 0x270
-  __TEXT.__oslogstring: 0x3131
-  __TEXT.__cstring: 0x735e
+1123.0.6.0.0
+  __TEXT.__text: 0x7044c
+  __TEXT.__objc_methlist: 0x8714
+  __TEXT.__const: 0x280
+  __TEXT.__oslogstring: 0x316f
+  __TEXT.__cstring: 0x7676
   __TEXT.__gcc_except_tab: 0x38c
-  __TEXT.__unwind_info: 0x23b0
+  __TEXT.__ustring: 0x70
+  __TEXT.__unwind_info: 0x2448
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x550
-  __DATA_CONST.__objc_classlist: 0x498
+  __DATA_CONST.__const: 0x580
+  __DATA_CONST.__objc_classlist: 0x4b0
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x29b8
+  __DATA_CONST.__objc_selrefs: 0x2a50
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x460
+  __DATA_CONST.__objc_superrefs: 0x478
   __DATA_CONST.__objc_arraydata: 0x98
-  __DATA_CONST.__got: 0x518
+  __DATA_CONST.__got: 0x538
   __AUTH_CONST.__const: 0x15a0
-  __AUTH_CONST.__cfstring: 0x5ea0
-  __AUTH_CONST.__objc_const: 0xf0d8
-  __AUTH_CONST.__objc_intobj: 0x120
+  __AUTH_CONST.__cfstring: 0x6180
+  __AUTH_CONST.__objc_const: 0xf528
+  __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xf50
-  __DATA.__objc_ivar: 0x898
+  __AUTH.__objc_data: 0x1040
+  __DATA.__objc_ivar: 0x8b8
   __DATA.__data: 0x2d0
-  __DATA_DIRTY.__objc_ivar: 0x150
+  __DATA_DIRTY.__objc_ivar: 0x158
   __DATA_DIRTY.__objc_data: 0x1ea0
   __DATA_DIRTY.__data: 0x30
   __DATA_DIRTY.__bss: 0x50

   - /System/Library/PrivateFrameworks/GeoServices.framework/Versions/A/GeoServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2974
-  Symbols:   6171
-  CStrings:  1130
+  Functions: 3028
+  Symbols:   6277
+  CStrings:  1155
 
Symbols:
+ +[RTDataIntegrityValidationResult displayNameForOrphanType:]
+ +[RTDataIntegrityValidationResult explanationForOrphanType:]
+ +[RTTripParkingMetrics getHourIDFromTimeID:]
+ +[RTTripParkingMetrics getTimeIDFromDate:]
+ +[RTTripParkingMetrics getWeekdayIDFromTimeID:]
+ +[RTTripParkingMetrics supportsSecureCoding]
+ +[RTTripParkingMetricsEnumerationContext supportsSecureCoding]
+ +[RTTripParkingMetricsEnumerationOptions supportsSecureCoding]
+ -[RTDataIntegrityValidationResult detailedDescriptionWithTriggerReason:]
+ -[RTDataIntegrityValidationResult initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:totalUnexpectedFilesDetected:executionDuration:]
+ -[RTDataIntegrityValidationResult totalUnexpectedFilesDetected]
+ -[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]
+ -[RTTripParkingMetrics .cxx_destruct]
+ -[RTTripParkingMetrics circlingTime]
+ -[RTTripParkingMetrics commuteID]
+ -[RTTripParkingMetrics copyWithZone:]
+ -[RTTripParkingMetrics description]
+ -[RTTripParkingMetrics encodeWithCoder:]
+ -[RTTripParkingMetrics expirationDate]
+ -[RTTripParkingMetrics hash]
+ -[RTTripParkingMetrics initWithCoder:]
+ -[RTTripParkingMetrics initWithCommuteID:timeID:circlingTime:walkingTime:expirationDate:]
+ -[RTTripParkingMetrics isEqual:]
+ -[RTTripParkingMetrics isEqualToTripParkingMetrics:]
+ -[RTTripParkingMetrics timeID]
+ -[RTTripParkingMetrics walkingTime]
+ -[RTTripParkingMetricsEnumerationContext .cxx_destruct]
+ -[RTTripParkingMetricsEnumerationContext copyWithZone:]
+ -[RTTripParkingMetricsEnumerationContext description]
+ -[RTTripParkingMetricsEnumerationContext encodeWithCoder:]
+ -[RTTripParkingMetricsEnumerationContext hash]
+ -[RTTripParkingMetricsEnumerationContext initWithCoder:]
+ -[RTTripParkingMetricsEnumerationContext initWithEnumerationOptions:]
+ -[RTTripParkingMetricsEnumerationContext initWithEnumerationOptions:offset:]
+ -[RTTripParkingMetricsEnumerationContext init]
+ -[RTTripParkingMetricsEnumerationContext isEqual:]
+ -[RTTripParkingMetricsEnumerationContext offset]
+ -[RTTripParkingMetricsEnumerationContext options]
+ -[RTTripParkingMetricsEnumerationOptions .cxx_destruct]
+ -[RTTripParkingMetricsEnumerationOptions batchSize]
+ -[RTTripParkingMetricsEnumerationOptions commuteID]
+ -[RTTripParkingMetricsEnumerationOptions copyWithZone:]
+ -[RTTripParkingMetricsEnumerationOptions description]
+ -[RTTripParkingMetricsEnumerationOptions encodeWithCoder:]
+ -[RTTripParkingMetricsEnumerationOptions hash]
+ -[RTTripParkingMetricsEnumerationOptions initWithCoder:]
+ -[RTTripParkingMetricsEnumerationOptions initWithCommuteID:]
+ -[RTTripParkingMetricsEnumerationOptions init]
+ -[RTTripParkingMetricsEnumerationOptions isEqual:]
+ -[RTTripParkingMetricsEnumerationOptions setBatchSize:]
+ -[RTTripParkingMetricsEnumerationOptions setCommuteID:]
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table208
+ GCC_except_table487
+ GCC_except_table570
+ GCC_except_table576
+ _OBJC_CLASS_$_RTTripParkingMetrics
+ _OBJC_CLASS_$_RTTripParkingMetricsEnumerationContext
+ _OBJC_CLASS_$_RTTripParkingMetricsEnumerationOptions
+ _OBJC_IVAR_$_RTDataIntegrityValidationResult._totalUnexpectedFilesDetected
+ _OBJC_IVAR_$_RTTripParkingMetrics._circlingTime
+ _OBJC_IVAR_$_RTTripParkingMetrics._commuteID
+ _OBJC_IVAR_$_RTTripParkingMetrics._expirationDate
+ _OBJC_IVAR_$_RTTripParkingMetrics._timeID
+ _OBJC_IVAR_$_RTTripParkingMetrics._walkingTime
+ _OBJC_IVAR_$_RTTripParkingMetricsEnumerationContext._offset
+ _OBJC_IVAR_$_RTTripParkingMetricsEnumerationContext._options
+ _OBJC_METACLASS_$_RTTripParkingMetrics
+ _OBJC_METACLASS_$_RTTripParkingMetricsEnumerationContext
+ _OBJC_METACLASS_$_RTTripParkingMetricsEnumerationOptions
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetrics
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetricsEnumerationContext
+ __OBJC_$_CLASS_METHODS_RTTripParkingMetricsEnumerationOptions
+ __OBJC_$_CLASS_PROP_LIST_RTTripParkingMetrics
+ __OBJC_$_CLASS_PROP_LIST_RTTripParkingMetricsEnumerationContext
+ __OBJC_$_INSTANCE_METHODS_RTTripParkingMetrics
+ __OBJC_$_INSTANCE_METHODS_RTTripParkingMetricsEnumerationContext
+ __OBJC_$_INSTANCE_METHODS_RTTripParkingMetricsEnumerationOptions
+ __OBJC_$_INSTANCE_VARIABLES_RTTripParkingMetrics
+ __OBJC_$_INSTANCE_VARIABLES_RTTripParkingMetricsEnumerationContext
+ __OBJC_$_INSTANCE_VARIABLES_RTTripParkingMetricsEnumerationOptions
+ __OBJC_$_PROP_LIST_RTTripParkingMetrics
+ __OBJC_$_PROP_LIST_RTTripParkingMetricsEnumerationContext
+ __OBJC_$_PROP_LIST_RTTripParkingMetricsEnumerationOptions
+ __OBJC_CLASS_PROTOCOLS_$_RTTripParkingMetrics
+ __OBJC_CLASS_PROTOCOLS_$_RTTripParkingMetricsEnumerationContext
+ __OBJC_CLASS_PROTOCOLS_$_RTTripParkingMetricsEnumerationOptions
+ __OBJC_CLASS_RO_$_RTTripParkingMetrics
+ __OBJC_CLASS_RO_$_RTTripParkingMetricsEnumerationContext
+ __OBJC_CLASS_RO_$_RTTripParkingMetricsEnumerationOptions
+ __OBJC_METACLASS_RO_$_RTTripParkingMetrics
+ __OBJC_METACLASS_RO_$_RTTripParkingMetricsEnumerationContext
+ __OBJC_METACLASS_RO_$_RTTripParkingMetricsEnumerationOptions
+ ___63-[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]_block_invoke
+ ___63-[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]_block_invoke_2
+ ___63-[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]_block_invoke_3
+ ___63-[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]_block_invoke_4
+ _kRTTripParkingMetricsTimeIDBucketsPerDay
+ _kRTTripParkingMetricsUnknownDuration
+ _objc_msgSend$allKeys
+ _objc_msgSend$circlingTime
+ _objc_msgSend$displayNameForOrphanType:
+ _objc_msgSend$explanationForOrphanType:
+ _objc_msgSend$fetchTripParkingMetricsWithOptions:reply:
+ _objc_msgSend$initWithCommuteID:timeID:circlingTime:walkingTime:expirationDate:
+ _objc_msgSend$initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:totalUnexpectedFilesDetected:executionDuration:
+ _objc_msgSend$isEqualToTripParkingMetrics:
+ _objc_msgSend$numberWithInt:
+ _objc_msgSend$setCommuteID:
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$timeID
+ _objc_msgSend$totalUnexpectedFilesDetected
+ _objc_msgSend$walkingTime
- -[RTDataIntegrityValidationResult initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:executionDuration:]
- GCC_except_table191
- GCC_except_table192
- GCC_except_table203
- GCC_except_table477
- GCC_except_table565
- GCC_except_table571
- _objc_msgSend$initWithOrphanCountsByType:sampleOrphanedVisitIdentifiers:sampleOrphanedLOIIdentifiers:sampleUnexpectedFileExtensions:executionDuration:
CStrings:
+ "\nSample Orphaned LOI Identifiers (%lu shown):\n"
+ "\nSample Orphaned Visit Identifiers (%lu shown):\n"
+ "\nSample Unexpected Files (%lu shown):\n"
+ "\nUnexpected Files Detected: %lu (cache files with unexpected or missing extensions)\n"
+ "  %@\n"
+ "  • %@: %lu (%@)\n"
+ "-[RTRoutineManager fetchTripParkingMetricsWithOptions:handler:]"
+ "Execution Duration: %.2fs\n\n"
+ "LOI→MapItem"
+ "Locations of Interest with unresolvable mapItem references (MUID)"
+ "Orphan Breakdown:\n"
+ "RTDataIntegrityValidationResult, total, %lu, visitToPlace, %@, visitToMapItem, %@, loiToMapItem, %@, unexpectedFilesDetected, %lu, duration, %.2fs"
+ "RTRoutineManager: invoked fetchTripParkingMetricsWithOptions."
+ "RTTripParkingMetricsEnumerationContext: options=%@, offset=%lu"
+ "RTTripParkingMetricsEnumerationOptions: commuteID=%@, batchSize=%lu"
+ "Unknown orphan type"
+ "Validation Trigger: %@\n"
+ "Visits with incomplete place references"
+ "Visits with unresolvable finerGranularityMapItemIdentifier"
+ "Visit→MapItem"
+ "Visit→Place"
+ "circlingTime"
+ "commuteID,%@,timeID,%d,circlingTime,%f,walkingTime,%f"
+ "timeID"
+ "totalUnexpectedFilesDetected"
+ "walkingTime"
- "RTDataIntegrityValidationResult, total, %lu, visitToPlace, %@, visitToMapItem, %@, loiToMapItem, %@, unexpectedFileExtensions, %@, duration, %.2fs"
```

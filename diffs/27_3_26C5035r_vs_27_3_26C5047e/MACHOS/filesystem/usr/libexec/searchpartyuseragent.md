## searchpartyuseragent

> `/usr/libexec/searchpartyuseragent`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`

```diff

-449.22.9.13.5
-  __TEXT.__text: 0x159a290
-  __TEXT.__auth_stubs: 0x86c0
-  __TEXT.__objc_stubs: 0x6a60
-  __TEXT.__objc_methlist: 0x3c0c
-  __TEXT.__objc_methname: 0x15588
-  __TEXT.__cstring: 0x2b183
-  __TEXT.__objc_classname: 0x45ac
-  __TEXT.__objc_methtype: 0x5666
-  __TEXT.__const: 0x88cf8
-  __TEXT.__oslogstring: 0x45977
-  __TEXT.__swift5_typeref: 0x20170
-  __TEXT.__constg_swiftt: 0x1e624
+449.22.9.13.11
+  __TEXT.__text: 0x15bc53c
+  __TEXT.__auth_stubs: 0x8700
+  __TEXT.__objc_stubs: 0x6ae0
+  __TEXT.__objc_methlist: 0x3c6c
+  __TEXT.__objc_methname: 0x15658
+  __TEXT.__cstring: 0x2bad3
+  __TEXT.__objc_classname: 0x45a6
+  __TEXT.__objc_methtype: 0x56cf
+  __TEXT.__const: 0x8a0a8
+  __TEXT.__oslogstring: 0x45cf4
+  __TEXT.__swift5_typeref: 0x203ea
+  __TEXT.__constg_swiftt: 0x1e85c
   __TEXT.__swift5_builtin: 0x8e8
-  __TEXT.__swift5_reflstr: 0x22030
-  __TEXT.__swift5_fieldmd: 0x22cb4
-  __TEXT.__swift5_assocty: 0x2890
-  __TEXT.__swift5_proto: 0x53d8
-  __TEXT.__swift5_types: 0x1c88
+  __TEXT.__swift5_reflstr: 0x22295
+  __TEXT.__swift5_fieldmd: 0x2302c
+  __TEXT.__swift5_assocty: 0x28f0
+  __TEXT.__swift5_proto: 0x548c
+  __TEXT.__swift5_types: 0x1cc4
   __TEXT.__swift5_protos: 0x2b8
-  __TEXT.__swift5_capture: 0x16dec
-  __TEXT.__swift_as_entry: 0x328c
-  __TEXT.__swift_as_ret: 0x6e90
-  __TEXT.__swift_as_cont: 0xc640
+  __TEXT.__swift5_capture: 0x16f08
+  __TEXT.__swift_as_entry: 0x330c
+  __TEXT.__swift_as_ret: 0x6f30
+  __TEXT.__swift_as_cont: 0xc72c
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_mpenum: 0x998
-  __TEXT.__unwind_info: 0x4d690
-  __TEXT.__eh_frame: 0xdac08
-  __DATA_CONST.__const: 0x65310
+  __TEXT.__unwind_info: 0x4d7a8
+  __TEXT.__eh_frame: 0xdbda4
+  __DATA_CONST.__const: 0x660a0
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_classlist: 0x7d0
   __DATA_CONST.__objc_catlist: 0x10

   __DATA_CONST.__objc_protorefs: 0x198
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__linkguard: 0x15
-  __DATA_CONST.__auth_got: 0x4368
-  __DATA_CONST.__got: 0x3508
-  __DATA_CONST.__auth_ptr: 0x4200
-  __DATA.__objc_const: 0x19150
-  __DATA.__objc_selrefs: 0x3090
+  __DATA_CONST.__auth_got: 0x4388
+  __DATA_CONST.__got: 0x3518
+  __DATA_CONST.__auth_ptr: 0x4228
+  __DATA.__objc_const: 0x19190
+  __DATA.__objc_selrefs: 0x30b0
   __DATA.__objc_ivar: 0x8
   __DATA.__objc_data: 0x33f0
-  __DATA.__data: 0x3ace0
-  __DATA.__bss: 0xa1160
-  __DATA.__common: 0x35f8
+  __DATA.__data: 0x3b120
+  __DATA.__bss: 0xa2800
+  __DATA.__common: 0x36a0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 60032
-  Symbols:   4347
-  CStrings:  12236
+  Functions: 60450
+  Symbols:   4350
+  CStrings:  12299
 
Symbols:
+ _$s11SwiftSQLite2aaoiyAA10ExpressionVySbSgGAF_ADySbGtF
+ _$s11SwiftSQLite2neoiyAA10ExpressionVySbSgGADyxSgG_AGtAA5ValueRzSQ8DatatypeRpzlF
+ _$s11SwiftSQLite2oooiyAA10ExpressionVySbSgGADySbG_AFtF
CStrings:
+ " AND (\"ObservedAdvertisement\".\"extraKeyBits\" & "
+ "\".\"advertisementData\" AND \"ObservedAdvertisement\".\"scanDate\" = \""
+ "\".\"scanDate\" AND \"ObservedAdvertisement\".\"trackingHeader\" IS NOT NULL)"
+ "\"ObservedAdvertisement\".\"isPosh\" = 1 AND \"ObservedAdvertisement\".\"source\" = "
+ "\"ObservedAdvertisement\".\"trackingHeader\" IS NOT NULL"
+ "%{public}s - deleted %{public}ld telemetry readings that only their own deleted tracking row could carry."
+ ") != 0 AND \"ObservedAdvertisement\".\"advId\" NOT IN ("
+ ".firmwareChanged ("
+ "BeaconObservationStore.allObservations(types:)"
+ "BeaconObservationStore.latestObservation(for:)"
+ "BeaconObservationStore.observations(for:types:)"
+ "BeaconObservationStore.observedBeaconIdentifiers"
+ "ClientTrampoline.allObservations(types:) XPC error: %@"
+ "ClientTrampoline.latestObservation(for:) XPC error: %@"
+ "ClientTrampoline.observations(for:types:) XPC error: %@"
+ "ClientTrampoline.observedBeaconIdentifiers XPC error: %@"
+ "ConfigurationCoordinator finderAllowedNetworkValues unusable, kept %{public}d entries from the last good list"
+ "Decimation - done. Keys processed: %ld/%ld, totalInput: %ld, kept: %ld, decimated: %ld, unlocated decimated: %{public}ld, unrelayable readings deleted with their rows: %ld, totalPreserveSet: %ld, finalObservationCount: %ld, complete: %{bool}d, decimationCutoffDate: %{public}s. Duration: %{public}s."
+ "Decimation - key summary: %{private,mask.hash}s, tracking: %{bool}d, input: %ld, preserved: %ld, decimated: %ld, median: %f."
+ "Delete of anonymous observations"
+ "EXISTS (SELECT 1 FROM \"ObservedAdvertisement\" WHERE \"ObservedAdvertisement\".\"advertisementData\" = \""
+ "Error reading latest observation for %{mask.hash}@: %@"
+ "Error reading observed beacon identifiers: %@"
+ "Error reading typed observations for %{mask.hash}@: %@"
+ "Error reading typed observations: %@"
+ "Found queue confirmation %s"
+ "Insert - not stored, a submit already carried this detection."
+ "Not updating system version for record %@, modified at %@ after the observation at %@"
+ "PublishedDetection"
+ "Purge - deleted %{public}ld advertisements with no location, kept %{public}ld direct scanner rows and %{public}ld rows located at publish to locate, and lost %{public}ld more rows located at publish past the locatable range, keeping direct scanner rows since: %{public}s, rows located at publish since: %{public}s."
+ "Purge - deleted %{public}ld telemetry readings older than %{public}s and %{public}ld only their own deleted tracking row could carry, kept %{public}ld of preserved observations, aged out %{public}ld published detections."
+ "Purge of redundant reconciled observations"
+ "Purge with no location"
+ "TelemetrySlotInfo: dropped %{public}ld of %{public}ld entries past the %{public}ld byte value"
+ "_configurationGeneration"
+ "allObservations(types:)"
+ "allObservations(types:) failed: %{public}@"
+ "allObservationsWithTypeRawValues:completion:"
+ "baseline"
+ "beaconPayloadEncoding"
+ "carrier"
+ "dult"
+ "extendedValue"
+ "finderAllowedNetworkValues"
+ "finderAllowedNetworkValues default not usable, the next layer's list applies"
+ "finderAllowedNetworkValues holds no entry this build implements, so no advertisement is stored"
+ "finderAllowedNetworkValues lists a value twice, the next layer's list applies"
+ "finderAllowedNetworkValues not read, the next layer's list applies: %{public}@"
+ "finderAllowedNetworkValuesList"
+ "keyFormat"
+ "latestObservation(for:)"
+ "latestObservation(for:) failed: %{public}@"
+ "latestObservation(for:types:)"
+ "latestObservationWithBeaconIdentifier:typeRawValues:completion:"
+ "not a value the allow list can hold"
+ "observations(for:types:)"
+ "observations(for:types:) failed: %{public}@"
+ "observationsWithBeaconIdentifier:typeRawValues:completion:"
+ "observedBeaconIdentifiers"
+ "observedBeaconIdentifiers failed: %{public}@"
+ "observedBeaconIdentifiers()"
+ "observedBeaconIdentifiersWithCompletion:"
+ "saveProductInfoRecords(infos:beaconUUIDs:requestedFirmwareVersions:taskIdentifier:completion:)"
+ "submitGuidedCategoryStatusEnabled"
+ "trackingAdvertisement"
+ "unimplemented"
+ "unimplemented carrier"
+ "v32@0:8@\"NSArray\"16@?<v@?@\"NSData\"@\"NSError\">24"
+ "v40@0:8@\"NSUUID\"16@\"NSArray\"24@?<v@?@\"NSData\"@\"NSError\">32"
- "Decimation - done. Keys processed: %ld/%ld, totalInput: %ld, kept: %ld, decimated: %ld, unlocated decimated: %{public}ld, totalPreserveSet: %ld, finalObservationCount: %ld, complete: %{bool}d, decimationCutoffDate: %{public}s. Duration: %{public}s."
- "Decimation - key summary: %{private,mask.hash}s, input: %ld, preserved: %ld, decimated: %ld, median: %f."
- "Found queueObservations %s"
- "Purge - deleted %{public}ld advertisements with no location, kept %{public}ld direct scanner rows to locate, keeping direct scanner rows since: %{public}s."
- "Purge - deleted %{public}ld telemetry readings older than %{public}s, kept %{public}ld of preserved observations."
- "saveProductInfoRecords(infos:beaconUUIDs:taskIdentifier:completion:)"
```

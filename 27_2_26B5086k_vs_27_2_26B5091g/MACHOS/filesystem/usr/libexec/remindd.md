## remindd

> `/usr/libexec/remindd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`

```diff

-4076.0.0.0.0
-  __TEXT.__text: 0x81b63c
+4077.0.0.0.0
+  __TEXT.__text: 0x81f050
   __TEXT.__auth_stubs: 0x8600
-  __TEXT.__objc_stubs: 0x1b9e0
-  __TEXT.__objc_methlist: 0xabc8
-  __TEXT.__const: 0x292b8
-  __TEXT.__objc_methname: 0x282f1
+  __TEXT.__objc_stubs: 0x1ba20
+  __TEXT.__objc_methlist: 0xac28
+  __TEXT.__const: 0x29358
+  __TEXT.__objc_methname: 0x28401
   __TEXT.__objc_classname: 0x6316
-  __TEXT.__cstring: 0x18b27
-  __TEXT.__objc_methtype: 0x43b7
+  __TEXT.__cstring: 0x18c17
+  __TEXT.__objc_methtype: 0x43a7
   __TEXT.__gcc_except_tab: 0x211c
-  __TEXT.__oslogstring: 0x60aa0
+  __TEXT.__oslogstring: 0x60fc0
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__swift5_typeref: 0x1435e
+  __TEXT.__swift5_typeref: 0x143e0
   __TEXT.__swift5_fieldmd: 0xa7e8
   __TEXT.__constg_swiftt: 0xd0a4
   __TEXT.__swift5_builtin: 0x3c0
   __TEXT.__swift5_reflstr: 0xc155
   __TEXT.__swift5_assocty: 0x1ee8
-  __TEXT.__swift5_capture: 0x6238
+  __TEXT.__swift5_capture: 0x62c0
   __TEXT.__swift5_protos: 0x2e4
   __TEXT.__swift5_proto: 0x1920
   __TEXT.__swift5_types: 0xb48

   __TEXT.__swift_as_ret: 0x224
   __TEXT.__swift_as_cont: 0x458
   __TEXT.__swift5_mpenum: 0xe0
-  __TEXT.__unwind_info: 0x14160
-  __TEXT.__eh_frame: 0x1fac0
-  __DATA_CONST.__const: 0x261e8
+  __TEXT.__unwind_info: 0x141a0
+  __TEXT.__eh_frame: 0x1fb38
+  __DATA_CONST.__const: 0x26378
   __DATA_CONST.__cfstring: 0x5220
   __DATA_CONST.__objc_classlist: 0xc48
   __DATA_CONST.__objc_catlist: 0x110

   __DATA_CONST.__objc_dictobj: 0x140
   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__auth_got: 0x4310
-  __DATA_CONST.__got: 0x3430
-  __DATA_CONST.__auth_ptr: 0x2868
-  __DATA.__objc_const: 0x1dd98
-  __DATA.__objc_selrefs: 0x7c48
+  __DATA_CONST.__got: 0x3438
+  __DATA_CONST.__auth_ptr: 0x2870
+  __DATA.__objc_const: 0x1ddb0
+  __DATA.__objc_selrefs: 0x7c70
   __DATA.__objc_ivar: 0x490
   __DATA.__objc_data: 0x87d8
-  __DATA.__data: 0x1f0a0
+  __DATA.__data: 0x1f0d0
   __DATA.__objc_stublist: 0x38
   __DATA.__bss: 0x23830
   __DATA.__common: 0xa00

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 22727
-  Symbols:   4141
-  CStrings:  11743
+  Functions: 22757
+  Symbols:   4142
+  CStrings:  11769
 
Symbols:
+ _$s19ReminderKitInternal15REMFeatureFlagsO27ckDeleteZoneAccountRecoveryyA2CmFWC
CStrings:
+ "No CK account persistent store found"
+ "Primary CK store has no URL"
+ "RDGroceryCategorizer: maximumResponseTokens: %ld"
+ "REMReminderStorageCDIngestor:applyDueDateDeltaAlertChanges: Collapsed duplicate existing early alerts {before: %ld, after: %ld, ids: %{public}s}"
+ "ckDeleteZone recovery: account re-initialized successfully"
+ "ckDeleteZone recovery: accountUtils is nil, cannot re-initialize accounts"
+ "ckDeleteZone recovery: cloudContext is nil, skipping server change token reset — data may not re-appear"
+ "ckDeleteZone recovery: resetting all CK server change tokens <rdar://181242487>"
+ "ckDeleteZone recovery: scheduling updateAccountsAndFetchMigrationState <rdar://181242487>"
+ "ckDeleteZone recovery: updateAccountsAndFetchMigrationState failed: %{public}@"
+ "com.apple.RDStoreController.ckDeleteZone.simulate"
+ "recoverAfterSimulatedZoneDeletion:"
+ "recoverAfterSimulatedZoneDeletion: triggerAccountsUpdateAfterZoneDeletion dispatched"
+ "setMetadata:forPersistentStoreOfType:URL:options:error:"
+ "simulateAccountStoreMarkedForDeletion:"
+ "simulateAccountStoreMarkedForDeletion: Marked store at %s — kill remindd to reproduce rdar://181242487"
+ "simulateLocalZoneDeletion"
+ "simulateLocalZoneDeletion: could not fetch primary CK account in simulation context"
+ "simulateLocalZoneDeletion: deleted %ld objects, triggerAccountsUpdateAfterZoneDeletion dispatched"
+ "simulateLocalZoneDeletion: deleting %ld child objects"
+ "simulateLocalZoneDeletion: failed: %@"
+ "simulateLocalZoneDeletion: failed: %s"
+ "simulateLocalZoneDeletion: no primary active CK account found"
+ "simulateLocalZoneDeletionAndRecover:"
+ "triggerAccountsUpdateAfterZoneDeletion"
+ "v24@0:8@?<v@?q@\"NSError\">16"
```

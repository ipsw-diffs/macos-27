## HomeKitBackingStore

> `/System/Library/PrivateFrameworks/HomeKitBackingStore.framework/Versions/A/HomeKitBackingStore`

```diff

-1520.2.7.4.1
-  __TEXT.__text: 0xa8ba0
+1535.0.0.0.2
+  __TEXT.__text: 0xa91b8
   __TEXT.__objc_methlist: 0x54b4
   __TEXT.__const: 0x148
-  __TEXT.__gcc_except_tab: 0x527c
-  __TEXT.__cstring: 0x74d0
-  __TEXT.__oslogstring: 0x1902e
+  __TEXT.__gcc_except_tab: 0x536c
+  __TEXT.__cstring: 0x7505
+  __TEXT.__oslogstring: 0x191c7
   __TEXT.__unwind_info: 0x22f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x2d0
   __DATA_CONST.__objc_arraydata: 0x98
-  __DATA_CONST.__got: 0x590
+  __DATA_CONST.__got: 0x598
   __AUTH_CONST.__const: 0x30f0
-  __AUTH_CONST.__cfstring: 0x45c0
+  __AUTH_CONST.__cfstring: 0x45e0
   __AUTH_CONST.__objc_const: 0xae10
   __AUTH_CONST.__objc_intobj: 0x1e0
   __AUTH_CONST.__objc_arrayobj: 0x60

   - /usr/lib/libz.1.dylib
   Functions: 2202
   Symbols:   5575
-  CStrings:  2410
+  CStrings:  2417
 
Functions:
~ -[HMBLocalZone(Process) _processItemsForBlockRow:error:] : 27548 -> 28620
~ -[HMBLocalSQLQueryTable prepareWithError:] : 6288 -> 6784
~ ___59-[HMBLocalZone(Record_Internal) removeAllRecordsWithError:]_block_invoke : 500 -> 492
CStrings:
+ "CREATE INDEX IF NOT EXISTS rid_%@ ON %@ (_record_id)"
+ "Failed to update schema version to current version %lu: %@"
+ "Unable to create record index %@: %@"
+ "[%{public}@] Dropped output block %lu since no records were staged for it"
+ "[%{public}@] Failed to drop output block %lu: domain=%{public}@ code=%ld"
+ "[%{public}@] Failed to update schema version to current version %lu: %@"
+ "[%{public}@] Unable to clean up rollback block: %@"
+ "[%{public}@] Unable to create record index %@: %@"
+ "[%{public}@] [%{public}@] Dropped output block %lu since no records were staged for it"
+ "[%{public}@] [%{public}@] Failed to drop output block %lu: domain=%{public}@ code=%ld"
+ "[%{public}@] [%{public}@] Unable to clean up rollback block: %@"
+ "[%{public}@] [%{public}@] unable to clean up corrupt block: %@"
+ "[%{public}@] unable to clean up corrupt block: %@"
- "Failed to updated schema version to current version %lu: %@"
- "[%{public}@] Failed to updated schema version to current version %lu: %@"
- "[%{public}@] Unable to cleanup rollback block: %@"
- "[%{public}@] [%{public}@] Unable to cleanup rollback block: %@"
- "[%{public}@] [%{public}@] unable to cleanup corrupt block: %@"
- "[%{public}@] unable to cleanup corrupt block: %@"
```

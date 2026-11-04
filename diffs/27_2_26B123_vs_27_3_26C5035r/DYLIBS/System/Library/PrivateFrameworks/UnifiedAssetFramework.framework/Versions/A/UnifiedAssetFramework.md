## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/Versions/A/UnifiedAssetFramework`

```diff

-3605.17.1.0.0
-  __TEXT.__text: 0x7d768
-  __TEXT.__objc_methlist: 0x3628
+3610.9.1.0.0
+  __TEXT.__text: 0x7de90
+  __TEXT.__objc_methlist: 0x3680
   __TEXT.__const: 0x1a8
   __TEXT.__constg_swiftt: 0x48
   __TEXT.__swift5_typeref: 0x67
   __TEXT.__swift5_reflstr: 0x9
   __TEXT.__swift5_fieldmd: 0x1c
-  __TEXT.__cstring: 0xb733
-  __TEXT.__oslogstring: 0xf3c6
+  __TEXT.__cstring: 0xb79e
+  __TEXT.__oslogstring: 0xf499
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0xe34
-  __TEXT.__unwind_info: 0x1610
+  __TEXT.__unwind_info: 0x1640
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2608
+  __DATA_CONST.__objc_selrefs: 0x2648
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0x128
   __DATA_CONST.__got: 0x598
-  __AUTH_CONST.__const: 0x1d68
-  __AUTH_CONST.__cfstring: 0x53a0
+  __AUTH_CONST.__const: 0x1d98
+  __AUTH_CONST.__cfstring: 0x5500
   __AUTH_CONST.__objc_const: 0x4630
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x1e0

   __AUTH.__objc_data: 0x98
   __DATA.__objc_ivar: 0x320
   __DATA.__data: 0x298
-  __DATA.__bss: 0x38
+  __DATA.__bss: 0x40
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x1018
   __DATA_DIRTY.__data: 0xc8

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1514
-  Symbols:   3745
-  CStrings:  2147
+  Functions: 1523
+  Symbols:   3764
+  CStrings:  2161
 
Symbols:
+ +[UAFSubscriptionStoreManager _reportsDatabaseFailuresInProcess:]
+ +[UAFSubscriptionStoreManager _reportsDatabaseFailures]
+ -[UAFSubscriptionStoreManager _enumerateSubscriptionsByName:user:usingBlock:]
+ -[UAFSubscriptionStoreManager _reportCorruption:]
+ -[UAFSubscriptionStoreManager _reportFailedReset:error:]
+ -[UAFSubscriptionStoreManager _reportFailedWrite:]
+ -[UAFSubscriptionStoreManager _reportFailureToABC:context:]
+ -[UAFSubscriptionStoreManager _reportSkippedRows:]
+ GCC_except_table106
+ GCC_except_table113
+ GCC_except_table119
+ GCC_except_table127
+ GCC_except_table45
+ GCC_except_table49
+ GCC_except_table65
+ GCC_except_table67
+ GCC_except_table88
+ GCC_except_table94
+ GCC_except_table96
+ ___54-[UAFSubscriptionStoreManager _getSubscriptions:user:]_block_invoke
+ ___66-[UAFSubscriptionStoreManager _getSubscriptionsAsDictionary:user:]_block_invoke
+ ___block_descriptor_40_e8_32s_e33_v16?0"UAFAssetSetSubscription"8l
+ _gReportedFailures
+ _objc_msgSend$_enumerateSubscriptionsByName:user:usingBlock:
+ _objc_msgSend$_reportCorruption:
+ _objc_msgSend$_reportFailedReset:error:
+ _objc_msgSend$_reportFailedWrite:
+ _objc_msgSend$_reportFailureToABC:context:
+ _objc_msgSend$_reportSkippedRows:
+ _objc_msgSend$_reportsDatabaseFailures
+ _objc_msgSend$_reportsDatabaseFailuresInProcess:
+ _objc_msgSend$setConnectionCodeSigningRequirement:
- -[UAFSubscriptionStoreManager _getSubscriptionsAsDictionary:subscriptionsFor:]
- GCC_except_table104
- GCC_except_table110
- GCC_except_table112
- GCC_except_table118
- GCC_except_table38
- GCC_except_table42
- GCC_except_table47
- GCC_except_table52
- GCC_except_table58
- GCC_except_table85
- GCC_except_table87
- _objc_msgSend$_getSubscriptionsAsDictionary:subscriptionsFor:
CStrings:
+ "%@ %@"
+ "%@ %ld"
+ "%s Could not enable fullfsync SQLite error: %d (%s, Extended: %d)"
+ "%s Failed to read subscription '%{public}@' for %{public}@"
+ "%s Reading db version from DbVersion table failed SQLite error: %d (%s, Extended: %d)"
+ "%s Skipped %lu rows of Subscriptions that don't read while reading all subscriptions"
+ "-[UAFSubscriptionStoreManager _enumerateSubscriptionsByName:user:usingBlock:]"
+ "-[UAFSubscriptionStoreManager _reportSkippedRows:]"
+ "PRAGMA fullfsync = ON"
+ "SELECT k1 FROM Subscriptions WHERE k0 = ? AND k4 = ?"
+ "Subscriptions:%lu"
+ "assetsubscriptiond"
+ "corruption"
+ "move"
+ "open"
+ "prepare"
+ "reset"
+ "reset failed"
+ "skipped rows"
+ "v16@?0@\"UAFAssetSetSubscription\"8"
- "%s Failed to read subscription: %s"
- "%s Reading db version from DbVersion table failed"
- "-[UAFSubscriptionStoreManager _getAllSubscriptions:]"
- "-[UAFSubscriptionStoreManager _getAllSubscriptionsFlat:]"
- "-[UAFSubscriptionStoreManager _getSubscriptionsAsDictionary:subscriptionsFor:]"
- "SELECT k2 FROM Subscriptions WHERE k0 = ? AND k4 = ?"
```

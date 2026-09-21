## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/Versions/A/SpotlightIndex`

```diff

-2465.1.2.0.0
-  __TEXT.__text: 0x4df494
+2465.1.3.0.0
+  __TEXT.__text: 0x4de5fc
   __TEXT.__objc_methlist: 0x404
   __TEXT.__const: 0xacf2
-  __TEXT.__cstring: 0x3eaf8
+  __TEXT.__cstring: 0x3ec81
   __TEXT.__gcc_except_tab: 0x27c
-  __TEXT.__oslogstring: 0x1f0f0
+  __TEXT.__oslogstring: 0x1f141
   __TEXT.__ustring: 0x400
   __TEXT.__dof_mds: 0x29b
-  __TEXT.__unwind_info: 0x7688
+  __TEXT.__unwind_info: 0x7698
   __TEXT.__eh_frame: 0x220
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x78
   __DATA_CONST.__got: 0x608
   __AUTH_CONST.__const: 0xd3d8
-  __AUTH_CONST.__cfstring: 0x12ce0
+  __AUTH_CONST.__cfstring: 0x12d00
   __AUTH_CONST.__objc_const: 0x5e8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x18

   __AUTH.__data: 0x18d8
   __DATA.__objc_ivar: 0x60
   __DATA.__data: 0xe08
-  __DATA.__bss: 0x57b8
+  __DATA.__bss: 0x5758
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x5a4
-  __DATA_DIRTY.__bss: 0x1a088
+  __DATA_DIRTY.__bss: 0x1a0e8
   __DATA_DIRTY.__common: 0x24030
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8104
-  Symbols:   10921
-  CStrings:  9582
+  Functions: 8108
+  Symbols:   10925
+  CStrings:  9600
 
Symbols:
+ GCC_except_table246
+ GCC_except_table255
+ GCC_except_table3907
+ GCC_except_table3912
+ GCC_except_table5329
+ GCC_except_table5332
+ GCC_except_table7082
+ __ZN19PartialQueryResults21cannedAttributeVectorEv
+ __ZN19PartialQueryResults28cannedCollectAttributeVectorEv
+ __ZN19PartialQueryResults29cannedRequiredAttributeVectorEv
+ __si_finish_property_write
+ __si_set_property_locked
+ __si_write_property_data
- GCC_except_table248
- GCC_except_table257
- GCC_except_table3909
- GCC_except_table3914
- GCC_except_table5336
- GCC_except_table5339
- GCC_except_table7086
- __ZN19PartialQueryResults16_attributeVectorEv
- __ZN19PartialQueryResults34setupCannedRequiredAttributeVectorEPPKcPPPFS2_P4__SIE
CStrings:
+ "%s:%d: <si:%s> - Failed to mark the store dirty after a property write, rc:%d"
+ "2465.1.3"
+ "<si:%s> - Failed to mark the store dirty after a property write, rc:%d"
+ "<si:%s> - Suspending preheat scheduler for %p (%s)"
+ "_attributeVector"
+ "_completionAttributeVector"
+ "_si_finish_property_write"
+ "_si_write_property_data"
+ "computeFlags"
+ "container_table_check"
+ "count < (CFIndex)UINT32_MAX && count >= 0"
+ "evaluateFuzzyQueryForIndex_block_invoke"
+ "kr == KERN_SUCCESS"
+ "oidArray"
+ "oidVector"
+ "ownOidArray"
+ "prepare"
+ "processPrefix"
+ "setOneFieldLocked"
+ "setupFieldIdVector"
+ "si_querypipe_addresults"
+ "suspendOthers"
+ "v40@?0^{__SI=Q{SIFileOps=^?^?^?}{SIGuardedFd=iQ}isII^{SIWatchDog}^{__CFDictionary}{_opaque_pthread_rwlock_t=q[192c]}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{os_unfair_lock_s=I}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}^{__CFDictionary}^{_MDPlistContainer}Bi[18^{si_scheduler_token_s}]iI[4^{dispatch_semaphore_s}]{?=[18^{_si_work_scheduler}][20^{_si_workqueue}]^{si_workqueue_list_s}}^{dispatch_queue_s}^{datastore_info}{CIMetaInfo=i^{fd_obj}iQIIIIIIIIqqiiBI}^{DocStore}QQ{_opaque_pthread_mutex_t=q[56c]}^{ContentIndexList}^{ContentIndexList}iII^{_SI_PersistentIDStore}{__SIStoreToken={?=CCCCCCCCCCCCCCCC}^{__CFUUID}}ACAII{os_unfair_lock_s=I}diI^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{os_unfair_lock_s=I}^{__CFBag}{_opaque_pthread_mutex_t=q[56c]}^{__CFSet}^{__CFDictionary}Q^{__CFBag}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_cond_t=q[40c]}iIIIIIIIIIIIIIIIIIIIIBBBAq^{__CFDictionary}^{__CFBitVector}^{__CFDictionary}^{__CFArray}^{si_mobile_journal}^{si_mobile_journal}^{si_mobile_journal}AqAqAq^{dispatch_source_s}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}^{__CFArray}Cd^?^vdd{?=^{fd_obj}IIIq{os_unfair_lock_s=I}BB^vQQQQAB}III^{FinderDateFields}{_opaque_pthread_mutex_t=q[56c]}^{fd_obj}^{fd_obj}^{fd_obj}iii^{_SIIndexCallbacks}^{__CFArray}^{__CFArray}qqqQIIiiBBBBBBBABB^{si_scheduler_token_s}BBBBBBQq[4096c]{os_unfair_lock_s=I}{os_unfair_lock_s=I}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b2b1b1^i^{__CFSet}^{__CFDictionary}^{__SIUINT64Set}^{ReverseDirStore_s}^{FileTree_Overlay_s}^{__CFSet}^{TermUpdateSet}{_opaque_pthread_rwlock_t=q[192c]}[16C]Bi^{datastore_info}AIBB[5i]*iI^vB^{fd_obj}iiii{AccumulatedCounts_s={_opaque_pthread_mutex_t=q[56c]}[256q][256I][256I]}BB^{SIAllMeInfo}{os_unfair_lock_s=I}^{si_analytics_s}}8^{_xpc_activity_s=}16^B24^{dispatch_group_s=}32"
- "2465.1.2"
- "<si:%s> - Suspending root scheduler for %p (%s)"
- "_si_store_property_cache"
- "count < (CFIndex)4294967295U && count >= 0"
- "v40@?0^{__SI=Q{SIFileOps=^?^?^?}{SIGuardedFd=iQ}isII^{SIWatchDog}^{__CFDictionary}{_opaque_pthread_rwlock_t=q[192c]}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{os_unfair_lock_s=I}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}^{__CFDictionary}^{_MDPlistContainer}Bi[18^{si_scheduler_token_s}]iI[4^{dispatch_semaphore_s}]{?=[18^{_si_work_scheduler}][20^{_si_workqueue}]^{si_workqueue_list_s}}^{dispatch_queue_s}^{datastore_info}{CIMetaInfo=i^{fd_obj}iQIIIIIIIIqqiiBI}^{DocStore}QQ{_opaque_pthread_mutex_t=q[56c]}^{ContentIndexList}^{ContentIndexList}iII^{_SI_PersistentIDStore}{__SIStoreToken={?=CCCCCCCCCCCCCCCC}^{__CFUUID}}ACAII{os_unfair_lock_s=I}diI^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{os_unfair_lock_s=I}^{__CFBag}{_opaque_pthread_mutex_t=q[56c]}^{__CFSet}^{__CFDictionary}Q^{__CFBag}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_cond_t=q[40c]}iIIIIIIIIIIIIIIIIIIIIBBBAq^{__CFDictionary}^{__CFBitVector}^{__CFDictionary}^{__CFArray}^{si_mobile_journal}^{si_mobile_journal}^{si_mobile_journal}AqAqAq^{dispatch_source_s}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}^{__CFArray}Cd^?^vdd{?=^{fd_obj}IIIq{os_unfair_lock_s=I}BB^vQQQQAB}III^{FinderDateFields}{_opaque_pthread_mutex_t=q[56c]}^{fd_obj}^{fd_obj}^{fd_obj}iii^{_SIIndexCallbacks}^{__CFArray}^{__CFArray}qqqQIIiiBBBBBBBABB^{si_scheduler_token_s}BBBBBBQq[4096c]{os_unfair_lock_s=I}{os_unfair_lock_s=I}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b2b1b1^i^{__CFSet}^{__CFDictionary}^{__SIUINT64Set}^{ReverseDirStore_s}^{FileTree_Overlay_s}^{__CFSet}^{TermUpdateSet}{_opaque_pthread_rwlock_t=q[192c]}[16C]Bi^{datastore_info}AIBB[5i]*iI^vB^{fd_obj}iiii{AccumulatedCounts_s={_opaque_pthread_mutex_t=q[56c]}[256q][256I][256I]}BB^{SIAllMeInfo}{os_unfair_lock_s=I}^{si_analytics_s}}8^{_xpc_activity_s=}16^B24^{dispatch_group_s=}32"
```

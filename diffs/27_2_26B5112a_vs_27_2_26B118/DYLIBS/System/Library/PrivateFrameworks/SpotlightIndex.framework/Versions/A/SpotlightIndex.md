## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/Versions/A/SpotlightIndex`

```diff

 2465.1.9.0.0
-  __TEXT.__text: 0x4df3b8
+  __TEXT.__text: 0x4e10b0
   __TEXT.__objc_methlist: 0x404
   __TEXT.__const: 0xacf2
-  __TEXT.__cstring: 0x3f0ec
+  __TEXT.__cstring: 0x3f117
   __TEXT.__gcc_except_tab: 0x27c
-  __TEXT.__oslogstring: 0x1f551
+  __TEXT.__oslogstring: 0x1f8e9
   __TEXT.__ustring: 0x400
   __TEXT.__dof_mds: 0x29b
-  __TEXT.__unwind_info: 0x76a0
+  __TEXT.__unwind_info: 0x76d8
   __TEXT.__eh_frame: 0x220
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6b38
+  __DATA_CONST.__const: 0x6b68
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x698

   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2020
+  __AUTH_CONST.__auth_got: 0x2028
   __AUTH.__objc_data: 0xa0
   __AUTH.__data: 0x18d8
   __DATA.__objc_ivar: 0x60
   __DATA.__data: 0xe08
-  __DATA.__bss: 0x5778
+  __DATA.__bss: 0x5768
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x5a4
-  __DATA_DIRTY.__bss: 0x1a0e8
+  __DATA_DIRTY.__bss: 0x1a138
   __DATA_DIRTY.__common: 0x24030
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8111
-  Symbols:   10931
-  CStrings:  9629
+  Functions: 8121
+  Symbols:   10946
+  CStrings:  9649
 
Symbols:
+ GCC_except_table3917
+ GCC_except_table3922
+ GCC_except_table5339
+ GCC_except_table5342
+ GCC_except_table7095
+ __sdb_cache_check_fault
+ __tus_check_fault
+ __tus_protect
+ __tus_unprotect
+ __wrcache_arm_slot
+ __wrcache_free_page
+ _arc4random_uniform
+ _db_cache_call_with_entry
+ _db_cache_dealloc
+ _db_cache_protect_entry
+ _db_cache_unprotect_entry
+ _s_mprotect_registry
+ _s_mprotect_registry_capacity
+ _s_mprotect_registry_count
+ _s_mprotect_registry_lock
- GCC_except_table3907
- GCC_except_table3912
- GCC_except_table5329
- GCC_except_table5332
- GCC_except_table7085
CStrings:
+ "???"
+ "ARM"
+ "DISARM"
+ "FREE"
+ "NONE"
+ "PROTECT"
+ "SDB cache %p slot %d op[oldest+%d]: %{public}s dbp=%p"
+ "SDB cache %p slot %d: dbp=%p guarded=%d eligible=%d sz=%zu pgnum=0x%x"
+ "TUS kMDSTagUpdateSetPositionInfo guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetPositionTable guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetPostings guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetTerms (dataAllocator) guard fault: addr=%p slab=%p size=%zu"
+ "TUS kMDSTagUpdateSetTerms (termSlab) guard fault: addr=%p slab=%p size=%zu"
+ "UNPROTECT"
+ "Write cache %p: page lost mprotect eligibility after resize (new_ptr=%p, aligned=%d, dbp_sz=%d, page_sz=%zu)"
+ "Write cache %p: slot %d page %p armed for mprotect guard"
+ "Write cache %p: slot %d page %p freed (was guarded, sz=%zu)"
+ "Write cache %p: slot %d page changed from %p to %p after flush — clearing stale mprotect guard"
+ "mprotect failed: ptr=%p sz=%zu prot=%d errno=%d"
+ "mprotect guard fault at %p: could not acquire registry lock"
```

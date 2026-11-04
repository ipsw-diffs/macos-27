## libsystem_malloc.dylib

> `/usr/lib/system/libsystem_malloc.dylib`

```diff

-886.41.1.0.0
-  __TEXT.__text: 0x46368
+886.60.5.0.0
+  __TEXT.__text: 0x46048
   __TEXT.__const: 0x6ff
-  __TEXT.__cstring: 0xbb21
+  __TEXT.__cstring: 0xb959
   __TEXT.__dof_magmalloc: 0xa96
-  __TEXT.__unwind_info: 0xba0
+  __TEXT.__unwind_info: 0xb98
   __TEXT.__eh_frame: 0x48
   __TEXT.__auth_stubs: 0x7b0
   __DATA_CONST.__const: 0xa28

   - /usr/lib/system/libsystem_kernel.dylib
   - /usr/lib/system/libsystem_platform.dylib
   - /usr/lib/system/libsystem_pthread.dylib
-  Functions: 982
-  Symbols:   1153
-  CStrings:  1018
+  Functions: 980
+  Symbols:   1156
+  CStrings:  1017
 
Symbols:
+ ___mfm_unlock
+ __xzm_fatal_pointer_was_not_allocated
+ _malloc_fatal_pointer_was_not_allocated
+ _memtag_validate_ptr
+ _mfm_validate_tag
- __xzm_free_abort
- _memtag_handle_mismatch
CStrings:
+ "*** error for object %p: %s\n"
+ "BUG IN CLIENT OF LIBMALLOC: pointer being freed is invalid or has mismatching MTE tag (probable double-free)"
+ "BUG IN LIBMALLOC: malloc assertion \"!chunk->xzc_bits.xzcb_preallocated\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7534)"
+ "BUG IN LIBMALLOC: malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:8314)"
+ "BUG IN LIBMALLOC: malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7858)"
+ "BUG IN LIBMALLOC: malloc assertion \"gxz.xz\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7750)"
+ "BUG IN LIBMALLOC: malloc assertion \"prev_slot_value == slot_meta.xasa_value\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2604)"
+ "BUG IN LIBMALLOC: malloc assertion \"retries < 10\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7594)"
+ "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2217)"
+ "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:5346)"
+ "MFM double free"
+ "free to already-freed small chunk (likely double-free)"
+ "free to empty or invalid freelist chunk (likely double-free)"
+ "invalid MFM address"
+ "invalid pointer tag (likely double-free)"
+ "not an allocated MFM block"
+ "pointer being freed was not allocated"
- "*** error for object %p: pointer being freed was not allocated\n"
- "BUG IN CLIENT OF LIBMALLOC: MTE tag mismatch (probable double-free)"
- "BUG IN CLIENT OF LIBMALLOC: double free detected"
- "BUG IN CLIENT OF LIBMALLOC: free to empty or invalid chunk detected (likely double-free)"
- "BUG IN CLIENT OF LIBMALLOC: ignored previous invalid free due to MTE tag mismatch in soft mode (probable double-free)"
- "BUG IN CLIENT OF LIBMALLOC: invalid address"
- "BUG IN CLIENT OF LIBMALLOC: not an allocated block"
- "BUG IN CLIENT OF LIBMALLOC: pointer being freed was not allocated"
- "BUG IN CLIENT OF LIBMALLOC: pointer being freed was not valid"
- "BUG IN LIBMALLOC: malloc assertion \"!chunk->xzc_bits.xzcb_preallocated\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7548)"
- "BUG IN LIBMALLOC: malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:8331)"
- "BUG IN LIBMALLOC: malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7872)"
- "BUG IN LIBMALLOC: malloc assertion \"gxz.xz\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7764)"
- "BUG IN LIBMALLOC: malloc assertion \"old_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:6854)"
- "BUG IN LIBMALLOC: malloc assertion \"prev_slot_value == slot_meta.xasa_value\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2603)"
- "BUG IN LIBMALLOC: malloc assertion \"retries < 10\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:7608)"
- "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:2216)"
- "BUG IN LIBMALLOC: malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc/src/xzone_malloc/xzone_malloc.c:5356)"
```

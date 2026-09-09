## libgmalloc.dylib

> `/usr/lib/libgmalloc.dylib`

### Sections with Same Size but Changed Content

- `__AUTH_CONST.__interpose`
- `__DATA.__data`

```diff

 64578.57.1.0.0
-  __TEXT.__text: 0x27b4
+  __TEXT.__text: 0x26cc
   __TEXT.__auth_stubs: 0x360
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x1308
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__auth_got: 0x1b0
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ _GuardMalloc_noteAllocation : 288 -> 276
~ _GuardMalloc_printZone : 448 -> 436
~ _GuardMalloc_statistics : 196 -> 184
~ _GuardMalloc_enumerator : 776 -> 788
~ _GMmprotect : 232 -> 220
~ _GMmalloc_set_zone_name : 248 -> 204
~ _GMmalloc : 64 -> 52
~ _GMfree : 124 -> 112
~ _GMrealloc : 124 -> 112
~ _GMcalloc : 72 -> 60
~ _GMvalloc : 64 -> 52
~ _GMmalloc_good_size : 56 -> 44
~ _GMposix_memalign : 88 -> 76
~ _GM_malloc_fork_prepare : 48 -> 36
~ _GM_malloc_fork_parent : 48 -> 36
~ _malloc_printf_va : 208 -> 196
~ _GuardMalloc_free : 100 -> 88
~ _GuardMalloc_realloc : 300 -> 284
~ _GuardMalloc_memalign : 44 -> 40
```

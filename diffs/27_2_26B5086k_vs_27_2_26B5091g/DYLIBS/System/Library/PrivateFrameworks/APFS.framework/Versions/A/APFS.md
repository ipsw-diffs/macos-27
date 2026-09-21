## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/Versions/A/APFS`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x56e94
+3288.40.14.0.0
+  __TEXT.__text: 0x56fac
   __TEXT.__const: 0x8540
   __TEXT.__cstring: 0xeb50
   __TEXT.__oslogstring: 0x1467

   __AUTH_CONST.__cfstring: 0x1520
   __AUTH_CONST.__weak_auth_got: 0x8
   __AUTH_CONST.__auth_got: 0x688
-  __AUTH.__data: 0x148
-  __DATA.__data: 0x9c
+  __DATA.__data: 0xc
   __DATA.__bss: 0x48
   __DATA.__common: 0x420
+  __DATA_DIRTY.__data: 0x1d8
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
Functions:
~ _spaceman_chunk_zone_info_init : 68 -> 84
~ _spaceman_iterate_process_bitmap_block : 1028 -> 1040
~ _spaceman_iterate_free_extents_internal : 3784 -> 3844
~ _spaceman_alloc_iterate_chunks : 3456 -> 3500
~ _spaceman_modify_bits : 3588 -> 3712
~ _jobj_validate_key_val : 572 -> 596
CStrings:
+ "3288.40.14"
- "3288.40.13"
```

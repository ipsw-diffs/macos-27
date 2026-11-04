## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/Versions/A/APFS`

```diff

-3288.41.1.0.0
-  __TEXT.__text: 0x56f8c
+3288.60.7.0.0
+  __TEXT.__text: 0x56fe4
   __TEXT.__const: 0x8540
-  __TEXT.__cstring: 0xeb4f
+  __TEXT.__cstring: 0xeba1
   __TEXT.__oslogstring: 0x1467
   __TEXT.__gcc_except_tab: 0x1c
   __TEXT.__unwind_info: 0xda0

   - /usr/lib/libutil.dylib
   Functions: 932
   Symbols:   1151
-  CStrings:  1452
+  CStrings:  1453
 
Functions:
~ _btree_node_child_id_update_cb : 32 -> 36
~ _spaceman_iterate_free_extents_internal : 3844 -> 3928
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "3288.60.7"
- "3288.41.1"
```

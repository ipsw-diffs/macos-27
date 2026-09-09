## search

> `/System/Library/OpenDirectory/Modules/search.bundle/Contents/MacOS/search`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 1003.0.1.0.0
-  __TEXT.__text: 0x481c
+  __TEXT.__text: 0x46d8
   __TEXT.__auth_stubs: 0x680
   __TEXT.__const: 0x90
   __TEXT.__oslogstring: 0x62b
   __TEXT.__cstring: 0x3794
-  __TEXT.__unwind_info: 0x160
+  __TEXT.__unwind_info: 0x1f0
   __DATA_CONST.__const: 0x600
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__auth_got: 0x340

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /usr/lib/libSystem.B.dylib
-  Functions: 104
+  Functions: 103
   Symbols:   251
   CStrings:  73
 
Functions:
~ __copy_nodelist : 132 -> 120
~ __add_to_list : 104 -> 92
~ ___odm_NodeCopySupportedRecordTypes_block_invoke_2 : 112 -> 100
~ ___odm_NodeCopySupportedAttributes_block_invoke_2 : 112 -> 100
~ __append_path : 104 -> 92
~ __free_req_state : 80 -> 68
~ ___odm_QueryCreateWithNode_block_invoke : 184 -> 172
~ __forward_query_cancel : 240 -> 228
~ ___copy_helper_block_8_32b40b48b56r : 112 -> 100
~ ___destroy_helper_block_8_32b40b48b56r : 92 -> 80
~ _odm_initialize : 224 -> 212
~ __dealloc_search_context : 80 -> 68
~ ___odm_configuration_loaded_block_invoke_2 : 80 -> 68
~ __copy_policy_paths : 140 -> 128
~ ____wait_for_startup_nodes_block_invoke : 208 -> 196
~ __wait_for_nodes : 796 -> 792
~ ___copy_helper_block_8_32b40b : 80 -> 68
~ ___destroy_helper_block_8_32b40b : 68 -> 56
~ ____publish_path_block_invoke : 208 -> 196
~ ____publish_store_block_invoke : 148 -> 136
~ ____notify_online_block_invoke : 132 -> 120
~ ____notify_offline_block_invoke : 136 -> 124
~ ____enable_notifications_block_invoke : 108 -> 96
~ ____enable_notifications_block_invoke_2 : 108 -> 96
- _OUTLINED_FUNCTION_1
~ _OUTLINED_FUNCTION_4 : 28 -> 16
```

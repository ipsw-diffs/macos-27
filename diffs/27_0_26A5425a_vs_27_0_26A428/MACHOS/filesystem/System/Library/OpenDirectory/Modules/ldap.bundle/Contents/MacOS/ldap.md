## ldap

> `/System/Library/OpenDirectory/Modules/ldap.bundle/Contents/MacOS/ldap`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 1003.0.1.0.0
-  __TEXT.__text: 0xd728
+  __TEXT.__text: 0xd60c
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__const: 0x110
   __TEXT.__oslogstring: 0x1196
   __TEXT.__cstring: 0xc0b
-  __TEXT.__unwind_info: 0x210
+  __TEXT.__unwind_info: 0x378
   __DATA_CONST.__const: 0x920
   __DATA_CONST.__cfstring: 0xa40
   __DATA_CONST.__auth_got: 0x6e0
Functions:
~ ___odm_NodeCreateRecord_block_invoke : 120 -> 108
~ __server_discovery : 660 -> 648
~ __odm_QueryCreateWithNode_block_invoke.40 : 108 -> 96
~ __complete_msg_ctx : 88 -> 76
~ _odm_locate_service : 3536 -> 3556
~ _odm_configuration_loaded : 196 -> 184
~ __ldap_context_dealloc : 252 -> 240
~ ___odm_create_connection_with_options_block_invoke_2 : 60 -> 48
~ __update_context_from_options : 548 -> 536
~ ___translate_recordtype_block_invoke : 100 -> 88
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ __escaped_rdn_copy : 480 -> 472
~ ____bervals_from_array_block_invoke : 472 -> 460
~ __msg_ctx_dealloc : 592 -> 580
~ ____server_discovery_block_invoke : 204 -> 192
~ ____query_create_searchFilter_block_invoke : 156 -> 144
~ ____build_filter_with_predicate_block_invoke : 308 -> 296
~ __escaped_value_copy : 648 -> 640
~ ____query_automount_byname_block_invoke : 288 -> 276
~ ____query_automount_byname_block_invoke_3 : 116 -> 104
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ __respond_with_error : 1268 -> 1244
~ ____close_ldap_block_invoke_2 : 68 -> 56
~ _OUTLINED_FUNCTION_9 : 32 -> 20
```

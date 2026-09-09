## SystemCache

> `/System/Library/OpenDirectory/Modules/SystemCache.bundle/Contents/MacOS/SystemCache`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1003.0.1.0.0
-  __TEXT.__text: 0x2e36c
+  __TEXT.__text: 0x2ddb8
   __TEXT.__auth_stubs: 0x1330
   __TEXT.__const: 0x208
   __TEXT.__cstring: 0x7e7c
   __TEXT.__oslogstring: 0x39e4
-  __TEXT.__unwind_info: 0x928
+  __TEXT.__unwind_info: 0xd08
   __DATA_CONST.__const: 0x4cd0
   __DATA_CONST.__cfstring: 0x49c0
   __DATA_CONST.__auth_got: 0x998

   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
-  Functions: 884
+  Functions: 883
   Symbols:   1780
   CStrings:  1219
 
Functions:
~ ___fixup_schema3 : 88 -> 76
~ ___mbr_cache_copy_statistics_block_invoke : 188 -> 176
~ ___mbr_cache_dump_block_invoke_2 : 236 -> 224
~ ___mbr_cache_dump_state_block_invoke_2 : 244 -> 232
~ ___mbr_cache_fetch_entry_block_invoke_2 : 124 -> 112
~ ___mbr_cache_flush_block_invoke : 52 -> 40
~ ___mbr_cache_nfsv4_change_occurred_block_invoke : 84 -> 72
~ ___mbr_cache_reset_statistics_block_invoke : 80 -> 68
~ _mbr_cache_statistics_query_total : 68 -> 56
~ _mbr_cache_statistics_groupmembersquery : 68 -> 56
~ _mbr_cache_statistics_groupmembershipquery : 68 -> 56
~ _mbr_cache_statistics_nestedgroupquery : 68 -> 56
~ _mbr_cache_statistics_translate : 88 -> 76
~ _mbr_cache_statistics_membership : 96 -> 84
~ _mbr_cache_statistics_getgrouplist : 80 -> 68
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ ___copy_helper_block_8_32b40b : 80 -> 68
~ ___destroy_helper_block_8_32b40b : 68 -> 56
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ _OUTLINED_FUNCTION_4 : 32 -> 24
~ _OUTLINED_FUNCTION_5 : 24 -> 20
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _mbr_entry_release : 108 -> 96
~ _mbr_entry_free : 320 -> 308
~ ___mbr_entry_add_to_cache_block_invoke_2 : 664 -> 652
~ ___mbr_entry_dump_block_invoke_2 : 152 -> 140
~ ___mbr_entry_dump_state_block_invoke_2 : 232 -> 220
~ ___copy_helper_block_8_32b40r : 80 -> 68
~ ___destroy_helper_block_8_32b40r : 68 -> 56
~ _mbr_entry_set_libinfo_user_attribs : 88 -> 76
~ _mbr_entry_set_libinfo_group_attribs : 64 -> 52
~ ___mbr_handle_getpwent_block_invoke_2 : 268 -> 256
~ ___mbr_handle_getgrent_block_invoke_3 : 268 -> 256
~ ____mbr_zone_block_invoke : 64 -> 52
~ ____mbr_entry_initialize_block_invoke : 92 -> 80
~ ____mbr_entry_parse_libinfo_user_block_invoke : 200 -> 188
~ ___copy_helper_block_8_32r40r48r56r64r72r80r : 160 -> 148
~ ___destroy_helper_block_8_32r40r48r56r64r72r80r : 128 -> 116
~ ____refresh_if_necessary_async_wait_block_invoke : 60 -> 48
~ ____initiate_refresh_if_necessary_block_invoke : 492 -> 468
~ __dump_refresh_flag : 112 -> 100
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ __mbr_entry_retain_cf : 60 -> 48
~ __mbr_entry_release_cf : 60 -> 48
~ ____mbr_entry_purge_groups_after_query_block_invoke : 72 -> 60
~ ___mbr_entry_refresh_nested_memberships_block_invoke.378 : 348 -> 336
~ __bfs_finalizer : 148 -> 136
~ __mbr_entry_is_in_table : 96 -> 84
~ ____refresh_if_necessary_async_block_invoke : 76 -> 64
~ _OUTLINED_FUNCTION_10 : 28 -> 16
~ _OUTLINED_FUNCTION_11 : 32 -> 20
~ _OUTLINED_FUNCTION_12 : 32 -> 20
~ __rbt_compare_nodes : 100 -> 88
~ __rbt_compare_key : 108 -> 96
~ ___mbr_hashtable_create_block_invoke : 64 -> 52
~ _mbr_hashtable_destroy : 84 -> 72
~ _____mbr_hashtable_flush_block_invoke : 80 -> 68
~ _mbr_lookup_copy_search_node_with_notify : 108 -> 96
~ ___mbr_lookup_copy_skipped_nodes_block_invoke : 208 -> 196
~ ___mbr_lookup_idtype_block_invoke_2 : 236 -> 224
~ ____mbr_query_node_block_invoke : 628 -> 616
~ ___mbr_lookup_create_from_result_block_invoke.28 : 276 -> 264
~ __mbr_lookup_get_string_from_dict_key : 108 -> 96
~ ____mbr_lookup_copyNFSv4Domain_block_invoke_3 : 204 -> 192
~ ____mbr_lookup_sidcache_queue_block_invoke_2 : 96 -> 84
~ ____mbr_lookup_copyNetBIOSName_block_invoke : 240 -> 228
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ ___perf_free_report_collection_block_invoke : 100 -> 88
~ _counter_advance_report : 192 -> 180
~ ___perf_set_event_block_invoke : 184 -> 172
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ _OUTLINED_FUNCTION_7 : 28 -> 16
~ _register_libinfo_types : 1072 -> 1060
~ _libinfo_flushcache : 76 -> 64
~ ___libinfo_dump_block_invoke_2 : 168 -> 156
~ _cache_dump : 208 -> 196
~ _passwd_for_root : 84 -> 72
~ __mbr_cache_lookup : 1160 -> 1148
~ __process_get_id : 200 -> 188
~ _libinfo_cache_add : 928 -> 916
~ _find_and_respond : 116 -> 92
~ ___all_caches_queue_block_invoke : 256 -> 244
~ ___service_cache_block_invoke : 132 -> 120
~ ___service_cache_block_invoke_2 : 84 -> 72
~ _metadata_release : 144 -> 132
~ ___create_xpc_dictionary_applier_block_invoke : 96 -> 84
~ ___create_xpc_from_cftype_block_invoke : 92 -> 80
~ ___libinfo_cache_add_block_invoke : 116 -> 104
~ ___add_cache_key_value_block_invoke : 168 -> 156
~ ___getAll_block_invoke : 120 -> 108
~ ___protocol_cache_block_invoke : 132 -> 120
~ ___protocol_cache_block_invoke_2 : 84 -> 72
~ ___rpc_cache_block_invoke : 132 -> 120
~ ___rpc_cache_block_invoke_2 : 84 -> 72
~ ___fstab_cache_block_invoke : 132 -> 120
~ ___alias_cache_block_invoke : 132 -> 120
~ ___alias_cache_block_invoke_2 : 84 -> 72
~ ___network_cache_block_invoke : 132 -> 120
~ ___network_cache_block_invoke_2 : 84 -> 72
~ ___netgroup_cache_block_invoke : 132 -> 120
~ ___netgroup_cache_block_invoke_2 : 84 -> 72
~ ___bootp_cache_block_invoke : 148 -> 136
- _OUTLINED_FUNCTION_6
~ _OUTLINED_FUNCTION_9 : 32 -> 20
~ _OUTLINED_FUNCTION_10 : 32 -> 20
~ _OUTLINED_FUNCTION_18 : 28 -> 16
~ _OUTLINED_FUNCTION_20 : 32 -> 20
~ _register_membership_types : 288 -> 276
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_2 : 80 -> 68
~ ____response_generate_block_invoke : 536 -> 524
~ ___response_generate_block_invoke.23 : 220 -> 208
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _odm_register_rpc_types : 68 -> 56
~ _odm_flush_entire_cache : 48 -> 36
~ process_getpwnam_initext.cold.1 : 344 -> 332
```

## mod_perl.so

> `/usr/libexec/apache2/mod_perl.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 117.0.0.0.0
-  __TEXT.__text: 0x1a7b4
+  __TEXT.__text: 0x1a30c
   __TEXT.__auth_stubs: 0x11a0
   __TEXT.__cstring: 0x3a5b
   __TEXT.__const: 0x51
-  __TEXT.__unwind_info: 0x590
+  __TEXT.__unwind_info: 0x790
   __DATA_CONST.__const: 0xac8
   __DATA_CONST.__auth_got: 0x8d0
   __DATA_CONST.__got: 0xa0
Functions:
~ sub_9e0 : 76 -> 64
~ _modperl_init : 204 -> 192
~ _modperl_init_globals : 104 -> 92
~ _modperl_register_hooks : 656 -> 644
~ sub_1654 -> sub_1624 : 100 -> 88
~ _modperl_interp_destroy : 148 -> 136
~ _modperl_thx_interp_set : 88 -> 76
~ sub_2e34 -> sub_2de0 : 160 -> 148
~ _modperl_cmd_config_requires : 80 -> 68
~ sub_439c -> sub_4330 : 164 -> 152
~ sub_4488 -> sub_4410 : 92 -> 80
~ _modperl_cmd_load_module : 80 -> 68
~ _modperl_callback : 1144 -> 1148
~ _modperl_handler_anon_init : 132 -> 120
~ _modperl_handler_equal : 80 -> 68
~ _modperl_handler_perl_get_handlers : 340 -> 328
~ _modperl_require_module : 648 -> 664
~ _modperl_newSVsv_obj : 140 -> 128
~ _modperl_xs_dl_handles_clear : 88 -> 76
~ _modperl_xs_dl_handles_close : 88 -> 76
~ _modperl_perl_exit : 88 -> 76
~ _modperl_dir_config : 264 -> 252
~ _modperl_table_get_set : 308 -> 296
~ _modperl_apr_array_header2avrv : 152 -> 140
~ _modperl_pnotes_kill : 140 -> 128
~ _modperl_pnotes : 424 -> 412
~ _modperl_register_auth_provider : 148 -> 136
~ sub_9b1c -> sub_9a04 : 264 -> 252
~ _modperl_register_auth_provider_name : 188 -> 176
~ sub_9ce0 -> sub_9bb0 : 208 -> 196
~ _modperl_io_perlio_restore_stdin : 80 -> 68
~ _modperl_io_perlio_restore_stdout : 368 -> 356
~ sub_ab98 -> sub_aa44 : 88 -> 76
~ sub_ac18 -> sub_aab8 : 28 -> 16
~ sub_ac34 -> sub_aac8 : 32 -> 20
~ sub_ade0 -> sub_ac68 : 140 -> 128
~ _modperl_wbucket_flush : 180 -> 156
~ _modperl_wbucket_write : 200 -> 188
~ _modperl_output_filter_write : 272 -> 260
~ _modperl_output_filter_handler : 120 -> 108
~ _modperl_input_filter_handler : 224 -> 212
~ _modperl_filter_runtime_add : 500 -> 488
~ sub_c82c -> sub_c654 : 36 -> 24
~ sub_c850 -> sub_c66c : 28 -> 16
~ sub_c86c -> sub_c67c : 32 -> 20
~ sub_c9b0 -> sub_c7b4 : 92 -> 80
~ _modperl_mgv_lookup : 148 -> 136
~ _modperl_mgv_lookup_autoload : 164 -> 152
~ _modperl_mgv_hash_handlers : 152 -> 140
~ sub_dee4 -> sub_dcb8 : 24 -> 12
~ _modperl_tls_reset_cleanup_request_rec : 120 -> 108
~ _modperl_global_request_obj_set : 40 -> 28
~ _modperl_global_init : 164 -> 152
~ _modperl_global_anon_cnt_init : 84 -> 72
~ _modperl_tls_reset_cleanup : 116 -> 104
~ _modperl_env_sync_srv_env_hash2table : 68 -> 56
~ _modperl_env_configure_server : 204 -> 192
~ sub_f9d4 -> sub_f748 : 400 -> 388
~ sub_fb64 -> sub_f8cc : 96 -> 84
~ sub_fc6c -> sub_f9c8 : 324 -> 312
~ sub_fdb0 -> sub_fb00 : 204 -> 192
~ _modperl_env_unload : 184 -> 172
~ _modperl_perl_destruct : 204 -> 192
~ _modperl_perl_global_avcv_call : 88 -> 76
~ _modperl_perl_global_avcv_clear : 80 -> 68
~ _modperl_module_config_table_set : 100 -> 88
~ sub_11dcc -> sub_11ad4 : 188 -> 176
~ sub_12344 -> sub_12040 : 164 -> 152
~ _modperl_svptr_table_destroy : 176 -> 164
~ _modperl_svptr_table_free : 72 -> 60
~ _modperl_svptr_table_store : 196 -> 184
~ _modperl_constants_lookup_apr_const : 5540 -> 5528
~ _modperl_constants_lookup_apache2_const : 6184 -> 6160
~ _modperl_constants_lookup_modperl : 184 -> 172
~ _ap_get_server_version : 104 -> 92
~ _modperl_register_handler_hooks : 512 -> 500
~ _modperl_cmd_process_connection_handlers : 164 -> 152
~ _modperl_cmd_open_logs_handlers : 164 -> 152
~ _modperl_cmd_post_config_handlers : 164 -> 152
~ _modperl_cmd_header_parser_handlers : 164 -> 152
~ _modperl_cmd_access_handlers : 164 -> 152
~ _modperl_cmd_authen_handlers : 164 -> 152
~ _modperl_cmd_authz_handlers : 164 -> 152
~ _modperl_cmd_type_handlers : 164 -> 152
~ _modperl_cmd_fixup_handlers : 164 -> 152
~ _modperl_cmd_response_handlers : 164 -> 152
~ _modperl_cmd_log_handlers : 164 -> 152
~ _modperl_cmd_cleanup_handlers : 164 -> 152
~ _modperl_cmd_input_filter_handlers : 164 -> 152
~ _modperl_cmd_output_filter_handlers : 164 -> 152
~ _modperl_cmd_post_read_request_handlers : 164 -> 152
~ _modperl_cmd_trans_handlers : 164 -> 152
~ _modperl_cmd_map_to_storage_handlers : 164 -> 152
~ _modperl_cmd_pre_connection_handlers : 164 -> 152
~ _modperl_cmd_child_init_handlers : 164 -> 152
~ _modperl_cmd_child_exit_handlers : 164 -> 152
~ _xs_init : 84 -> 72
~ sub_192e0 -> sub_18e68 : 260 -> 248
~ _modperl_io_handle_tie : 164 -> 152
~ sub_1a62c -> sub_1a19c : 124 -> 112
~ _modperl_perl_core_global_init : 168 -> 156
```

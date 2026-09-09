## postconf

> `/usr/sbin/postconf`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2923c
+  __TEXT.__text: 0x28bf4
   __TEXT.__auth_stubs: 0xc70
   __TEXT.__cstring: 0xec91
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x840
+  __TEXT.__unwind_info: 0xae0
   __DATA_CONST.__const: 0x7fb0
   __DATA_CONST.__auth_got: 0x638
   __DATA_CONST.__got: 0x58
Functions:
~ _pcf_register_builtin_parameters : 972 -> 960
~ _pcf_read_parameters : 140 -> 128
~ _pcf_show_parameters : 296 -> 284
~ sub_1000027d4 -> sub_1000027b0 : 228 -> 216
~ _pcf_free_master_entry : 108 -> 96
~ _pcf_print_master_entry : 808 -> 796
~ _pcf_show_master_entries : 532 -> 520
~ _pcf_show_master_fields : 656 -> 644
~ sub_10000372c -> sub_1000036cc : 996 -> 984
~ _pcf_edit_master_field : 132 -> 120
~ _pcf_show_master_params : 620 -> 608
~ sub_100003f2c -> sub_100003ea8 : 232 -> 220
~ _pcf_edit_master_param : 696 -> 684
~ _pcf_set_config_dir : 128 -> 116
~ _pcf_show_maps : 132 -> 120
~ _pcf_show_locks : 132 -> 120
~ _pcf_show_sasl : 144 -> 132
~ _pcf_flag_unused_main_parameters : 108 -> 96
~ _pcf_register_dbms_parameters : 112 -> 100
~ _pcf_lookup_parameter_value : 184 -> 172
~ _xsasl_server_init : 164 -> 152
~ sub_100005e94 -> sub_100005d98 : 40 -> 28
~ sub_100005ebc -> sub_100005db4 : 92 -> 80
~ _xsasl_client_init : 120 -> 108
~ sub_1000068f8 -> sub_1000067d8 : 40 -> 28
~ sub_100006ab0 -> sub_100006984 : 108 -> 96
~ sub_1000070e4 -> sub_100006fac : 64 -> 52
~ sub_100007184 -> sub_100007040 : 116 -> 104
~ sub_1000071f8 -> sub_1000070a8 : 664 -> 652
~ sub_100007490 -> sub_100007334 : 260 -> 248
~ _tls_param_init : 92 -> 80
~ _tls_free_app_context : 112 -> 100
~ _tls_free_context : 204 -> 192
~ sub_100008898 -> sub_10000870c : 632 -> 624
~ _been_here_free : 64 -> 52
~ sub_10000902c -> sub_100008e8c : 196 -> 184
~ sub_100009294 -> sub_1000090e8 : 152 -> 140
~ sub_10000932c -> sub_100009174 : 152 -> 140
~ sub_1000093c4 -> sub_100009200 : 128 -> 116
~ sub_1000097ac -> sub_1000095dc : 172 -> 160
~ sub_100009858 -> sub_10000967c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100009950 -> sub_10000975c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000b488 -> sub_10000b258 : 68 -> 56
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_10000d89c -> sub_10000d610 : 1244 -> 1224
~ sub_10000f354 -> sub_10000f0b4 : 148 -> 136
~ sub_10000f3e8 -> sub_10000f13c : 464 -> 468
~ sub_10001111c -> sub_100010e74 : 336 -> 324
~ sub_1000123d8 -> sub_100012124 : 164 -> 152
~ sub_100012614 -> sub_100012354 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100013d38 -> sub_100013a68 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013f14 -> sub_100013c2c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000154bc -> sub_100015194 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100015744 -> sub_100015404 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100016b60 -> sub_1000167d8 : 96 -> 84
~ sub_100017698 -> sub_100017304 : 172 -> 160
~ sub_100017a74 -> sub_1000176d4 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100017b60 -> sub_1000177a8 : 112 -> 100
~ sub_100017c58 -> sub_100017894 : 64 -> 52
~ sub_100017d4c -> sub_10001797c : 116 -> 104
~ sub_100017f70 -> sub_100017b94 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018f58 -> sub_100018b68 : 248 -> 236
~ sub_100019294 -> sub_100018e98 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001999c -> sub_100019598 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100019dc4 -> sub_1000199a8 : 64 -> 52
~ sub_100019eac -> sub_100019a84 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a980 -> sub_10001a544 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001e684 -> sub_10001e20c : 152 -> 140
~ _mvect_realloc : 128 -> 124
~ _mymalloc : 148 -> 136
~ _myrealloc : 328 -> 316
~ _myfree : 216 -> 204
~ _mystrdup : 128 -> 116
~ _mymemdup : 84 -> 72
~ _myrand : 88 -> 76
~ _netstring_get_data : 220 -> 212
~ _netstring_get : 104 -> 92
~ _netstring_put : 228 -> 208
~ _open_limit : 184 -> 180
~ _printable : 120 -> 124
~ _safe_getenv : 76 -> 64
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_1000226b8 -> sub_100022178 : 984 -> 976
~ sub_100022f9c -> sub_100022a54 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100024b68 -> sub_100024600 : 144 -> 140
~ _edit_file_cleanup : 132 -> 120
~ _dict_fail_open : 192 -> 180
~ sub_100025e5c -> sub_1000258d8 : 60 -> 48
~ sub_1000264a0 -> sub_100025f10 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000272dc -> sub_100026d44 : 228 -> 216
~ sub_100027578 -> sub_100026fd4 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100027c50 -> sub_1000276a4 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100027e64 -> sub_1000278a0 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100028a40 -> sub_100028440 : 100 -> 88
~ sub_100029424 -> sub_100028e18 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

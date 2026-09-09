## showq

> `/usr/libexec/postfix/showq`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2aa58
+  __TEXT.__text: 0x2a484
   __TEXT.__auth_stubs: 0xaa0
   __TEXT.__cstring: 0x92c5
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x888
+  __TEXT.__unwind_info: 0xb70
   __DATA_CONST.__const: 0x1580
   __DATA_CONST.__auth_got: 0x550
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100001b24 : 300 -> 276
~ sub_100001c50 -> sub_100001c38 : 300 -> 276
~ sub_100001f18 -> sub_100001ee8 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100003814 -> sub_1000037cc : 196 -> 184
~ sub_100003a7c -> sub_100003a28 : 152 -> 140
~ sub_100003b14 -> sub_100003ab4 : 152 -> 140
~ sub_100003bac -> sub_100003b40 : 128 -> 116
~ sub_100003f94 -> sub_100003f1c : 172 -> 160
~ sub_100004040 -> sub_100003fbc : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100004138 -> sub_10000409c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_1000062f0 -> sub_10000620c : 68 -> 56
~ _dsb_free : 108 -> 96
~ _get_file_id_st : 152 -> 140
~ _log_adhoc : 1796 -> 1764
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_raw : 128 -> 116
~ _get_mail_conf_raw_fn : 132 -> 120
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ sub_10000af90 -> sub_10000adf0 : 1244 -> 1224
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000ec94 -> sub_10000eaa4 : 148 -> 136
~ sub_10000ed28 -> sub_10000eb2c : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100010fec -> sub_100010ddc : 336 -> 324
~ sub_1000122a8 -> sub_10001208c : 164 -> 152
~ sub_1000124e4 -> sub_1000122bc : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100013c08 -> sub_1000139d0 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013de4 -> sub_100013b94 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000154c4 -> sub_100015234 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10001574c -> sub_1000154a4 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100016b68 -> sub_100016878 : 96 -> 84
~ sub_1000176a0 -> sub_1000173a4 : 172 -> 160
~ sub_100017a7c -> sub_100017774 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100017b68 -> sub_100017848 : 112 -> 100
~ sub_100017c60 -> sub_100017934 : 64 -> 52
~ sub_100017d54 -> sub_100017a1c : 116 -> 104
~ sub_100017f78 -> sub_100017c34 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018f60 -> sub_100018c08 : 248 -> 236
~ sub_10001929c -> sub_100018f38 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_1000199a4 -> sub_100019638 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100019dcc -> sub_100019a48 : 64 -> 52
~ sub_10001a070 -> sub_100019ce0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001ab44 -> sub_10001a7a0 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001ed9c -> sub_10001e9bc : 152 -> 140
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
~ _safe_open : 340 -> 316
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_1000235a0 -> sub_1000230e0 : 984 -> 976
~ sub_100023e84 -> sub_1000239bc : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100025a50 -> sub_100025568 : 144 -> 140
~ sub_100026260 -> sub_100025d74 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_1000273b4 -> sub_100026ea4 : 60 -> 48
~ sub_1000279f8 -> sub_1000274dc : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100028b20 -> sub_1000285fc : 228 -> 216
~ sub_100028dbc -> sub_10002888c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100029494 -> sub_100028f5c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000296a8 -> sub_100029158 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002a284 -> sub_100029cf8 : 100 -> 88
~ sub_10002ac68 -> sub_10002a6d0 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

## flush

> `/usr/libexec/postfix/flush`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x29a90
+  __TEXT.__text: 0x294e4
   __TEXT.__auth_stubs: 0xac0
   __TEXT.__cstring: 0x928e
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x838
+  __TEXT.__unwind_info: 0xb28
   __DATA_CONST.__const: 0x1500
   __DATA_CONST.__auth_got: 0x560
   __DATA_CONST.__got: 0x58
Functions:
~ sub_10000090c : 1536 -> 1524
~ sub_100001278 -> sub_10000126c : 320 -> 324
~ sub_1000024a8 -> sub_1000024a0 : 300 -> 276
~ sub_1000025d4 -> sub_1000025b4 : 300 -> 276
~ sub_10000289c -> sub_100002864 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100003c24 -> sub_100003bd4 : 196 -> 184
~ sub_100003e8c -> sub_100003e30 : 152 -> 140
~ sub_100003f24 -> sub_100003ebc : 152 -> 140
~ sub_100003fbc -> sub_100003f48 : 128 -> 116
~ sub_1000043a4 -> sub_100004324 : 172 -> 160
~ sub_100004450 -> sub_1000043c4 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100004548 -> sub_1000044a4 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006700 -> sub_100006614 : 68 -> 56
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
~ sub_10000aa78 -> sub_10000a8dc : 1244 -> 1224
~ _REMOVE : 272 -> 260
~ sub_10000d844 -> sub_10000d688 : 148 -> 136
~ sub_10000d8d8 -> sub_10000d710 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000fb9c -> sub_10000f9c0 : 336 -> 324
~ sub_100010e58 -> sub_100010c70 : 164 -> 152
~ sub_100011094 -> sub_100010ea0 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000127b8 -> sub_1000125b4 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100012994 -> sub_100012778 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014074 -> sub_100013e18 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000142fc -> sub_100014088 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100015718 -> sub_10001545c : 96 -> 84
~ sub_100016250 -> sub_100015f88 : 172 -> 160
~ sub_10001662c -> sub_100016358 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100016718 -> sub_10001642c : 112 -> 100
~ sub_100016810 -> sub_100016518 : 64 -> 52
~ sub_100016904 -> sub_100016600 : 116 -> 104
~ sub_100016b28 -> sub_100016818 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100017b10 -> sub_1000177ec : 248 -> 236
~ sub_100017e4c -> sub_100017b1c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100018554 -> sub_10001821c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001897c -> sub_10001862c : 64 -> 52
~ sub_100018c20 -> sub_1000188c4 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_1000196f4 -> sub_100019384 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001da94 -> sub_10001d6e8 : 152 -> 140
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
~ sub_100021114 -> sub_100020cc4 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_1000224bc -> sub_100022024 : 984 -> 976
~ sub_100022da0 -> sub_100022900 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10002496c -> sub_1000244ac : 144 -> 140
~ sub_10002517c -> sub_100024cb8 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_1000263ec -> sub_100025f04 : 60 -> 48
~ sub_100026a30 -> sub_10002653c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100027b58 -> sub_10002765c : 228 -> 216
~ sub_100027df4 -> sub_1000278ec : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000284cc -> sub_100027fbc : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000286e0 -> sub_1000281b8 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000292bc -> sub_100028d58 : 100 -> 88
~ sub_100029ca0 -> sub_100029730 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

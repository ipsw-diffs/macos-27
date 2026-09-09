## proxymap

> `/usr/libexec/postfix/proxymap`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x26590
+  __TEXT.__text: 0x26020
   __TEXT.__auth_stubs: 0xa20
   __TEXT.__cstring: 0x8b76
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x7d8
+  __TEXT.__unwind_info: 0xa88
   __DATA_CONST.__const: 0x1700
   __DATA_CONST.__auth_got: 0x510
   __DATA_CONST.__got: 0x58
Functions:
~ _dict_proxy_open : 164 -> 152
~ _multi_server_disconnect : 248 -> 236
~ sub_1000020ec -> sub_1000020d4 : 260 -> 236
~ sub_1000021f0 -> sub_1000021c0 : 260 -> 236
~ sub_10000243c -> sub_1000023f4 : 416 -> 392
~ sub_1000025f8 -> sub_100002598 : 268 -> 256
~ _been_here_free : 64 -> 52
~ sub_10000388c -> sub_100003814 : 196 -> 184
~ sub_100003af4 -> sub_100003a70 : 152 -> 140
~ sub_100003b8c -> sub_100003afc : 152 -> 140
~ sub_100003c24 -> sub_100003b88 : 128 -> 116
~ sub_10000400c -> sub_100003f64 : 172 -> 160
~ sub_1000040b8 -> sub_100004004 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000041b0 -> sub_1000040e4 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
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
~ sub_100008bdc -> sub_100008a4c : 1244 -> 1224
~ sub_10000b534 -> sub_10000b390 : 148 -> 136
~ sub_10000b5c8 -> sub_10000b418 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000d88c -> sub_10000d6c8 : 336 -> 324
~ sub_10000eb48 -> sub_10000e978 : 164 -> 152
~ sub_10000ed84 -> sub_10000eba8 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000104a8 -> sub_1000102bc : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100010684 -> sub_100010480 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100011d64 -> sub_100011b20 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100011fec -> sub_100011d90 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100013408 -> sub_100013164 : 96 -> 84
~ sub_100013f40 -> sub_100013c90 : 172 -> 160
~ sub_10001431c -> sub_100014060 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100014408 -> sub_100014134 : 112 -> 100
~ sub_100014500 -> sub_100014220 : 64 -> 52
~ sub_1000145f4 -> sub_100014308 : 116 -> 104
~ sub_100014818 -> sub_100014520 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100015800 -> sub_1000154f4 : 248 -> 236
~ sub_100015b3c -> sub_100015824 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100016244 -> sub_100015f24 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001666c -> sub_100016334 : 64 -> 52
~ sub_100016754 -> sub_100016410 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100017228 -> sub_100016ed0 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001b2b4 -> sub_10001af20 : 152 -> 140
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
~ sub_10001f2a0 -> sub_10001ee44 : 984 -> 976
~ sub_10001fb84 -> sub_10001f720 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100021750 -> sub_1000212cc : 144 -> 140
~ sub_100021f60 -> sub_100021ad8 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100022eec -> sub_100022a40 : 60 -> 48
~ sub_100023530 -> sub_100023078 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100024658 -> sub_100024198 : 228 -> 216
~ sub_1000248f4 -> sub_100024428 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100024fcc -> sub_100024af8 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000251e0 -> sub_100024cf4 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100025dbc -> sub_100025894 : 100 -> 88
~ sub_1000267a0 -> sub_10002626c : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

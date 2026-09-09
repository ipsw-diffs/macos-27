## dnsblog

> `/usr/libexec/postfix/dnsblog`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x29300
+  __TEXT.__text: 0x28d64
   __TEXT.__auth_stubs: 0xa80
   __TEXT.__cstring: 0x941b
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x810
+  __TEXT.__unwind_info: 0xaf0
   __DATA_CONST.__const: 0x1900
   __DATA_CONST.__auth_got: 0x540
   __DATA_CONST.__got: 0x60
Functions:
~ sub_10000090c : 1284 -> 1276
~ _dns_rr_free : 88 -> 76
~ _dns_rr_to_pa : 100 -> 88
~ _dns_str_resflags : 96 -> 84
~ sub_100003878 -> sub_10000384c : 300 -> 276
~ sub_1000039a4 -> sub_100003960 : 300 -> 276
~ sub_100003c6c -> sub_100003c10 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100004ff4 -> sub_100004f80 : 196 -> 184
~ sub_10000525c -> sub_1000051dc : 152 -> 140
~ sub_1000052f4 -> sub_100005268 : 152 -> 140
~ sub_10000538c -> sub_1000052f4 : 128 -> 116
~ sub_100005774 -> sub_1000056d0 : 172 -> 160
~ sub_100005820 -> sub_100005770 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100005918 -> sub_100005850 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100007ad0 -> sub_1000079c0 : 68 -> 56
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
~ sub_10000b310 -> sub_10000b16c : 1244 -> 1224
~ sub_10000dc68 -> sub_10000dab0 : 148 -> 136
~ sub_10000dcfc -> sub_10000db38 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000ffc0 -> sub_10000fde8 : 336 -> 324
~ sub_10001127c -> sub_100011098 : 164 -> 152
~ sub_1000114b8 -> sub_1000112c8 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100012bdc -> sub_1000129dc : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100012db8 -> sub_100012ba0 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014498 -> sub_100014240 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100014720 -> sub_1000144b0 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100015b3c -> sub_100015884 : 96 -> 84
~ sub_100016674 -> sub_1000163b0 : 172 -> 160
~ sub_100016a50 -> sub_100016780 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100016b3c -> sub_100016854 : 112 -> 100
~ sub_100016c34 -> sub_100016940 : 64 -> 52
~ sub_100016d28 -> sub_100016a28 : 116 -> 104
~ sub_100016f4c -> sub_100016c40 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100017f34 -> sub_100017c14 : 248 -> 236
~ sub_100018270 -> sub_100017f44 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100018978 -> sub_100018644 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100018da0 -> sub_100018a54 : 64 -> 52
~ sub_100018e88 -> sub_100018b30 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001995c -> sub_1000195f0 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001d9e8 -> sub_10001d640 : 152 -> 140
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
~ sub_100021e48 -> sub_1000219c0 : 984 -> 976
~ sub_10002272c -> sub_10002229c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_1000242f8 -> sub_100023e48 : 144 -> 140
~ sub_100024b08 -> sub_100024654 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100025c5c -> sub_100025784 : 60 -> 48
~ sub_1000262a0 -> sub_100025dbc : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000273c8 -> sub_100026edc : 228 -> 216
~ sub_100027664 -> sub_10002716c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100027d3c -> sub_10002783c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100027f50 -> sub_100027a38 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100028b2c -> sub_1000285d8 : 100 -> 88
~ sub_100029510 -> sub_100028fb0 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

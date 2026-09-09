## verify

> `/usr/libexec/postfix/verify`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2aa14
+  __TEXT.__text: 0x2a40c
   __TEXT.__auth_stubs: 0xab0
   __TEXT.__cstring: 0x96a1
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x890
+  __TEXT.__unwind_info: 0xb78
   __DATA_CONST.__const: 0x1770
   __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000eb8 : 212 -> 200
~ _multi_server_disconnect : 248 -> 236
~ sub_100001e88 -> sub_100001e70 : 260 -> 236
~ sub_100001f8c -> sub_100001f5c : 260 -> 236
~ sub_1000021d8 -> sub_100002190 : 416 -> 392
~ sub_100002394 -> sub_100002334 : 268 -> 256
~ _been_here_free : 64 -> 52
~ sub_100003628 -> sub_1000035b0 : 196 -> 184
~ sub_100003890 -> sub_10000380c : 152 -> 140
~ sub_100003928 -> sub_100003898 : 152 -> 140
~ sub_1000039c0 -> sub_100003924 : 128 -> 116
~ sub_100003da8 -> sub_100003d00 : 172 -> 160
~ sub_100003e54 -> sub_100003da0 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100003f4c -> sub_100003e80 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006104 -> sub_100005ff0 : 68 -> 56
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
~ _mail_date : 616 -> 612
~ sub_100009c48 -> sub_100009a9c : 1244 -> 1224
~ sub_10000aa7c -> sub_10000a8bc : 608 -> 596
~ _post_mail_fopen_async : 264 -> 252
~ sub_10000aea4 -> sub_10000accc : 408 -> 396
~ _post_mail_fclose_async : 256 -> 244
~ _quote_822_local_flags : 664 -> 652
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _data_redirect_file : 64 -> 52
~ sub_10000ea10 -> sub_10000e7f0 : 148 -> 136
~ sub_10000eaa4 -> sub_10000e878 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100010e24 -> sub_100010be4 : 336 -> 324
~ sub_1000120e0 -> sub_100011e94 : 164 -> 152
~ sub_10001231c -> sub_1000120c4 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100013a40 -> sub_1000137d8 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013c1c -> sub_10001399c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000152fc -> sub_10001503c : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100015584 -> sub_1000152ac : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000169a0 -> sub_100016680 : 96 -> 84
~ sub_1000174d8 -> sub_1000171ac : 172 -> 160
~ sub_1000178b4 -> sub_10001757c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000179a0 -> sub_100017650 : 112 -> 100
~ sub_100017a98 -> sub_10001773c : 64 -> 52
~ sub_100017b8c -> sub_100017824 : 116 -> 104
~ sub_100017db0 -> sub_100017a3c : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018d98 -> sub_100018a10 : 248 -> 236
~ sub_1000190d4 -> sub_100018d40 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_1000197dc -> sub_100019440 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100019c04 -> sub_100019850 : 64 -> 52
~ sub_100019cec -> sub_10001992c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a7c0 -> sub_10001a3ec : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001e84c -> sub_10001e43c : 152 -> 140
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
~ sub_100022978 -> sub_1000224a0 : 984 -> 976
~ sub_10002325c -> sub_100022d7c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100024e28 -> sub_100024928 : 144 -> 140
~ sub_100025638 -> sub_100025134 : 308 -> 284
~ _dict_cache_control : 600 -> 596
~ sub_10002671c -> sub_1000261fc : 480 -> 468
~ _dict_cache_close : 124 -> 112
~ _dict_fail_open : 192 -> 180
~ sub_100027370 -> sub_100026e2c : 60 -> 48
~ sub_1000279b4 -> sub_100027464 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100028adc -> sub_100028584 : 228 -> 216
~ sub_100028d78 -> sub_100028814 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100029450 -> sub_100028ee4 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100029664 -> sub_1000290e0 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002a240 -> sub_100029c80 : 100 -> 88
~ sub_10002ac24 -> sub_10002a658 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

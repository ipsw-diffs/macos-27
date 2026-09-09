## bounce

> `/usr/libexec/postfix/bounce`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x3002c
+  __TEXT.__text: 0x2f980
   __TEXT.__auth_stubs: 0xac0
   __TEXT.__cstring: 0xa9a0
   __TEXT.__const: 0x1e2
-  __TEXT.__unwind_info: 0x970
+  __TEXT.__unwind_info: 0xc78
   __DATA_CONST.__const: 0x19d8
   __DATA_CONST.__auth_got: 0x560
   __DATA_CONST.__got: 0x58
Functions:
~ sub_1000013e8 : 100 -> 88
~ _bounce_cleanup_log : 76 -> 64
~ _bounce_cleanup_register : 180 -> 168
~ sub_1000020fc -> sub_1000020d8 : 72 -> 60
~ _bounce_mail_free : 184 -> 172
~ _bounce_template_free : 72 -> 60
~ sub_100004564 -> sub_10000451c : 880 -> 868
~ _bounce_template_expand : 244 -> 232
~ sub_1000049c8 -> sub_100004968 : 624 -> 612
~ _bounce_templates_free : 84 -> 72
~ _bounce_templates_expand : 312 -> 300
~ _bounce_templates_dump : 280 -> 268
~ sub_100006020 -> sub_100005f90 : 300 -> 276
~ sub_10000614c -> sub_1000060a4 : 300 -> 276
~ sub_100006414 -> sub_100006354 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100007d10 -> sub_100007c38 : 196 -> 184
~ sub_100007f78 -> sub_100007e94 : 152 -> 140
~ sub_100008010 -> sub_100007f20 : 152 -> 140
~ sub_1000080a8 -> sub_100007fac : 128 -> 116
~ sub_100008490 -> sub_100008388 : 172 -> 160
~ sub_10000853c -> sub_100008428 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100008634 -> sub_100008508 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000a93c -> sub_10000a7c8 : 68 -> 56
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
~ _mail_date : 616 -> 612
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ sub_10000f9d4 -> sub_10000f7a0 : 1244 -> 1224
~ sub_100010808 -> sub_1000105c0 : 608 -> 596
~ _post_mail_fopen_async : 264 -> 252
~ sub_100010c30 -> sub_1000109d0 : 408 -> 396
~ _post_mail_fclose_async : 256 -> 244
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10001407c -> sub_100013dc8 : 148 -> 136
~ sub_100014110 -> sub_100013e50 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100016490 -> sub_1000161bc : 336 -> 324
~ sub_10001774c -> sub_10001746c : 164 -> 152
~ sub_100017988 -> sub_10001769c : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000190ac -> sub_100018db0 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100019288 -> sub_100018f74 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001a968 -> sub_10001a614 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10001abf0 -> sub_10001a884 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001c00c -> sub_10001bc58 : 96 -> 84
~ sub_10001cb44 -> sub_10001c784 : 172 -> 160
~ sub_10001cf20 -> sub_10001cb54 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001d00c -> sub_10001cc28 : 112 -> 100
~ sub_10001d104 -> sub_10001cd14 : 64 -> 52
~ sub_10001d1f8 -> sub_10001cdfc : 116 -> 104
~ sub_10001d41c -> sub_10001d014 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001e404 -> sub_10001dfe8 : 248 -> 236
~ sub_10001e740 -> sub_10001e318 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001ee48 -> sub_10001ea18 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001f270 -> sub_10001ee28 : 64 -> 52
~ sub_10001f514 -> sub_10001f0c0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001ffe8 -> sub_10001fb80 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _line_wrap : 412 -> 400
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_1000243dc -> sub_100023f2c : 152 -> 140
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
~ _rand_sleep : 156 -> 144
~ _safe_getenv : 76 -> 64
~ _safe_open : 340 -> 316
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_1000289d4 -> sub_100028438 : 984 -> 976
~ sub_1000292b8 -> sub_100028d14 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10002ae84 -> sub_10002a8c0 : 144 -> 140
~ sub_10002b694 -> sub_10002b0cc : 308 -> 284
~ _allspace : 60 -> 64
~ _dict_fail_open : 192 -> 180
~ sub_10002c988 -> sub_10002c3a0 : 60 -> 48
~ sub_10002cfcc -> sub_10002c9d8 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002e0f4 -> sub_10002daf8 : 228 -> 216
~ sub_10002e390 -> sub_10002dd88 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002ea68 -> sub_10002e458 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002ec7c -> sub_10002e654 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002f858 -> sub_10002f1f4 : 100 -> 88
~ sub_10003023c -> sub_10002fbcc : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

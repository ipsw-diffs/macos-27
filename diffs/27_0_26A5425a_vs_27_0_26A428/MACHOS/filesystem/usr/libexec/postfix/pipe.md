## pipe

> `/usr/libexec/postfix/pipe`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2edb4
+  __TEXT.__text: 0x2e758
   __TEXT.__auth_stubs: 0xb50
   __TEXT.__cstring: 0xa371
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x930
+  __TEXT.__unwind_info: 0xc30
   __DATA_CONST.__const: 0x17b8
   __DATA_CONST.__auth_got: 0x5a8
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100001c88 : 120 -> 108
~ sub_100002810 -> sub_100002804 : 300 -> 276
~ sub_10000293c -> sub_100002918 : 300 -> 276
~ sub_100002c04 -> sub_100002bc8 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100003f8c -> sub_100003f38 : 196 -> 184
~ sub_1000041f4 -> sub_100004194 : 152 -> 140
~ sub_10000428c -> sub_100004220 : 152 -> 140
~ sub_100004324 -> sub_1000042ac : 128 -> 116
~ sub_10000470c -> sub_100004688 : 172 -> 160
~ sub_1000047b8 -> sub_100004728 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000048b0 -> sub_100004808 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100007540 -> sub_100007450 : 68 -> 56
~ _dsn_free : 108 -> 96
~ _dsb_free : 108 -> 96
~ _get_file_id_st : 152 -> 140
~ _header_opts_find : 796 -> 788
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
~ _mbox_release : 76 -> 64
~ sub_10000d464 -> sub_10000d298 : 1244 -> 1224
~ sub_10000ebcc -> sub_10000e9ec : 192 -> 180
~ sub_10000ec8c -> sub_10000eaa0 : 192 -> 180
~ sub_10000ed4c -> sub_10000eb54 : 168 -> 156
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ _delivered_hdr_free : 80 -> 68
~ sub_100012748 -> sub_1000124f8 : 148 -> 136
~ sub_1000127dc -> sub_100012580 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100014b94 -> sub_100014924 : 336 -> 324
~ sub_100015e50 -> sub_100015bd4 : 164 -> 152
~ sub_10001608c -> sub_100015e04 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000177b0 -> sub_100017518 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10001798c -> sub_1000176dc : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001924c -> sub_100018f44 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000194d4 -> sub_1000191b4 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001a8f0 -> sub_10001a588 : 96 -> 84
~ sub_10001b428 -> sub_10001b0b4 : 172 -> 160
~ sub_10001b804 -> sub_10001b484 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001b8f0 -> sub_10001b558 : 112 -> 100
~ sub_10001b9e8 -> sub_10001b644 : 64 -> 52
~ sub_10001badc -> sub_10001b72c : 116 -> 104
~ sub_10001bd00 -> sub_10001b944 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001cce8 -> sub_10001c918 : 248 -> 236
~ sub_10001d024 -> sub_10001cc48 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001d72c -> sub_10001d348 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001db54 -> sub_10001d758 : 64 -> 52
~ sub_10001ddf8 -> sub_10001d9f0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001e8cc -> sub_10001e4b0 : 368 -> 364
~ _get_file_limit : 76 -> 72
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100022cb0 -> sub_100022854 : 152 -> 140
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
~ sub_10002794c -> sub_100027404 : 984 -> 976
~ sub_100028230 -> sub_100027ce0 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100029dfc -> sub_10002988c : 144 -> 140
~ sub_10002a60c -> sub_10002a098 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_10002b760 -> sub_10002b1c8 : 60 -> 48
~ sub_10002bda4 -> sub_10002b800 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002cecc -> sub_10002c920 : 228 -> 216
~ sub_10002d168 -> sub_10002cbb0 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002d840 -> sub_10002d280 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002da54 -> sub_10002d47c : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002e630 -> sub_10002e01c : 100 -> 88
~ sub_10002f014 -> sub_10002e9f4 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

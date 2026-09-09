## pickup

> `/usr/libexec/postfix/pickup`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x29d38
+  __TEXT.__text: 0x29784
   __TEXT.__auth_stubs: 0xad0
   __TEXT.__cstring: 0x9567
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x870
+  __TEXT.__unwind_info: 0xb48
   __DATA_CONST.__const: 0x1740
   __DATA_CONST.__auth_got: 0x568
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100001e20 : 436 -> 412
~ sub_100001fd4 -> sub_100001fbc : 176 -> 164
~ sub_100002084 -> sub_100002060 : 436 -> 412
~ _been_here_free : 64 -> 52
~ sub_1000035b0 -> sub_100003568 : 196 -> 184
~ sub_100003818 -> sub_1000037c4 : 152 -> 140
~ sub_1000038b0 -> sub_100003850 : 152 -> 140
~ sub_100003948 -> sub_1000038dc : 128 -> 116
~ sub_100003f2c -> sub_100003eb4 : 172 -> 160
~ sub_100003fd8 -> sub_100003f54 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000040d0 -> sub_100004034 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006288 -> sub_1000061a4 : 68 -> 56
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
~ sub_10000a920 -> sub_10000a788 : 1244 -> 1224
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000e148 -> sub_10000df78 : 148 -> 136
~ sub_10000e1dc -> sub_10000e000 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10001055c -> sub_10001036c : 336 -> 324
~ sub_100011818 -> sub_10001161c : 164 -> 152
~ sub_100011a54 -> sub_10001184c : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100013178 -> sub_100012f60 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013354 -> sub_100013124 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014a34 -> sub_1000147c4 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100014cbc -> sub_100014a34 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000160d8 -> sub_100015e08 : 96 -> 84
~ sub_100016c10 -> sub_100016934 : 172 -> 160
~ sub_100016fec -> sub_100016d04 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000170d8 -> sub_100016dd8 : 112 -> 100
~ sub_1000171d0 -> sub_100016ec4 : 64 -> 52
~ sub_1000172c4 -> sub_100016fac : 116 -> 104
~ sub_1000174e8 -> sub_1000171c4 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000184d0 -> sub_100018198 : 248 -> 236
~ sub_10001880c -> sub_1000184c8 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100018f14 -> sub_100018bc8 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001933c -> sub_100018fd8 : 64 -> 52
~ sub_1000195e0 -> sub_100019270 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a0b4 -> sub_100019d30 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001df84 -> sub_10001dbc4 : 152 -> 140
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
~ sub_100022880 -> sub_1000223e0 : 984 -> 976
~ sub_100023164 -> sub_100022cbc : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100024d30 -> sub_100024868 : 144 -> 140
~ sub_100025540 -> sub_100025074 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100026694 -> sub_1000261a4 : 60 -> 48
~ sub_100026cd8 -> sub_1000267dc : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100027e00 -> sub_1000278fc : 228 -> 216
~ sub_10002809c -> sub_100027b8c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100028774 -> sub_10002825c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100028988 -> sub_100028458 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100029564 -> sub_100028ff8 : 100 -> 88
~ sub_100029f48 -> sub_1000299d0 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

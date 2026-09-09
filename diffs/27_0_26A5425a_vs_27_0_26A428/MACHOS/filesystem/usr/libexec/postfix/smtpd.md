## smtpd

> `/usr/libexec/postfix/smtpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x56428
+  __TEXT.__text: 0x55b30
   __TEXT.__auth_stubs: 0x1440
   __TEXT.__cstring: 0x14c2f
   __TEXT.__const: 0x2b2
-  __TEXT.__unwind_info: 0xe00
+  __TEXT.__unwind_info: 0x12d0
   __DATA_CONST.__const: 0x4628
   __DATA_CONST.__auth_got: 0xa20
   __DATA_CONST.__got: 0x88
Functions:
~ sub_100002a6c : 148 -> 136
~ _smtpd_token : 752 -> 756
~ sub_1000086c0 -> sub_1000086b8 : 108 -> 96
~ sub_1000092c4 -> sub_1000092b0 : 272 -> 260
~ sub_10000c244 -> sub_10000c224 : 256 -> 244
~ sub_10000c490 -> sub_10000c464 : 204 -> 192
~ sub_10000c648 -> sub_10000c610 : 196 -> 184
~ sub_10000cf50 -> sub_10000cf0c : 448 -> 436
~ sub_10000d590 -> sub_10000d540 : 564 -> 552
~ sub_10000d7c4 -> sub_10000d768 : 316 -> 304
~ sub_10000f61c -> sub_10000f5b4 : 388 -> 376
~ sub_10000fcb0 -> sub_10000fc3c : 368 -> 356
~ sub_10000ff90 -> sub_10000ff10 : 108 -> 96
~ sub_100010c7c -> sub_100010bf0 : 136 -> 124
~ _smtpd_chat_notify : 508 -> 484
~ _smtpd_state_reset : 220 -> 208
~ _smtpd_peer_init : 2480 -> 2472
~ _smtpd_peer_reset : 152 -> 140
~ _smtpd_sasl_auth_cmd : 612 -> 600
~ sub_100013a2c -> sub_100013950 : 224 -> 212
~ sub_100013cd4 -> sub_100013bec : 88 -> 76
~ _smtpd_milter_eval : 1360 -> 1348
~ sub_100014714 -> sub_100014614 : 56 -> 44
~ _smtpd_resolve_addr : 168 -> 156
~ _smtpd_expand_init : 68 -> 56
~ _smtpd_expand_lookup : 660 -> 648
~ sub_100015978 -> sub_100015848 : 300 -> 276
~ sub_100015aa4 -> sub_10001595c : 300 -> 276
~ sub_100015d6c -> sub_100015c0c : 512 -> 500
~ _tls_pkey_fprint : 268 -> 256
~ sub_100016a2c -> sub_1000168b4 : 184 -> 176
~ sub_100016ae4 -> sub_100016964 : 200 -> 192
~ _tls_param_init : 92 -> 80
~ _tls_free_app_context : 112 -> 100
~ _tls_free_context : 204 -> 192
~ sub_100017960 -> sub_1000177b4 : 632 -> 624
~ _tls_set_dh_from_file : 244 -> 232
~ _tls_peer_CN : 96 -> 84
~ sub_1000184f4 -> sub_100018328 : 480 -> 484
~ _tls_issuer_CN : 128 -> 116
~ _tls_session_stop : 216 -> 204
~ _tls_scache_close : 124 -> 112
~ _tls_int_seed : 92 -> 80
~ _xsasl_server_init : 164 -> 152
~ sub_10001ad14 -> sub_10001ab10 : 40 -> 28
~ sub_10001ad3c -> sub_10001ab2c : 92 -> 80
~ sub_10001b644 -> sub_10001b428 : 64 -> 52
~ sub_10001b6e4 -> sub_10001b4bc : 116 -> 104
~ sub_10001b758 -> sub_10001b524 : 664 -> 652
~ sub_10001b9f0 -> sub_10001b7b0 : 260 -> 248
~ _milter_free : 148 -> 136
~ sub_10001f1c8 -> sub_10001ef70 : 176 -> 164
~ sub_100020bac -> sub_100020948 : 448 -> 444
~ _milter_macros_free : 148 -> 136
~ _dns_rr_free : 88 -> 76
~ _dns_rr_to_pa : 100 -> 88
~ _dns_str_resflags : 96 -> 84
~ _been_here_free : 64 -> 52
~ sub_1000247ac -> sub_100024508 : 196 -> 184
~ sub_100024a14 -> sub_100024764 : 152 -> 140
~ sub_100024aac -> sub_1000247f0 : 152 -> 140
~ sub_100024b44 -> sub_10002487c : 128 -> 116
~ sub_100025128 -> sub_100024e54 : 172 -> 160
~ sub_1000251d4 -> sub_100024ef4 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000252cc -> sub_100024fd4 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100027630 -> sub_1000272f0 : 68 -> 56
~ _get_file_id_st : 152 -> 140
~ _header_opts_find : 796 -> 788
~ _header_token : 1208 -> 1172
~ _log_adhoc : 1796 -> 1764
~ sub_1000296e8 -> sub_100029344 : 340 -> 328
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
~ _mail_stream_cleanup : 136 -> 124
~ sub_10002d89c -> sub_10002d464 : 144 -> 132
~ _mime_state_update : 4064 -> 4060
~ sub_10002ea08 -> sub_10002e5c0 : 1244 -> 1224
~ sub_10002f83c -> sub_10002f3e0 : 608 -> 596
~ _post_mail_fopen_async : 264 -> 252
~ sub_10002fc64 -> sub_10002f7f0 : 408 -> 396
~ _post_mail_fclose_async : 256 -> 244
~ _quote_821_local_flags : 664 -> 652
~ _quote_822_local_flags : 664 -> 652
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100032f2c -> sub_100032a64 : 316 -> 304
~ sub_10003640c -> sub_100035f38 : 148 -> 136
~ sub_1000364a0 -> sub_100035fc0 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100039598 -> sub_1000390a4 : 336 -> 324
~ sub_10003a854 -> sub_10003a354 : 164 -> 152
~ sub_10003aa90 -> sub_10003a584 : 220 -> 224
~ _allprint : 60 -> 64
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ _attr_clnt_free : 60 -> 48
~ sub_10003d4b8 -> sub_10003cf94 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10003d694 -> sub_10003d158 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10003ef54 -> sub_10003e9c0 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10003f1dc -> sub_10003ec30 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000405f8 -> sub_100040004 : 96 -> 84
~ sub_100041130 -> sub_100040b30 : 172 -> 160
~ sub_10004150c -> sub_100040f00 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000415f8 -> sub_100040fd4 : 112 -> 100
~ sub_1000416f0 -> sub_1000410c0 : 64 -> 52
~ sub_1000417e4 -> sub_1000411a8 : 116 -> 104
~ sub_100041a08 -> sub_1000413c0 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000429f0 -> sub_100042394 : 248 -> 236
~ sub_100042d2c -> sub_1000426c4 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100043434 -> sub_100042dc4 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10004385c -> sub_1000431d4 : 64 -> 52
~ sub_100043ba4 -> sub_100043510 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100044678 -> sub_100043fd0 : 368 -> 364
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
~ sub_100048fc4 -> sub_1000488d4 : 152 -> 140
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
~ sub_10004c9e0 -> sub_10004c24c : 176 -> 164
~ _uppercase : 100 -> 104
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_10004ddec -> sub_10004d614 : 984 -> 976
~ sub_10004e6d0 -> sub_10004def0 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10005077c -> sub_10004ff7c : 144 -> 140
~ sub_100050f8c -> sub_100050788 : 308 -> 284
~ _ip_match_save : 76 -> 64
~ _dict_fail_open : 192 -> 180
~ sub_100052d74 -> sub_100052540 : 60 -> 48
~ sub_1000533b8 -> sub_100052b78 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000544f0 -> sub_100053ca8 : 228 -> 216
~ sub_10005478c -> sub_100053f38 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100054e64 -> sub_100054608 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100055078 -> sub_100054804 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100055c54 -> sub_1000553a4 : 100 -> 88
~ sub_100056638 -> sub_100055d7c : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

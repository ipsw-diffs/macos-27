## local

> `/usr/libexec/postfix/local`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x36afc
+  __TEXT.__text: 0x363d0
   __TEXT.__auth_stubs: 0xbd0
   __TEXT.__cstring: 0xb5f4
   __TEXT.__const: 0x1f2
-  __TEXT.__unwind_info: 0xa20
+  __TEXT.__unwind_info: 0xd30
   __DATA_CONST.__const: 0x1c98
   __DATA_CONST.__auth_got: 0x5e8
   __DATA_CONST.__got: 0x58
Functions:
~ _deliver_command : 1748 -> 1736
~ _deliver_file : 1212 -> 1200
~ _deliver_include : 1320 -> 1308
~ _deliver_indirect : 440 -> 428
~ sub_10000368c -> sub_10000365c : 164 -> 152
~ sub_100003dd0 -> sub_100003d94 : 1568 -> 1556
~ _deliver_recipient : 1764 -> 1752
~ _deliver_maildir : 1652 -> 1640
~ _biff_notify : 352 -> 340
~ _deliver_unknown : 1076 -> 1028
~ _bounce_workaround : 916 -> 892
~ sub_100007520 -> sub_10000746c : 300 -> 276
~ sub_10000764c -> sub_100007580 : 300 -> 276
~ sub_100007914 -> sub_100007830 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100008cbc -> sub_100008bc0 : 196 -> 184
~ sub_100008f24 -> sub_100008e1c : 152 -> 140
~ sub_100008fbc -> sub_100008ea8 : 152 -> 140
~ sub_100009054 -> sub_100008f34 : 128 -> 116
~ sub_10000943c -> sub_100009310 : 172 -> 160
~ sub_1000094e8 -> sub_1000093b0 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000095e0 -> sub_100009490 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000c748 -> sub_10000c5b0 : 68 -> 56
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
~ _mail_date : 616 -> 612
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ _mbox_release : 76 -> 64
~ sub_100012a74 -> sub_1000127fc : 1244 -> 1224
~ _mypwfree : 220 -> 208
~ sub_100014700 -> sub_100014468 : 192 -> 180
~ sub_1000147c0 -> sub_10001451c : 192 -> 180
~ sub_100014880 -> sub_1000145d0 : 168 -> 156
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_1000173e4 -> sub_1000170e8 : 316 -> 304
~ _tok822_resolve_from : 216 -> 204
~ _delivered_hdr_free : 80 -> 68
~ sub_10001a504 -> sub_10001a1e4 : 148 -> 136
~ sub_10001a598 -> sub_10001a26c : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10001ca0c -> sub_10001c6cc : 336 -> 324
~ sub_10001dcc8 -> sub_10001d97c : 164 -> 152
~ sub_10001df04 -> sub_10001dbac : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10001f628 -> sub_10001f2c0 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10001f804 -> sub_10001f484 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000210c4 -> sub_100020cec : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10002134c -> sub_100020f5c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100022768 -> sub_100022330 : 96 -> 84
~ sub_1000232a0 -> sub_100022e5c : 172 -> 160
~ sub_10002367c -> sub_10002322c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100023768 -> sub_100023300 : 112 -> 100
~ sub_100023860 -> sub_1000233ec : 64 -> 52
~ sub_100023954 -> sub_1000234d4 : 116 -> 104
~ sub_100023b78 -> sub_1000236ec : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100024b60 -> sub_1000246c0 : 248 -> 236
~ sub_100024e9c -> sub_1000249f0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_1000255a4 -> sub_1000250f0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_1000259cc -> sub_100025500 : 64 -> 52
~ sub_100025c70 -> sub_100025798 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100026744 -> sub_100026258 : 368 -> 364
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
~ sub_10002aba0 -> sub_10002a674 : 152 -> 140
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
~ sub_10002f694 -> sub_10002f07c : 984 -> 976
~ sub_10002ff78 -> sub_10002f958 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100031b44 -> sub_100031504 : 144 -> 140
~ sub_100032354 -> sub_100031d10 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_1000334a8 -> sub_100032e40 : 60 -> 48
~ sub_100033aec -> sub_100033478 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100034c14 -> sub_100034598 : 228 -> 216
~ sub_100034eb0 -> sub_100034828 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100035588 -> sub_100034ef8 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10003579c -> sub_1000350f4 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100036378 -> sub_100035c94 : 100 -> 88
~ sub_100036d5c -> sub_10003666c : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

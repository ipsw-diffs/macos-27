## qmqpd

> `/usr/libexec/postfix/qmqpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2c4d8
+  __TEXT.__text: 0x2bec4
   __TEXT.__auth_stubs: 0xb60
   __TEXT.__cstring: 0x9ce4
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x8c0
+  __TEXT.__unwind_info: 0xba8
   __DATA_CONST.__const: 0x1730
   __DATA_CONST.__auth_got: 0x5b0
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000950 : 244 -> 232
~ _qmqpd_state_free : 132 -> 120
~ _qmqpd_peer_reset : 84 -> 72
~ sub_1000029ec -> sub_1000029c8 : 300 -> 276
~ sub_100002b18 -> sub_100002adc : 300 -> 276
~ sub_100002de0 -> sub_100002d8c : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100004168 -> sub_1000040fc : 196 -> 184
~ sub_1000043d0 -> sub_100004358 : 152 -> 140
~ sub_100004468 -> sub_1000043e4 : 152 -> 140
~ sub_100004500 -> sub_100004470 : 128 -> 116
~ sub_100004a08 -> sub_10000496c : 172 -> 160
~ sub_100004ab4 -> sub_100004a0c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100004bac -> sub_100004aec : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006f10 -> sub_100006e08 : 68 -> 56
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
~ _mail_stream_cleanup : 136 -> 124
~ sub_10000bef4 -> sub_10000bd2c : 1244 -> 1224
~ _quote_822_local_flags : 664 -> 652
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000fa7c -> sub_10000f870 : 148 -> 136
~ sub_10000fb10 -> sub_10000f8f8 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100011f84 -> sub_100011d58 : 336 -> 324
~ sub_100013240 -> sub_100013008 : 164 -> 152
~ sub_10001347c -> sub_100013238 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100014ba0 -> sub_10001494c : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100014d7c -> sub_100014b10 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001663c -> sub_100016378 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000168c4 -> sub_1000165e8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100017ce0 -> sub_1000179bc : 96 -> 84
~ sub_100018818 -> sub_1000184e8 : 172 -> 160
~ sub_100018bf4 -> sub_1000188b8 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100018ce0 -> sub_10001898c : 112 -> 100
~ sub_100018dd8 -> sub_100018a78 : 64 -> 52
~ sub_100018ecc -> sub_100018b60 : 116 -> 104
~ sub_1000190f0 -> sub_100018d78 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001a0d8 -> sub_100019d4c : 248 -> 236
~ sub_10001a414 -> sub_10001a07c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001ab1c -> sub_10001a77c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001af44 -> sub_10001ab8c : 64 -> 52
~ sub_10001b1fc -> sub_10001ae38 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001bcd0 -> sub_10001b8f8 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100020154 -> sub_10001fd40 : 152 -> 140
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
~ sub_10002367c -> sub_1000231c4 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_100024a24 -> sub_100024524 : 984 -> 976
~ sub_100025308 -> sub_100024e00 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_1000273b4 -> sub_100026e8c : 144 -> 140
~ sub_100027bc4 -> sub_100027698 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100028e34 -> sub_1000288e4 : 60 -> 48
~ sub_100029478 -> sub_100028f1c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002a5a0 -> sub_10002a03c : 228 -> 216
~ sub_10002a83c -> sub_10002a2cc : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002af14 -> sub_10002a99c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002b128 -> sub_10002ab98 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002bd04 -> sub_10002b738 : 100 -> 88
~ sub_10002c6e8 -> sub_10002c110 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

## virtual

> `/usr/libexec/postfix/virtual`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2dd70
+  __TEXT.__text: 0x2d740
   __TEXT.__auth_stubs: 0xaf0
   __TEXT.__cstring: 0x9e76
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x910
+  __TEXT.__unwind_info: 0xc00
   __DATA_CONST.__const: 0x1808
   __DATA_CONST.__auth_got: 0x578
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000ba4 : 120 -> 108
~ _deliver_maildir : 1564 -> 1552
~ _deliver_unknown : 268 -> 256
~ sub_100002b68 -> sub_100002b44 : 300 -> 276
~ sub_100002c94 -> sub_100002c58 : 300 -> 276
~ sub_100002f5c -> sub_100002f08 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_1000042e4 -> sub_100004278 : 196 -> 184
~ sub_10000454c -> sub_1000044d4 : 152 -> 140
~ sub_1000045e4 -> sub_100004560 : 152 -> 140
~ sub_10000467c -> sub_1000045ec : 128 -> 116
~ sub_100004a64 -> sub_1000049c8 : 172 -> 160
~ sub_100004b10 -> sub_100004a68 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100004c08 -> sub_100004b48 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100007898 -> sub_100007790 : 68 -> 56
~ _dsn_free : 108 -> 96
~ _dsb_free : 108 -> 96
~ _get_file_id_st : 152 -> 140
~ _log_adhoc : 1796 -> 1764
~ sub_1000099d4 -> sub_10000987c : 340 -> 328
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
~ sub_10000daf8 -> sub_10000d910 : 1244 -> 1224
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100011f7c -> sub_100011d40 : 148 -> 136
~ sub_100012010 -> sub_100011dc8 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_1000142d4 -> sub_100014078 : 336 -> 324
~ sub_100015590 -> sub_100015328 : 164 -> 152
~ sub_1000157cc -> sub_100015558 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100016ef0 -> sub_100016c6c : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_1000170cc -> sub_100016e30 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000187ac -> sub_1000184d0 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100018a34 -> sub_100018740 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100019e50 -> sub_100019b14 : 96 -> 84
~ sub_10001a988 -> sub_10001a640 : 172 -> 160
~ sub_10001ad64 -> sub_10001aa10 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001ae50 -> sub_10001aae4 : 112 -> 100
~ sub_10001af48 -> sub_10001abd0 : 64 -> 52
~ sub_10001b03c -> sub_10001acb8 : 116 -> 104
~ sub_10001b260 -> sub_10001aed0 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001c248 -> sub_10001bea4 : 248 -> 236
~ sub_10001c584 -> sub_10001c1d4 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001cc8c -> sub_10001c8d4 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001d0b4 -> sub_10001cce4 : 64 -> 52
~ sub_10001d358 -> sub_10001cf7c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001de2c -> sub_10001da3c : 368 -> 364
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
~ sub_10002212c -> sub_100021cfc : 152 -> 140
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
~ sub_1000268b8 -> sub_10002639c : 984 -> 976
~ sub_10002719c -> sub_100026c78 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100028d68 -> sub_100028824 : 144 -> 140
~ sub_100029578 -> sub_100029030 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_10002a6cc -> sub_10002a160 : 60 -> 48
~ sub_10002ad10 -> sub_10002a798 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002be38 -> sub_10002b8b8 : 228 -> 216
~ sub_10002c0d4 -> sub_10002bb48 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002c7ac -> sub_10002c218 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002c9c0 -> sub_10002c414 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002d59c -> sub_10002cfb4 : 100 -> 88
~ sub_10002df80 -> sub_10002d98c : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

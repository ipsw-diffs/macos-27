## error

> `/usr/libexec/postfix/error`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x29f8c
+  __TEXT.__text: 0x299b4
   __TEXT.__auth_stubs: 0xa50
   __TEXT.__cstring: 0x9320
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x888
+  __TEXT.__unwind_info: 0xb48
   __DATA_CONST.__const: 0x14a0
   __DATA_CONST.__auth_got: 0x528
   __DATA_CONST.__got: 0x58
Functions:
~ sub_1000008f8 : 248 -> 236
~ sub_10000171c -> sub_100001710 : 300 -> 276
~ sub_100001848 -> sub_100001824 : 300 -> 276
~ sub_100001b10 -> sub_100001ad4 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100002e98 -> sub_100002e44 : 196 -> 184
~ sub_100003100 -> sub_1000030a0 : 152 -> 140
~ sub_100003198 -> sub_10000312c : 152 -> 140
~ sub_100003230 -> sub_1000031b8 : 128 -> 116
~ sub_100003618 -> sub_100003594 : 172 -> 160
~ sub_1000036c4 -> sub_100003634 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000037bc -> sub_100003714 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000638c -> sub_10000629c : 68 -> 56
~ _dsn_free : 108 -> 96
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
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ sub_10000a9ac -> sub_10000a800 : 1244 -> 1224
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000e4b8 -> sub_10000e2c4 : 148 -> 136
~ sub_10000e54c -> sub_10000e34c : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100010810 -> sub_1000105fc : 336 -> 324
~ sub_100011acc -> sub_1000118ac : 164 -> 152
~ sub_100011d08 -> sub_100011adc : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10001342c -> sub_1000131f0 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013608 -> sub_1000133b4 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014ce8 -> sub_100014a54 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100014f70 -> sub_100014cc4 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001638c -> sub_100016098 : 96 -> 84
~ sub_100016ec4 -> sub_100016bc4 : 172 -> 160
~ sub_1000172a0 -> sub_100016f94 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001738c -> sub_100017068 : 112 -> 100
~ sub_100017484 -> sub_100017154 : 64 -> 52
~ sub_100017578 -> sub_10001723c : 116 -> 104
~ sub_10001779c -> sub_100017454 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018784 -> sub_100018428 : 248 -> 236
~ sub_100018ac0 -> sub_100018758 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_1000191c8 -> sub_100018e58 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_1000195f0 -> sub_100019268 : 64 -> 52
~ sub_100019894 -> sub_100019500 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a368 -> sub_100019fc0 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001e5c0 -> sub_10001e1dc : 152 -> 140
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
~ sub_100022ad4 -> sub_100022610 : 984 -> 976
~ sub_1000233b8 -> sub_100022eec : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100024f84 -> sub_100024a98 : 144 -> 140
~ sub_100025794 -> sub_1000252a4 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_1000268e8 -> sub_1000263d4 : 60 -> 48
~ sub_100026f2c -> sub_100026a0c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100028054 -> sub_100027b2c : 228 -> 216
~ sub_1000282f0 -> sub_100027dbc : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000289c8 -> sub_10002848c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100028bdc -> sub_100028688 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000297b8 -> sub_100029228 : 100 -> 88
~ sub_10002a19c -> sub_100029c00 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

## scache

> `/usr/libexec/postfix/scache`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x27dd0
+  __TEXT.__text: 0x27804
   __TEXT.__auth_stubs: 0xa40
   __TEXT.__cstring: 0x8e8c
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x810
+  __TEXT.__unwind_info: 0xad8
   __DATA_CONST.__const: 0x1520
   __DATA_CONST.__auth_got: 0x520
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000920 : 2036 -> 2028
~ sub_100001358 -> sub_100001350 : 84 -> 72
~ _multi_server_disconnect : 248 -> 236
~ sub_100001fd8 -> sub_100001fb8 : 260 -> 236
~ sub_1000020dc -> sub_1000020a4 : 260 -> 236
~ sub_100002328 -> sub_1000022d8 : 416 -> 392
~ sub_1000024e4 -> sub_10000247c : 268 -> 256
~ _been_here_free : 64 -> 52
~ sub_100003778 -> sub_1000036f8 : 196 -> 184
~ sub_1000039e0 -> sub_100003954 : 152 -> 140
~ sub_100003a78 -> sub_1000039e0 : 152 -> 140
~ sub_100003b10 -> sub_100003a6c : 128 -> 116
~ sub_100003ef8 -> sub_100003e48 : 172 -> 160
~ sub_100003fa4 -> sub_100003ee8 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_10000409c -> sub_100003fc8 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006254 -> sub_100006138 : 68 -> 56
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
~ sub_100009a94 -> sub_1000098e4 : 1244 -> 1224
~ sub_10000ae38 -> sub_10000ac74 : 100 -> 88
~ sub_10000aea8 -> sub_10000acd8 : 268 -> 256
~ sub_10000afc0 -> sub_10000ade4 : 212 -> 200
~ sub_10000b094 -> sub_10000aeac : 80 -> 68
~ sub_10000b0e4 -> sub_10000aef0 : 80 -> 68
~ sub_10000cc2c -> sub_10000ca2c : 148 -> 136
~ sub_10000ccc0 -> sub_10000cab4 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000ef84 -> sub_10000ed64 : 336 -> 324
~ sub_100010240 -> sub_100010014 : 164 -> 152
~ sub_10001047c -> sub_100010244 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100011ba0 -> sub_100011958 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100011d7c -> sub_100011b1c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001345c -> sub_1000131bc : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000136e4 -> sub_10001342c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100014b00 -> sub_100014800 : 96 -> 84
~ sub_100015638 -> sub_10001532c : 172 -> 160
~ sub_100015a14 -> sub_1000156fc : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100015b00 -> sub_1000157d0 : 112 -> 100
~ sub_100015bf8 -> sub_1000158bc : 64 -> 52
~ sub_100015cec -> sub_1000159a4 : 116 -> 104
~ sub_100015f10 -> sub_100015bbc : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100016ef8 -> sub_100016b90 : 248 -> 236
~ sub_100017234 -> sub_100016ec0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001793c -> sub_1000175c0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100017d64 -> sub_1000179d0 : 64 -> 52
~ sub_100017e4c -> sub_100017aac : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100018920 -> sub_10001856c : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001c9ac -> sub_10001c5bc : 152 -> 140
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
~ sub_100020aa0 -> sub_1000205e8 : 984 -> 976
~ sub_100021384 -> sub_100020ec4 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100022f50 -> sub_100022a70 : 144 -> 140
~ sub_100023760 -> sub_10002327c : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_10002472c -> sub_100024224 : 60 -> 48
~ sub_100024d70 -> sub_10002485c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100025e98 -> sub_10002597c : 228 -> 216
~ sub_100026134 -> sub_100025c0c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002680c -> sub_1000262dc : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100026a20 -> sub_1000264d8 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000275fc -> sub_100027078 : 100 -> 88
~ sub_100027fe0 -> sub_100027a50 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

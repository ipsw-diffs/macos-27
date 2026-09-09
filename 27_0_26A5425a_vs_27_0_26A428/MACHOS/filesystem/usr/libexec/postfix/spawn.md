## spawn

> `/usr/libexec/postfix/spawn`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x27dcc
+  __TEXT.__text: 0x27844
   __TEXT.__auth_stubs: 0xac0
   __TEXT.__cstring: 0x8fde
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x7f0
+  __TEXT.__unwind_info: 0xac8
   __DATA_CONST.__const: 0x14e0
   __DATA_CONST.__auth_got: 0x560
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100001800 : 300 -> 276
~ sub_10000192c -> sub_100001914 : 300 -> 276
~ sub_100001bf4 -> sub_100001bc4 : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100002f7c -> sub_100002f34 : 196 -> 184
~ sub_1000031e4 -> sub_100003190 : 152 -> 140
~ sub_10000327c -> sub_10000321c : 152 -> 140
~ sub_100003314 -> sub_1000032a8 : 128 -> 116
~ sub_1000036fc -> sub_100003684 : 172 -> 160
~ sub_1000037a8 -> sub_100003724 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000038a0 -> sub_100003804 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100005a58 -> sub_100005974 : 68 -> 56
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
~ sub_100009298 -> sub_100009120 : 1244 -> 1224
~ sub_10000bbf0 -> sub_10000ba64 : 148 -> 136
~ sub_10000bc84 -> sub_10000baec : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000e03c -> sub_10000de90 : 336 -> 324
~ sub_10000f2f8 -> sub_10000f140 : 164 -> 152
~ sub_10000f534 -> sub_10000f370 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100010c58 -> sub_100010a84 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100010e34 -> sub_100010c48 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000126f4 -> sub_1000124b0 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10001297c -> sub_100012720 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100013d98 -> sub_100013af4 : 96 -> 84
~ sub_1000148d0 -> sub_100014620 : 172 -> 160
~ sub_100014cac -> sub_1000149f0 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100014d98 -> sub_100014ac4 : 112 -> 100
~ sub_100014e90 -> sub_100014bb0 : 64 -> 52
~ sub_100014f84 -> sub_100014c98 : 116 -> 104
~ sub_1000151a8 -> sub_100014eb0 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100016190 -> sub_100015e84 : 248 -> 236
~ sub_1000164cc -> sub_1000161b4 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100016bd4 -> sub_1000168b4 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100016ffc -> sub_100016cc4 : 64 -> 52
~ sub_1000170e4 -> sub_100016da0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100017bb8 -> sub_100017860 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001bd28 -> sub_10001b994 : 152 -> 140
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
~ sub_100020914 -> sub_1000204a0 : 984 -> 976
~ sub_1000211f8 -> sub_100020d7c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100022dc4 -> sub_100022928 : 144 -> 140
~ sub_1000235d4 -> sub_100023134 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100024728 -> sub_100024264 : 60 -> 48
~ sub_100024d6c -> sub_10002489c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100025e94 -> sub_1000259bc : 228 -> 216
~ sub_100026130 -> sub_100025c4c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100026808 -> sub_10002631c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100026a1c -> sub_100026518 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000275f8 -> sub_1000270b8 : 100 -> 88
~ sub_100027fdc -> sub_100027a90 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

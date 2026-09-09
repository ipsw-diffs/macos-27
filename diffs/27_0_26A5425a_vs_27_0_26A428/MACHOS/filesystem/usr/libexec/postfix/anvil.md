## anvil

> `/usr/libexec/postfix/anvil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2895c
+  __TEXT.__text: 0x283bc
   __TEXT.__auth_stubs: 0xa30
   __TEXT.__cstring: 0x8ddf
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x810
+  __TEXT.__unwind_info: 0xae0
   __DATA_CONST.__const: 0x1590
   __DATA_CONST.__auth_got: 0x518
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000934 : 416 -> 404
~ sub_100000b4c -> sub_100000b40 : 212 -> 200
~ sub_100001a58 -> sub_100001a40 : 84 -> 72
~ _multi_server_disconnect : 248 -> 236
~ sub_1000026d8 -> sub_1000026a8 : 260 -> 236
~ sub_1000027dc -> sub_100002794 : 260 -> 236
~ sub_100002a28 -> sub_1000029c8 : 416 -> 392
~ sub_100002be4 -> sub_100002b6c : 268 -> 256
~ _been_here_free : 64 -> 52
~ sub_100003e78 -> sub_100003de8 : 196 -> 184
~ sub_1000040e0 -> sub_100004044 : 152 -> 140
~ sub_100004178 -> sub_1000040d0 : 152 -> 140
~ sub_100004210 -> sub_10000415c : 128 -> 116
~ sub_1000045f8 -> sub_100004538 : 172 -> 160
~ sub_1000046a4 -> sub_1000045d8 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_10000479c -> sub_1000046b8 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100006954 -> sub_100006828 : 68 -> 56
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
~ sub_10000a194 -> sub_100009fd4 : 1244 -> 1224
~ sub_10000caec -> sub_10000c918 : 148 -> 136
~ sub_10000cb80 -> sub_10000c9a0 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10000ee44 -> sub_10000ec50 : 336 -> 324
~ sub_100010100 -> sub_10000ff00 : 164 -> 152
~ sub_10001033c -> sub_100010130 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100012874 -> sub_100012658 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100012a50 -> sub_10001281c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014130 -> sub_100013ebc : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000143b8 -> sub_10001412c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000157d4 -> sub_100015500 : 96 -> 84
~ sub_10001630c -> sub_10001602c : 172 -> 160
~ sub_1000166e8 -> sub_1000163fc : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000167d4 -> sub_1000164d0 : 112 -> 100
~ sub_1000168cc -> sub_1000165bc : 64 -> 52
~ sub_1000169c0 -> sub_1000166a4 : 116 -> 104
~ sub_100016be4 -> sub_1000168bc : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100017bcc -> sub_100017890 : 248 -> 236
~ sub_100017f08 -> sub_100017bc0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100018610 -> sub_1000182c0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100018a38 -> sub_1000186d0 : 64 -> 52
~ sub_100018b20 -> sub_1000187ac : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_1000195f4 -> sub_10001926c : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001d680 -> sub_10001d2bc : 152 -> 140
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
~ sub_10002166c -> sub_1000211e0 : 984 -> 976
~ sub_100021f50 -> sub_100021abc : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100023b1c -> sub_100023668 : 144 -> 140
~ sub_10002432c -> sub_100023e74 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_1000252b8 -> sub_100024ddc : 60 -> 48
~ sub_1000258fc -> sub_100025414 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100026a24 -> sub_100026534 : 228 -> 216
~ sub_100026cc0 -> sub_1000267c4 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100027398 -> sub_100026e94 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000275ac -> sub_100027090 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100028188 -> sub_100027c30 : 100 -> 88
~ sub_100028b6c -> sub_100028608 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

## trivial-rewrite

> `/usr/libexec/postfix/trivial-rewrite`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2a9a8
+  __TEXT.__text: 0x2a39c
   __TEXT.__auth_stubs: 0xa20
   __TEXT.__cstring: 0x93ba
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x858
+  __TEXT.__unwind_info: 0xb30
   __DATA_CONST.__const: 0x18c8
   __DATA_CONST.__auth_got: 0x510
   __DATA_CONST.__got: 0x58
Functions:
~ sub_10000093c : 288 -> 276
~ sub_100000ba0 -> sub_100000b94 : 68 -> 56
~ sub_100000be4 -> sub_100000bcc : 100 -> 88
~ _rewrite_tree : 912 -> 888
~ _transport_post_init : 72 -> 60
~ _transport_free : 88 -> 76
~ sub_100002560 -> sub_10000250c : 120 -> 108
~ sub_1000025d8 -> sub_100002578 : 188 -> 176
~ _multi_server_disconnect : 248 -> 236
~ sub_1000032c0 -> sub_100003248 : 260 -> 236
~ sub_1000033c4 -> sub_100003334 : 260 -> 236
~ sub_100003610 -> sub_100003568 : 416 -> 392
~ sub_1000037cc -> sub_10000370c : 268 -> 256
~ _been_here_free : 64 -> 52
~ sub_100004a60 -> sub_100004988 : 196 -> 184
~ sub_100004cc8 -> sub_100004be4 : 152 -> 140
~ sub_100004d60 -> sub_100004c70 : 152 -> 140
~ sub_100004df8 -> sub_100004cfc : 128 -> 116
~ sub_1000051e0 -> sub_1000050d8 : 172 -> 160
~ sub_10000528c -> sub_100005178 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100005384 -> sub_100005258 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000753c -> sub_1000073c8 : 68 -> 56
~ _log_adhoc : 1796 -> 1764
~ sub_1000088d8 -> sub_100008738 : 340 -> 328
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
~ sub_10000b400 -> sub_10000b1ec : 1244 -> 1224
~ _quote_822_local_flags : 664 -> 652
~ sub_10000d0dc -> sub_10000cea8 : 316 -> 304
~ sub_10000f94c -> sub_10000f70c : 148 -> 136
~ sub_10000f9e0 -> sub_10000f794 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100011ca4 -> sub_100011a44 : 336 -> 324
~ sub_100012f60 -> sub_100012cf4 : 164 -> 152
~ sub_10001319c -> sub_100012f24 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000148c0 -> sub_100014638 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100014a9c -> sub_1000147fc : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001617c -> sub_100015e9c : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100016404 -> sub_10001610c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100017820 -> sub_1000174e0 : 96 -> 84
~ sub_100018358 -> sub_10001800c : 172 -> 160
~ sub_100018734 -> sub_1000183dc : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100018820 -> sub_1000184b0 : 112 -> 100
~ sub_100018918 -> sub_10001859c : 64 -> 52
~ sub_100018a0c -> sub_100018684 : 116 -> 104
~ sub_100018c30 -> sub_10001889c : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100019c18 -> sub_100019870 : 248 -> 236
~ sub_100019f54 -> sub_100019ba0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001a65c -> sub_10001a2a0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001aa84 -> sub_10001a6b0 : 64 -> 52
~ sub_10001ab6c -> sub_10001a78c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001b640 -> sub_10001b24c : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001f6cc -> sub_10001f29c : 152 -> 140
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
~ sub_1000236b8 -> sub_1000231c0 : 984 -> 976
~ sub_100023f9c -> sub_100023a9c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100025b68 -> sub_100025648 : 144 -> 140
~ sub_100026378 -> sub_100025e54 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100027304 -> sub_100026dbc : 60 -> 48
~ sub_100027948 -> sub_1000273f4 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100028a70 -> sub_100028514 : 228 -> 216
~ sub_100028d0c -> sub_1000287a4 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000293e4 -> sub_100028e74 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000295f8 -> sub_100029070 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002a1d4 -> sub_100029c10 : 100 -> 88
~ sub_10002abb8 -> sub_10002a5e8 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

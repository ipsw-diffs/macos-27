## postalias

> `/usr/sbin/postalias`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x23dac
+  __TEXT.__text: 0x238b0
   __TEXT.__auth_stubs: 0x930
   __TEXT.__cstring: 0x7f1d
   __TEXT.__const: 0x142
-  __TEXT.__unwind_info: 0x740
+  __TEXT.__unwind_info: 0x9b8
   __DATA_CONST.__const: 0x14e0
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x50
Functions:
~ _been_here_free : 64 -> 52
~ sub_100001e3c -> sub_100001e30 : 196 -> 184
~ sub_1000020a4 -> sub_10000208c : 152 -> 140
~ sub_10000213c -> sub_100002118 : 152 -> 140
~ sub_1000021d4 -> sub_1000021a4 : 128 -> 116
~ sub_1000025bc -> sub_100002580 : 172 -> 160
~ sub_100002668 -> sub_100002620 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100002760 -> sub_100002700 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _dict_proxy_open : 1024 -> 1012
~ sub_100004298 -> sub_1000041fc : 68 -> 56
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_100006650 -> sub_100006558 : 96 -> 84
~ _mkmap_close : 92 -> 80
~ sub_100006a20 -> sub_100006910 : 1244 -> 1224
~ _quote_822_local_flags : 664 -> 652
~ sub_1000082a8 -> sub_100008178 : 316 -> 304
~ sub_100009ed4 -> sub_100009d98 : 148 -> 136
~ sub_100009f68 -> sub_100009e20 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ sub_10000c048 -> sub_10000bef8 : 336 -> 324
~ sub_10000d304 -> sub_10000d1a8 : 164 -> 152
~ sub_10000d540 -> sub_10000d3d8 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10000ec64 -> sub_10000eaec : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000ee40 -> sub_10000ecb0 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100010598 -> sub_1000103b0 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100010820 -> sub_100010620 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100011c3c -> sub_1000119f4 : 96 -> 84
~ sub_100012774 -> sub_100012520 : 172 -> 160
~ sub_100012b50 -> sub_1000128f0 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100012c3c -> sub_1000129c4 : 112 -> 100
~ sub_100012d34 -> sub_100012ab0 : 64 -> 52
~ sub_100012e28 -> sub_100012b98 : 116 -> 104
~ sub_10001304c -> sub_100012db0 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100014034 -> sub_100013d84 : 248 -> 236
~ sub_100014370 -> sub_1000140b4 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100014a78 -> sub_1000147b4 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100014ea0 -> sub_100014bc4 : 64 -> 52
~ sub_100014f88 -> sub_100014ca0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100015a5c -> sub_100015760 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100019760 -> sub_100019428 : 152 -> 140
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
~ sub_10001d56c -> sub_10001d16c : 984 -> 976
~ sub_10001de50 -> sub_10001da48 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10001fa1c -> sub_10001f5f4 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_1000209f4 -> sub_1000205bc : 60 -> 48
~ sub_100021038 -> sub_100020bf4 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100021e74 -> sub_100021a28 : 228 -> 216
~ sub_100022110 -> sub_100021cb8 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000227e8 -> sub_100022388 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000229fc -> sub_100022584 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000235d8 -> sub_100023124 : 100 -> 88
~ sub_100023fbc -> sub_100023afc : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

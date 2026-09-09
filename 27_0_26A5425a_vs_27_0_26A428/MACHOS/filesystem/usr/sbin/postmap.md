## postmap

> `/usr/sbin/postmap`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x241e8
+  __TEXT.__text: 0x23cc8
   __TEXT.__auth_stubs: 0x930
   __TEXT.__cstring: 0x836e
   __TEXT.__const: 0x192
-  __TEXT.__unwind_info: 0x720
+  __TEXT.__unwind_info: 0x9a0
   __DATA_CONST.__const: 0x15d0
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x50
Functions:
~ _been_here_free : 64 -> 52
~ sub_1000021c0 -> sub_1000021b4 : 196 -> 184
~ sub_100002428 -> sub_100002410 : 152 -> 140
~ sub_1000024c0 -> sub_10000249c : 152 -> 140
~ sub_100002558 -> sub_100002528 : 128 -> 116
~ sub_100002940 -> sub_100002904 : 172 -> 160
~ sub_1000029ec -> sub_1000029a4 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100002ae4 -> sub_100002a84 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000461c -> sub_100004580 : 68 -> 56
~ _header_opts_find : 796 -> 788
~ _header_token : 1208 -> 1172
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_100007124 -> sub_100007000 : 144 -> 132
~ _mime_state_update : 4064 -> 4060
~ sub_100008488 -> sub_100008354 : 96 -> 84
~ _mkmap_close : 92 -> 80
~ sub_100008858 -> sub_10000870c : 1244 -> 1224
~ sub_10000a310 -> sub_10000a1b0 : 148 -> 136
~ sub_10000a3a4 -> sub_10000a238 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ sub_10000c484 -> sub_10000c310 : 336 -> 324
~ sub_10000d740 -> sub_10000d5c0 : 164 -> 152
~ sub_10000d97c -> sub_10000d7f0 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10000f0a0 -> sub_10000ef04 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000f27c -> sub_10000f0c8 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_1000109d4 -> sub_1000107c8 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100010c5c -> sub_100010a38 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100012078 -> sub_100011e0c : 96 -> 84
~ sub_100012bb0 -> sub_100012938 : 172 -> 160
~ sub_100012f8c -> sub_100012d08 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100013078 -> sub_100012ddc : 112 -> 100
~ sub_100013170 -> sub_100012ec8 : 64 -> 52
~ sub_100013264 -> sub_100012fb0 : 116 -> 104
~ sub_100013488 -> sub_1000131c8 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100014470 -> sub_10001419c : 248 -> 236
~ sub_1000147ac -> sub_1000144cc : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100014eb4 -> sub_100014bcc : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_1000152dc -> sub_100014fdc : 64 -> 52
~ sub_1000153c4 -> sub_1000150b8 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100015e98 -> sub_100015b78 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100019b9c -> sub_100019840 : 152 -> 140
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
~ sub_10001d9a8 -> sub_10001d584 : 984 -> 976
~ sub_10001e28c -> sub_10001de60 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10001fe58 -> sub_10001fa0c : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100020e30 -> sub_1000209d4 : 60 -> 48
~ sub_100021474 -> sub_10002100c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000222b0 -> sub_100021e40 : 228 -> 216
~ sub_10002254c -> sub_1000220d0 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100022c24 -> sub_1000227a0 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100022e38 -> sub_10002299c : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100023a14 -> sub_10002353c : 100 -> 88
~ sub_1000243f8 -> sub_100023f14 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

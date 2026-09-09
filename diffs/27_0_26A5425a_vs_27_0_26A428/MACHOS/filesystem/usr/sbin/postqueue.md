## postqueue

> `/usr/sbin/postqueue`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2532c
+  __TEXT.__text: 0x24de8
   __TEXT.__auth_stubs: 0xa40
   __TEXT.__cstring: 0x8868
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x778
+  __TEXT.__unwind_info: 0xa08
   __DATA_CONST.__const: 0x1500
   __DATA_CONST.__auth_got: 0x520
   __DATA_CONST.__got: 0x50
Functions:
~ sub_100000cc4 : 708 -> 684
~ sub_10000113c -> sub_100001124 : 176 -> 164
~ sub_100001934 -> sub_100001910 : 828 -> 832
~ _been_here_free : 64 -> 52
~ sub_1000020c0 -> sub_100002094 : 196 -> 184
~ sub_100002328 -> sub_1000022f0 : 152 -> 140
~ sub_1000023c0 -> sub_10000237c : 152 -> 140
~ sub_100002458 -> sub_100002408 : 128 -> 116
~ sub_100002840 -> sub_1000027e4 : 172 -> 160
~ sub_1000028ec -> sub_100002884 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000029e4 -> sub_100002964 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000451c -> sub_100004460 : 68 -> 56
~ _get_file_id_st : 152 -> 140
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ sub_100007860 -> sub_10000772c : 1244 -> 1224
~ _mypwfree : 220 -> 208
~ _REMOVE : 272 -> 260
~ sub_100009fb4 -> sub_100009e54 : 148 -> 136
~ sub_10000a048 -> sub_100009edc : 464 -> 468
~ _mail_version_free : 60 -> 48
~ sub_10000c0f8 -> sub_10000bf84 : 336 -> 324
~ sub_10000d3b4 -> sub_10000d234 : 164 -> 152
~ sub_10000d5f0 -> sub_10000d464 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10000ed14 -> sub_10000eb78 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000eef0 -> sub_10000ed3c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100010648 -> sub_10001043c : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000108d0 -> sub_1000106ac : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100011cec -> sub_100011a80 : 96 -> 84
~ sub_100012824 -> sub_1000125ac : 172 -> 160
~ sub_100012c00 -> sub_10001297c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100012cec -> sub_100012a50 : 112 -> 100
~ sub_100012de4 -> sub_100012b3c : 64 -> 52
~ sub_100012ed8 -> sub_100012c24 : 116 -> 104
~ sub_1000130fc -> sub_100012e3c : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000140e4 -> sub_100013e10 : 248 -> 236
~ sub_100014420 -> sub_100014140 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100014b28 -> sub_100014840 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100014f50 -> sub_100014c50 : 64 -> 52
~ sub_100015208 -> sub_100014efc : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100015cdc -> sub_1000159bc : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100019dd8 -> sub_100019a7c : 152 -> 140
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
~ sub_10001cf6c -> sub_10001cb6c : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_10001e314 -> sub_10001decc : 984 -> 976
~ sub_10001ebf8 -> sub_10001e7a8 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100020ca4 -> sub_100020834 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100021f60 -> sub_100021ae0 : 60 -> 48
~ sub_1000225a4 -> sub_100022118 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000233e0 -> sub_100022f4c : 228 -> 216
~ sub_10002367c -> sub_1000231dc : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100023d54 -> sub_1000238ac : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100023f68 -> sub_100023aa8 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100024b44 -> sub_100024648 : 100 -> 88
~ sub_100025528 -> sub_100025020 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

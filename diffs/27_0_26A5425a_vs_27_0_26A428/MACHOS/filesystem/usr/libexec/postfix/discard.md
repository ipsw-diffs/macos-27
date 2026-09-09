## discard

> `/usr/libexec/postfix/discard`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2a108
+  __TEXT.__text: 0x29b3c
   __TEXT.__auth_stubs: 0xa50
   __TEXT.__cstring: 0x9353
   __TEXT.__const: 0x1d2
-  __TEXT.__unwind_info: 0x888
+  __TEXT.__unwind_info: 0xb48
   __DATA_CONST.__const: 0x14a0
   __DATA_CONST.__auth_got: 0x528
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100001658 : 300 -> 276
~ sub_100001784 -> sub_10000176c : 300 -> 276
~ sub_100001a4c -> sub_100001a1c : 512 -> 500
~ _been_here_free : 64 -> 52
~ sub_100002dd4 -> sub_100002d8c : 196 -> 184
~ sub_10000303c -> sub_100002fe8 : 152 -> 140
~ sub_1000030d4 -> sub_100003074 : 152 -> 140
~ sub_10000316c -> sub_100003100 : 128 -> 116
~ sub_100003554 -> sub_1000034dc : 172 -> 160
~ sub_100003600 -> sub_10000357c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_1000036f8 -> sub_10000365c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_1000062c8 -> sub_1000061e4 : 68 -> 56
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
~ sub_10000a8e8 -> sub_10000a748 : 1244 -> 1224
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000e634 -> sub_10000e44c : 148 -> 136
~ sub_10000e6c8 -> sub_10000e4d4 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10001098c -> sub_100010784 : 336 -> 324
~ sub_100011c48 -> sub_100011a34 : 164 -> 152
~ sub_100011e84 -> sub_100011c64 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000135a8 -> sub_100013378 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013784 -> sub_10001353c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100014e64 -> sub_100014bdc : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000150ec -> sub_100014e4c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100016508 -> sub_100016220 : 96 -> 84
~ sub_100017040 -> sub_100016d4c : 172 -> 160
~ sub_10001741c -> sub_10001711c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100017508 -> sub_1000171f0 : 112 -> 100
~ sub_100017600 -> sub_1000172dc : 64 -> 52
~ sub_1000176f4 -> sub_1000173c4 : 116 -> 104
~ sub_100017918 -> sub_1000175dc : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018900 -> sub_1000185b0 : 248 -> 236
~ sub_100018c3c -> sub_1000188e0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100019344 -> sub_100018fe0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001976c -> sub_1000193f0 : 64 -> 52
~ sub_100019a10 -> sub_100019688 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a4e4 -> sub_10001a148 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001e73c -> sub_10001e364 : 152 -> 140
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
~ sub_100022c50 -> sub_100022798 : 984 -> 976
~ sub_100023534 -> sub_100023074 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100025100 -> sub_100024c20 : 144 -> 140
~ sub_100025910 -> sub_10002542c : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100026a64 -> sub_10002655c : 60 -> 48
~ sub_1000270a8 -> sub_100026b94 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000281d0 -> sub_100027cb4 : 228 -> 216
~ sub_10002846c -> sub_100027f44 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100028b44 -> sub_100028614 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100028d58 -> sub_100028810 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100029934 -> sub_1000293b0 : 100 -> 88
~ sub_10002a318 -> sub_100029d88 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

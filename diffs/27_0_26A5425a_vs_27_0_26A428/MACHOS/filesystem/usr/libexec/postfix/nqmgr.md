## nqmgr

> `/usr/libexec/postfix/nqmgr`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x326a8
+  __TEXT.__text: 0x31f0c
   __TEXT.__auth_stubs: 0xab0
   __TEXT.__cstring: 0xb1fc
   __TEXT.__const: 0x1e2
-  __TEXT.__unwind_info: 0x9e0
+  __TEXT.__unwind_info: 0xd20
   __DATA_CONST.__const: 0x19b8
   __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000988 : 416 -> 408
~ sub_100000b2c -> sub_100000b24 : 464 -> 452
~ sub_100000ea0 -> sub_100000e8c : 96 -> 84
~ sub_1000015d0 -> sub_1000015b0 : 88 -> 76
~ sub_100001628 -> sub_1000015fc : 376 -> 364
~ sub_1000017ac -> sub_100001774 : 64 -> 52
~ sub_1000017ec -> sub_1000017a8 : 280 -> 260
~ _qmgr_transport_throttle : 252 -> 240
~ _qmgr_transport_select : 224 -> 220
~ _qmgr_transport_alloc : 364 -> 352
~ sub_100001d10 -> sub_100001c9c : 272 -> 248
~ sub_100002240 -> sub_1000021b4 : 64 -> 52
~ _qmgr_queue_suspend : 204 -> 192
~ sub_10000234c -> sub_1000022a8 : 172 -> 148
~ sub_1000026e8 -> sub_10000262c : 100 -> 88
~ _qmgr_queue_done : 380 -> 368
~ _qmgr_entry_move_todo : 284 -> 272
~ _qmgr_entry_done : 796 -> 784
~ _qmgr_message_free : 392 -> 380
~ sub_100003b60 -> sub_100003a68 : 3796 -> 3788
~ sub_100004a34 -> sub_100004934 : 212 -> 200
~ sub_1000055c0 -> sub_1000054b4 : 300 -> 288
~ sub_1000056ec -> sub_1000055d4 : 172 -> 160
~ _qmgr_job_move_limits : 156 -> 152
~ _qmgr_job_free : 304 -> 292
~ sub_100006ccc -> sub_100006b98 : 128 -> 116
~ _qmgr_peer_free : 196 -> 184
~ _qmgr_peer_obtain : 88 -> 76
~ _qmgr_enable_queue : 164 -> 152
~ _qmgr_scan_request : 148 -> 136
~ _qmgr_scan_next : 200 -> 188
~ sub_100008550 -> sub_1000083d4 : 436 -> 412
~ sub_100008704 -> sub_100008570 : 176 -> 164
~ sub_1000087b4 -> sub_100008614 : 436 -> 412
~ sub_100008e9c -> sub_100008ce4 : 476 -> 452
~ sub_10000913c -> sub_100008f6c : 456 -> 432
~ sub_1000094c0 -> sub_1000092d8 : 180 -> 168
~ _been_here_free : 64 -> 52
~ sub_10000a418 -> sub_10000a218 : 196 -> 184
~ sub_10000a680 -> sub_10000a474 : 152 -> 140
~ sub_10000a718 -> sub_10000a500 : 152 -> 140
~ sub_10000a7b0 -> sub_10000a58c : 128 -> 116
~ sub_10000ab98 -> sub_10000a968 : 172 -> 160
~ sub_10000ac44 -> sub_10000aa08 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_10000ad3c -> sub_10000aae8 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000cf84 -> sub_10000cce8 : 68 -> 56
~ _dsn_free : 108 -> 96
~ _dsb_free : 108 -> 96
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
~ sub_100011f10 -> sub_100011bac : 1244 -> 1224
~ _vopened : 200 -> 188
~ _quote_822_local_flags : 664 -> 652
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100016b80 -> sub_1000167c8 : 148 -> 136
~ sub_100016c14 -> sub_100016850 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100018ed8 -> sub_100018b00 : 336 -> 324
~ sub_10001a194 -> sub_100019db0 : 164 -> 152
~ sub_10001a3d0 -> sub_100019fe0 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10001baf4 -> sub_10001b6f4 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10001bcd0 -> sub_10001b8b8 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001d3b0 -> sub_10001cf58 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10001d638 -> sub_10001d1c8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001ea54 -> sub_10001e59c : 96 -> 84
~ sub_10001f58c -> sub_10001f0c8 : 172 -> 160
~ sub_10001f968 -> sub_10001f498 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001fa54 -> sub_10001f56c : 112 -> 100
~ sub_10001fb4c -> sub_10001f658 : 64 -> 52
~ sub_10001fc40 -> sub_10001f740 : 116 -> 104
~ sub_10001fe64 -> sub_10001f958 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100020e4c -> sub_10002092c : 248 -> 236
~ sub_100021188 -> sub_100020c5c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100021890 -> sub_10002135c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100021cb8 -> sub_10002176c : 64 -> 52
~ sub_100021f5c -> sub_100021a04 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100022a30 -> sub_1000224c4 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100026900 -> sub_100026358 : 152 -> 140
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
~ sub_10002b1f0 -> sub_10002ab68 : 984 -> 976
~ sub_10002bad4 -> sub_10002b444 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10002d6a0 -> sub_10002cff0 : 144 -> 140
~ sub_10002deb0 -> sub_10002d7fc : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_10002f004 -> sub_10002e92c : 60 -> 48
~ sub_10002f648 -> sub_10002ef64 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100030770 -> sub_100030084 : 228 -> 216
~ sub_100030a0c -> sub_100030314 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000310e4 -> sub_1000309e4 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000312f8 -> sub_100030be0 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100031ed4 -> sub_100031780 : 100 -> 88
~ sub_1000328b8 -> sub_100032158 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

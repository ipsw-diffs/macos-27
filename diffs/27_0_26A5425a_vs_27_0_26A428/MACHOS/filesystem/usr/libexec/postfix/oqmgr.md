## oqmgr

> `/usr/libexec/postfix/oqmgr`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x312d4
+  __TEXT.__text: 0x30b74
   __TEXT.__auth_stubs: 0xab0
   __TEXT.__cstring: 0xad24
   __TEXT.__const: 0x1e2
-  __TEXT.__unwind_info: 0x9b8
+  __TEXT.__unwind_info: 0xcf8
   __DATA_CONST.__const: 0x18b8
   __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0x58
Functions:
~ sub_100000988 : 416 -> 408
~ sub_100000b2c -> sub_100000b24 : 376 -> 364
~ sub_100000e88 -> sub_100000e74 : 96 -> 84
~ sub_1000015b8 -> sub_100001598 : 88 -> 76
~ sub_100001610 -> sub_1000015e4 : 376 -> 364
~ sub_100001794 -> sub_10000175c : 64 -> 52
~ sub_1000017d4 -> sub_100001790 : 280 -> 260
~ _qmgr_transport_throttle : 252 -> 240
~ _qmgr_transport_select : 232 -> 228
~ _qmgr_transport_alloc : 364 -> 352
~ sub_100001d00 -> sub_100001c8c : 272 -> 248
~ sub_1000020c0 -> sub_100002034 : 64 -> 52
~ _qmgr_queue_suspend : 204 -> 192
~ sub_1000021cc -> sub_100002128 : 156 -> 144
~ sub_100002558 -> sub_1000024a8 : 100 -> 88
~ _qmgr_queue_done : 380 -> 368
~ _qmgr_entry_move_todo : 204 -> 192
~ _qmgr_entry_done : 652 -> 640
~ _qmgr_message_free : 380 -> 368
~ sub_1000046a0 -> sub_1000045b4 : 212 -> 200
~ sub_100004d7c -> sub_100004c84 : 240 -> 228
~ sub_10000515c -> sub_100005058 : 312 -> 300
~ sub_100005294 -> sub_100005184 : 172 -> 160
~ _qmgr_enable_queue : 164 -> 152
~ _qmgr_scan_request : 148 -> 136
~ _qmgr_scan_next : 200 -> 188
~ sub_100007268 -> sub_100007128 : 436 -> 412
~ sub_10000741c -> sub_1000072c4 : 176 -> 164
~ sub_1000074cc -> sub_100007368 : 436 -> 412
~ sub_100007bb4 -> sub_100007a38 : 476 -> 452
~ sub_100007e54 -> sub_100007cc0 : 456 -> 432
~ sub_1000081d8 -> sub_10000802c : 180 -> 168
~ _been_here_free : 64 -> 52
~ sub_100009130 -> sub_100008f6c : 196 -> 184
~ sub_100009398 -> sub_1000091c8 : 152 -> 140
~ sub_100009430 -> sub_100009254 : 152 -> 140
~ sub_1000094c8 -> sub_1000092e0 : 128 -> 116
~ sub_1000098b0 -> sub_1000096bc : 172 -> 160
~ sub_10000995c -> sub_10000975c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100009a54 -> sub_10000983c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000bc9c -> sub_10000ba3c : 68 -> 56
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
~ sub_100010c28 -> sub_100010900 : 1244 -> 1224
~ _vopened : 200 -> 188
~ _quote_822_local_flags : 664 -> 652
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100015898 -> sub_10001551c : 148 -> 136
~ sub_10001592c -> sub_1000155a4 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100017bf0 -> sub_100017854 : 336 -> 324
~ sub_100018eac -> sub_100018b04 : 164 -> 152
~ sub_1000190e8 -> sub_100018d34 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10001a80c -> sub_10001a448 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10001a9e8 -> sub_10001a60c : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001c0c8 -> sub_10001bcac : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10001c350 -> sub_10001bf1c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001d76c -> sub_10001d2f0 : 96 -> 84
~ sub_10001e2a4 -> sub_10001de1c : 172 -> 160
~ sub_10001e680 -> sub_10001e1ec : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001e76c -> sub_10001e2c0 : 112 -> 100
~ sub_10001e864 -> sub_10001e3ac : 64 -> 52
~ sub_10001e958 -> sub_10001e494 : 116 -> 104
~ sub_10001eb7c -> sub_10001e6ac : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001fb64 -> sub_10001f680 : 248 -> 236
~ sub_10001fea0 -> sub_10001f9b0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_1000205a8 -> sub_1000200b0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_1000209d0 -> sub_1000204c0 : 64 -> 52
~ sub_100020c74 -> sub_100020758 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100021748 -> sub_100021218 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100025618 -> sub_1000250ac : 152 -> 140
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
~ sub_100029e1c -> sub_1000297d0 : 984 -> 976
~ sub_10002a700 -> sub_10002a0ac : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10002c2cc -> sub_10002bc58 : 144 -> 140
~ sub_10002cadc -> sub_10002c464 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_10002dc30 -> sub_10002d594 : 60 -> 48
~ sub_10002e274 -> sub_10002dbcc : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002f39c -> sub_10002ecec : 228 -> 216
~ sub_10002f638 -> sub_10002ef7c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002fd10 -> sub_10002f64c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002ff24 -> sub_10002f848 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100030b00 -> sub_1000303e8 : 100 -> 88
~ sub_1000314e4 -> sub_100030dc0 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

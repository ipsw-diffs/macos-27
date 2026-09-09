## tlsproxy

> `/usr/libexec/postfix/tlsproxy`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2df4c
+  __TEXT.__text: 0x2d87c
   __TEXT.__auth_stubs: 0x1180
   __TEXT.__cstring: 0xb307
   __TEXT.__const: 0x1e2
-  __TEXT.__unwind_info: 0x910
+  __TEXT.__unwind_info: 0xc30
   __DATA_CONST.__const: 0x2330
   __DATA_CONST.__auth_got: 0x8c0
   __DATA_CONST.__got: 0x80
Functions:
~ sub_100000990 : 204 -> 192
~ sub_1000010d0 -> sub_1000010c4 : 676 -> 664
~ sub_100001374 -> sub_10000135c : 184 -> 160
~ sub_10000142c -> sub_1000013fc : 104 -> 92
~ sub_100001494 -> sub_100001458 : 784 -> 724
~ _tlsp_state_free : 180 -> 168
~ _event_server_disconnect : 240 -> 228
~ sub_100002944 -> sub_1000028b4 : 260 -> 236
~ sub_100002a48 -> sub_1000029a0 : 260 -> 236
~ sub_100002c68 -> sub_100002ba8 : 104 -> 92
~ sub_100002cd0 -> sub_100002c04 : 396 -> 372
~ sub_100002e5c -> sub_100002d78 : 216 -> 204
~ _tls_pkey_fprint : 268 -> 256
~ sub_100003710 -> sub_100003614 : 184 -> 176
~ sub_1000037c8 -> sub_1000036c4 : 200 -> 192
~ _tls_param_init : 92 -> 80
~ _tls_free_app_context : 112 -> 100
~ _tls_free_context : 204 -> 192
~ sub_100004644 -> sub_100004514 : 632 -> 624
~ _tls_set_dh_from_file : 244 -> 232
~ _tls_peer_CN : 96 -> 84
~ sub_1000051d8 -> sub_100005088 : 480 -> 484
~ _tls_issuer_CN : 128 -> 116
~ _tls_session_stop : 216 -> 204
~ _tls_scache_close : 124 -> 112
~ _tls_int_seed : 92 -> 80
~ _been_here_free : 64 -> 52
~ sub_100008514 -> sub_10000838c : 196 -> 184
~ sub_10000877c -> sub_1000085e8 : 152 -> 140
~ sub_100008814 -> sub_100008674 : 152 -> 140
~ sub_1000088ac -> sub_100008700 : 128 -> 116
~ sub_100008c94 -> sub_100008adc : 172 -> 160
~ sub_100008d40 -> sub_100008b7c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100008e38 -> sub_100008c5c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000aff0 -> sub_10000adcc : 68 -> 56
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
~ sub_10000e830 -> sub_10000e578 : 1244 -> 1224
~ sub_100011188 -> sub_100010ebc : 148 -> 136
~ sub_10001121c -> sub_100010f44 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_1000134e0 -> sub_1000131f4 : 336 -> 324
~ sub_10001479c -> sub_1000144a4 : 164 -> 152
~ sub_1000149d8 -> sub_1000146d4 : 220 -> 224
~ _allprint : 60 -> 64
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ _attr_clnt_free : 60 -> 48
~ sub_100017400 -> sub_1000170e4 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_1000175dc -> sub_1000172a8 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100018cbc -> sub_100018948 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100018f44 -> sub_100018bb8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001a360 -> sub_100019f8c : 96 -> 84
~ sub_10001ae98 -> sub_10001aab8 : 172 -> 160
~ sub_10001b274 -> sub_10001ae88 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001b360 -> sub_10001af5c : 112 -> 100
~ sub_10001b458 -> sub_10001b048 : 64 -> 52
~ sub_10001b54c -> sub_10001b130 : 116 -> 104
~ sub_10001b770 -> sub_10001b348 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001c758 -> sub_10001c31c : 248 -> 236
~ sub_10001ca94 -> sub_10001c64c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001d19c -> sub_10001cd4c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001d5c4 -> sub_10001d15c : 64 -> 52
~ sub_10001d73c -> sub_10001d2c8 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001e210 -> sub_10001dd88 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_1000224d0 -> sub_10002200c : 152 -> 140
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
~ sub_1000264bc -> sub_100025f30 : 984 -> 976
~ sub_100026da0 -> sub_10002680c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10002896c -> sub_1000283b8 : 144 -> 140
~ sub_10002917c -> sub_100028bc4 : 308 -> 284
~ sub_100029e78 -> sub_1000298a8 : 892 -> 880
~ _nbbio_disable_readwrite : 88 -> 76
~ _nbbio_slumber : 96 -> 84
~ _nbbio_free : 128 -> 116
~ _dict_fail_open : 192 -> 180
~ sub_10002a898 -> sub_10002a28c : 60 -> 48
~ sub_10002aedc -> sub_10002a8c4 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002c014 -> sub_10002b9f4 : 228 -> 216
~ sub_10002c2b0 -> sub_10002bc84 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002c988 -> sub_10002c354 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002cb9c -> sub_10002c550 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002d778 -> sub_10002d0f0 : 100 -> 88
~ sub_10002e15c -> sub_10002dac8 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

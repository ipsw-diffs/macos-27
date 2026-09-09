## smtp

> `/usr/libexec/postfix/smtp`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x469c8
+  __TEXT.__text: 0x460c4
   __TEXT.__auth_stubs: 0x12b0
   __TEXT.__cstring: 0x10404
   __TEXT.__const: 0x262
-  __TEXT.__unwind_info: 0xc88
+  __TEXT.__unwind_info: 0x1070
   __DATA_CONST.__const: 0x4198
   __DATA_CONST.__auth_got: 0x958
   __DATA_CONST.__got: 0x90
Functions:
~ sub_100000a04 : 292 -> 280
~ sub_100001018 -> sub_10000100c : 636 -> 624
~ sub_1000016cc -> sub_1000016b4 : 4032 -> 4020
~ sub_1000028d0 -> sub_1000028ac : 416 -> 404
~ sub_100005914 -> sub_1000058e4 : 708 -> 696
~ sub_100005bd8 -> sub_100005b9c : 176 -> 164
~ sub_100005c88 -> sub_100005c40 : 292 -> 268
~ sub_100005f54 -> sub_100005ef4 : 124 -> 112
~ _smtp_chat_notify : 540 -> 516
~ _smtp_session_free : 212 -> 200
~ sub_100007c6c -> sub_100007bdc : 208 -> 196
~ _smtp_state_free : 172 -> 160
~ sub_100008f18 -> sub_100008e70 : 120 -> 108
~ _smtp_sasl_helo_login : 352 -> 340
~ _smtp_save_session : 252 -> 240
~ _smtp_reuse_nexthop : 152 -> 140
~ _smtp_reuse_addr : 196 -> 184
~ sub_10000aba4 -> sub_10000aac0 : 100 -> 88
~ _smtp_sasl_auth_cache_store : 232 -> 220
~ sub_10000acf0 -> sub_10000abf4 : 108 -> 96
~ sub_10000aefc -> sub_10000adf4 : 284 -> 272
~ sub_10000bb28 -> sub_10000ba14 : 300 -> 276
~ sub_10000bc54 -> sub_10000bb28 : 300 -> 276
~ sub_10000bf1c -> sub_10000bdd8 : 512 -> 500
~ _tls_pkey_fprint : 268 -> 256
~ sub_10000cbdc -> sub_10000ca80 : 184 -> 176
~ sub_10000cc94 -> sub_10000cb30 : 200 -> 192
~ _tls_param_init : 92 -> 80
~ _tls_free_app_context : 112 -> 100
~ _tls_free_context : 204 -> 192
~ sub_10000db10 -> sub_10000d980 : 632 -> 624
~ _tls_set_dh_from_file : 244 -> 232
~ _tls_peer_CN : 96 -> 84
~ sub_10000e6a4 -> sub_10000e4f4 : 480 -> 484
~ _tls_issuer_CN : 128 -> 116
~ _tls_dane_free : 204 -> 192
~ sub_10000eb00 -> sub_10000e93c : 84 -> 72
~ _tls_dane_add_ee_digests : 372 -> 348
~ _tls_session_stop : 216 -> 204
~ sub_1000101f0 -> sub_10000fffc : 144 -> 132
~ _tls_scache_close : 124 -> 112
~ _tls_int_seed : 92 -> 80
~ _dns_rr_free : 88 -> 76
~ _dns_rr_to_pa : 100 -> 88
~ _dns_sa_to_rr : 140 -> 116
~ _dns_str_resflags : 96 -> 84
~ _xsasl_client_init : 120 -> 108
~ sub_10001388c -> sub_10001362c : 40 -> 28
~ sub_100013a44 -> sub_1000137d8 : 108 -> 96
~ _been_here_free : 64 -> 52
~ sub_100014cf8 -> sub_100014a74 : 196 -> 184
~ sub_100014f60 -> sub_100014cd0 : 152 -> 140
~ sub_100014ff8 -> sub_100014d5c : 152 -> 140
~ sub_100015090 -> sub_100014de8 : 128 -> 116
~ sub_100015478 -> sub_1000151c4 : 172 -> 160
~ sub_100015524 -> sub_100015264 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_10001561c -> sub_100015344 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_100018870 -> sub_100018550 : 68 -> 56
~ _dsn_free : 108 -> 96
~ _dsb_free : 108 -> 96
~ _get_file_id_st : 152 -> 140
~ _header_opts_find : 796 -> 788
~ _header_token : 1208 -> 1172
~ _log_adhoc : 1796 -> 1764
~ sub_10001b634 -> sub_10001b298 : 340 -> 328
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
~ _mail_date : 616 -> 612
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ sub_10001f20c -> sub_10001ede8 : 144 -> 132
~ _mime_state_update : 4064 -> 4060
~ sub_1000204a0 -> sub_10002006c : 1244 -> 1224
~ sub_1000212d4 -> sub_100020e8c : 608 -> 596
~ _post_mail_fopen_async : 264 -> 252
~ sub_1000216fc -> sub_10002129c : 408 -> 396
~ _post_mail_fclose_async : 256 -> 244
~ _quote_821_local_flags : 664 -> 652
~ _quote_822_local_flags : 664 -> 652
~ _rcpb_free : 76 -> 64
~ _recipient_list_add : 264 -> 272
~ _recipient_list_free : 124 -> 112
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100024044 -> sub_100023b80 : 72 -> 60
~ sub_10002548c -> sub_100024fbc : 316 -> 304
~ _hbc_header_checks : 292 -> 280
~ sub_1000270c0 -> sub_100026bd8 : 928 -> 916
~ _hbc_body_checks : 228 -> 216
~ __hbc_checks_free : 108 -> 96
~ sub_100028a4c -> sub_100028540 : 148 -> 136
~ sub_100028ae0 -> sub_1000285c8 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_10002b328 -> sub_10002adfc : 336 -> 324
~ sub_10002c5e4 -> sub_10002c0ac : 164 -> 152
~ sub_10002c820 -> sub_10002c2dc : 220 -> 224
~ _allprint : 60 -> 64
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ _attr_clnt_free : 60 -> 48
~ sub_10002f248 -> sub_10002ecec : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10002f424 -> sub_10002eeb0 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100030b04 -> sub_100030550 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100030d8c -> sub_1000307c0 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000321a8 -> sub_100031b94 : 96 -> 84
~ sub_100032ce0 -> sub_1000326c0 : 172 -> 160
~ sub_1000330bc -> sub_100032a90 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000331a8 -> sub_100032b64 : 112 -> 100
~ sub_1000332a0 -> sub_100032c50 : 64 -> 52
~ sub_100033394 -> sub_100032d38 : 116 -> 104
~ sub_1000335b8 -> sub_100032f50 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000345a0 -> sub_100033f24 : 248 -> 236
~ sub_1000348dc -> sub_100034254 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100034fe4 -> sub_100034954 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10003540c -> sub_100034d64 : 64 -> 52
~ sub_100035740 -> sub_10003508c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100036214 -> sub_100035b4c : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _line_wrap : 412 -> 400
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10003a83c -> sub_10003a12c : 152 -> 140
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
~ sub_10003f32c -> sub_10003eb3c : 984 -> 976
~ sub_10003fc10 -> sub_10003f418 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_1000417dc -> sub_100040fc4 : 144 -> 140
~ sub_100041fec -> sub_1000417d0 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100043314 -> sub_100042ad4 : 60 -> 48
~ sub_100043958 -> sub_10004310c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100044a90 -> sub_10004423c : 228 -> 216
~ sub_100044d2c -> sub_1000444cc : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100045404 -> sub_100044b9c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100045618 -> sub_100044d98 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_1000461f4 -> sub_100045938 : 100 -> 88
~ sub_100046bd8 -> sub_100046310 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

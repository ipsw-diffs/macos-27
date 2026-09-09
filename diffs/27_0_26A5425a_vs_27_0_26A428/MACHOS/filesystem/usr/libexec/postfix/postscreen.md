## postscreen

> `/usr/libexec/postfix/postscreen`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x301bc
+  __TEXT.__text: 0x2fa44
   __TEXT.__auth_stubs: 0xae0
   __TEXT.__const: 0x222
   __TEXT.__cstring: 0xb8e3
-  __TEXT.__unwind_info: 0x910
+  __TEXT.__unwind_info: 0xc38
   __DATA_CONST.__const: 0x2300
   __DATA_CONST.__auth_got: 0x570
   __DATA_CONST.__got: 0x58
Functions:
~ sub_1000009d4 : 172 -> 160
~ sub_100000a80 -> sub_100000a74 : 388 -> 376
~ sub_100000c04 -> sub_100000bec : 1368 -> 1352
~ sub_10000115c -> sub_100001134 : 120 -> 108
~ sub_100001274 -> sub_100001240 : 1420 -> 1372
~ _psc_addr_match_list_match : 436 -> 432
~ _psc_cache_lookup : 448 -> 444
~ _psc_cache_update : 440 -> 436
~ _psc_dict_get : 436 -> 432
~ _psc_maps_find : 440 -> 436
~ _psc_dnsbl_retrieve : 384 -> 376
~ _psc_early_tests : 408 -> 384
~ sub_100002e78 -> sub_100002de0 : 220 -> 208
~ sub_100002f54 -> sub_100002eb0 : 1720 -> 1696
~ _psc_smtpd_tests : 332 -> 308
~ sub_100004760 -> sub_10000468c : 352 -> 340
~ _psc_smtpd_init : 584 -> 572
~ sub_100004e5c -> sub_100004d70 : 360 -> 348
~ sub_1000052c8 -> sub_1000051d0 : 216 -> 204
~ sub_100005410 -> sub_10000530c : 76 -> 64
~ sub_1000054d0 -> sub_1000053c0 : 160 -> 148
~ sub_100005570 -> sub_100005454 : 288 -> 276
~ _psc_format_delta_time : 308 -> 304
~ _psc_conclude : 420 -> 396
~ _psc_hangup_event : 140 -> 128
~ _psc_parse_tests : 276 -> 264
~ _psc_send_socket : 652 -> 616
~ sub_1000066ec -> sub_10000656c : 260 -> 248
~ _psc_starttls_open : 596 -> 584
~ _psc_expand_init : 68 -> 56
~ _psc_endpt_lookup : 220 -> 208
~ _psc_endpt_haproxy_lookup : 196 -> 184
~ _event_server_disconnect : 240 -> 228
~ sub_1000083a8 -> sub_1000081e0 : 260 -> 236
~ sub_1000084ac -> sub_1000082cc : 260 -> 236
~ sub_1000086cc -> sub_1000084d4 : 104 -> 92
~ sub_100008734 -> sub_100008530 : 396 -> 372
~ sub_1000088c0 -> sub_1000086a4 : 216 -> 204
~ _been_here_free : 64 -> 52
~ sub_100009880 -> sub_10000964c : 196 -> 184
~ sub_100009ae8 -> sub_1000098a8 : 152 -> 140
~ sub_100009b80 -> sub_100009934 : 152 -> 140
~ sub_100009c18 -> sub_1000099c0 : 128 -> 116
~ sub_10000a000 -> sub_100009d9c : 172 -> 160
~ sub_10000a0ac -> sub_100009e3c : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_10000a1a4 -> sub_100009f1c : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000c35c -> sub_10000c08c : 68 -> 56
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
~ sub_10000fc90 -> sub_10000f92c : 1244 -> 1224
~ _data_redirect_file : 64 -> 52
~ sub_100012b64 -> sub_1000127e0 : 148 -> 136
~ sub_100012bf8 -> sub_100012868 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100015794 -> sub_1000153f0 : 336 -> 324
~ sub_100016a50 -> sub_1000166a0 : 164 -> 152
~ sub_100016c8c -> sub_1000168d0 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000183b0 -> sub_100017fe4 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10001858c -> sub_1000181a8 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100019c6c -> sub_100019848 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100019ef4 -> sub_100019ab8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10001b310 -> sub_10001ae8c : 96 -> 84
~ sub_10001be48 -> sub_10001b9b8 : 172 -> 160
~ sub_10001c224 -> sub_10001bd88 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10001c310 -> sub_10001be5c : 112 -> 100
~ sub_10001c408 -> sub_10001bf48 : 64 -> 52
~ sub_10001c4fc -> sub_10001c030 : 116 -> 104
~ sub_10001c720 -> sub_10001c248 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001d708 -> sub_10001d21c : 248 -> 236
~ sub_10001da44 -> sub_10001d54c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001e14c -> sub_10001dc4c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10001e574 -> sub_10001e05c : 64 -> 52
~ sub_10001e65c -> sub_10001e138 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001f130 -> sub_10001ebf8 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_1000231bc -> sub_100022c48 : 152 -> 140
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
~ sub_10002773c -> sub_100027100 : 984 -> 976
~ sub_100028020 -> sub_1000279dc : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100029bec -> sub_100029588 : 144 -> 140
~ sub_10002a3fc -> sub_100029d94 : 308 -> 284
~ _dict_cache_control : 600 -> 596
~ sub_10002b520 -> sub_10002ae9c : 480 -> 468
~ _dict_cache_close : 124 -> 112
~ _ip_match_save : 76 -> 64
~ _dict_fail_open : 192 -> 180
~ sub_10002cb18 -> sub_10002c464 : 60 -> 48
~ sub_10002d15c -> sub_10002ca9c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10002e284 -> sub_10002dbbc : 228 -> 216
~ sub_10002e520 -> sub_10002de4c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10002ebf8 -> sub_10002e51c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10002ee0c -> sub_10002e718 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10002f9e8 -> sub_10002f2b8 : 100 -> 88
~ sub_1000303cc -> sub_10002fc90 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

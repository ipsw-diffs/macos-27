## tlsmgr

> `/usr/libexec/postfix/tlsmgr`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x2a11c
+  __TEXT.__text: 0x29b28
   __TEXT.__auth_stubs: 0xc50
   __TEXT.__cstring: 0xa038
   __TEXT.__const: 0x1c2
-  __TEXT.__unwind_info: 0x878
+  __TEXT.__unwind_info: 0xb70
   __DATA_CONST.__const: 0x1e30
   __DATA_CONST.__auth_got: 0x628
   __DATA_CONST.__got: 0x60
Functions:
~ sub_1000009b8 : 1852 -> 1840
~ sub_1000018ec -> sub_1000018e0 : 156 -> 144
~ _multi_server_disconnect : 248 -> 236
~ sub_1000025b4 -> sub_100002590 : 260 -> 236
~ sub_1000026b8 -> sub_10000267c : 260 -> 236
~ sub_100002904 -> sub_1000028b0 : 416 -> 392
~ sub_100002ac0 -> sub_100002a54 : 268 -> 256
~ _tls_prng_dev_read : 280 -> 272
~ _tls_prng_egd_read : 400 -> 392
~ _tls_prng_exch_close : 144 -> 132
~ _tls_param_init : 92 -> 80
~ _tls_free_app_context : 112 -> 100
~ _tls_free_context : 204 -> 192
~ sub_100004444 -> sub_10000438c : 632 -> 624
~ _tls_scache_close : 124 -> 112
~ _been_here_free : 64 -> 52
~ sub_100005d30 -> sub_100005c58 : 196 -> 184
~ sub_100005f98 -> sub_100005eb4 : 152 -> 140
~ sub_100006030 -> sub_100005f40 : 152 -> 140
~ sub_1000060c8 -> sub_100005fcc : 128 -> 116
~ sub_1000064b0 -> sub_1000063a8 : 172 -> 160
~ sub_10000655c -> sub_100006448 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100006654 -> sub_100006528 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _debug_process : 120 -> 108
~ _dict_proxy_open : 1024 -> 1012
~ sub_10000880c -> sub_100008698 : 68 -> 56
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
~ sub_10000c04c -> sub_10000be44 : 1244 -> 1224
~ _data_redirect_file : 64 -> 52
~ sub_10000ec0c -> sub_10000e9e4 : 148 -> 136
~ sub_10000eca0 -> sub_10000ea6c : 464 -> 468
~ _mail_version_free : 60 -> 48
~ _dsn_filter_free : 124 -> 112
~ sub_100010f64 -> sub_100010d1c : 336 -> 324
~ sub_100012220 -> sub_100011fcc : 164 -> 152
~ sub_10001245c -> sub_1000121fc : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100013b80 -> sub_100013910 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100013d5c -> sub_100013ad4 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10001543c -> sub_100015174 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000156c4 -> sub_1000153e4 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100016ae0 -> sub_1000167b8 : 96 -> 84
~ sub_100017618 -> sub_1000172e4 : 172 -> 160
~ sub_1000179f4 -> sub_1000176b4 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100017ae0 -> sub_100017788 : 112 -> 100
~ sub_100017bd8 -> sub_100017874 : 64 -> 52
~ sub_100017ccc -> sub_10001795c : 116 -> 104
~ sub_100017ef0 -> sub_100017b74 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100018ed8 -> sub_100018b48 : 248 -> 236
~ sub_100019214 -> sub_100018e78 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10001991c -> sub_100019578 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100019d44 -> sub_100019988 : 64 -> 52
~ sub_100019e2c -> sub_100019a64 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10001a900 -> sub_10001a524 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_10001ebc0 -> sub_10001e7a8 : 152 -> 140
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
~ sub_100022ca4 -> sub_1000227c4 : 984 -> 976
~ sub_100023588 -> sub_1000230a0 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100025154 -> sub_100024c4c : 144 -> 140
~ sub_100025964 -> sub_100025458 : 308 -> 284
~ _dict_fail_open : 192 -> 180
~ sub_100026ab8 -> sub_100026588 : 60 -> 48
~ sub_1000270fc -> sub_100026bc0 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100028234 -> sub_100027cf0 : 228 -> 216
~ sub_1000284d0 -> sub_100027f80 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100028ba8 -> sub_100028650 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100028dbc -> sub_10002884c : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100029998 -> sub_1000293ec : 100 -> 88
~ sub_10002a37c -> sub_100029dc4 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

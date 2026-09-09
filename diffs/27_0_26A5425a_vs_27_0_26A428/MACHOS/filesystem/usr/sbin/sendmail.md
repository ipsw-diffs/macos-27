## sendmail

> `/usr/sbin/sendmail`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x23d08
+  __TEXT.__text: 0x23818
   __TEXT.__auth_stubs: 0x8a0
   __TEXT.__cstring: 0x76f3
   __TEXT.__const: 0x162
-  __TEXT.__unwind_info: 0x770
+  __TEXT.__unwind_info: 0x9c8
   __DATA_CONST.__const: 0x16a0
   __DATA_CONST.__auth_got: 0x450
   __DATA_CONST.__got: 0x48
Functions:
~ _been_here_free : 64 -> 52
~ _debug_process : 120 -> 108
~ _get_file_id_st : 152 -> 140
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
~ _mail_queue_name_ok : 108 -> 112
~ _mail_queue_id_ok : 116 -> 120
~ _mail_queue_remove : 52 -> 40
~ _mail_queue_open : 172 -> 160
~ _mail_stream_cleanup : 136 -> 124
~ sub_100006db0 -> sub_100006cf4 : 144 -> 132
~ _mime_state_update : 4064 -> 4060
~ sub_100007f1c -> sub_100007e50 : 1244 -> 1224
~ _mypwfree : 220 -> 208
~ _quote_822_local_flags : 664 -> 652
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_10000a8fc -> sub_10000a7e0 : 316 -> 304
~ _mail_version_free : 60 -> 48
~ _allprint : 60 -> 64
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10000d43c -> sub_10000d2f8 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000d618 -> sub_10000d4bc : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10000eda0 -> sub_10000ebec : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10000f028 -> sub_10000ee5c : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100010444 -> sub_100010230 : 96 -> 84
~ sub_100010f7c -> sub_100010d5c : 172 -> 160
~ sub_100011358 -> sub_10001112c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100011444 -> sub_100011200 : 112 -> 100
~ sub_10001153c -> sub_1000112ec : 64 -> 52
~ sub_100011630 -> sub_1000113d4 : 116 -> 104
~ sub_100011854 -> sub_1000115ec : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10001283c -> sub_1000125c0 : 248 -> 236
~ sub_100012b78 -> sub_1000128f0 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100013280 -> sub_100012ff0 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_1000136a8 -> sub_100013400 : 64 -> 52
~ sub_100013960 -> sub_1000136ac : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100014434 -> sub_10001416c : 368 -> 364
~ _get_file_limit : 76 -> 72
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _match_list_free : 92 -> 80
~ _msg_syslog_init : 204 -> 192
~ sub_100018790 -> sub_100018488 : 152 -> 140
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
~ sub_10001b924 -> sub_10001b578 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_10001ccf0 -> sub_10001c8fc : 984 -> 976
~ sub_10001d5d4 -> sub_10001d1d8 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_10001f680 -> sub_10001f264 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_10002093c -> sub_100020510 : 60 -> 48
~ sub_100020f80 -> sub_100020b48 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100021dbc -> sub_10002197c : 228 -> 216
~ sub_100022058 -> sub_100021c0c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100022730 -> sub_1000222dc : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100022944 -> sub_1000224d8 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100023520 -> sub_100023078 : 100 -> 88
~ sub_100023f04 -> sub_100023a50 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

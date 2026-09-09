## postlog

> `/usr/sbin/postlog`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x18458
+  __TEXT.__text: 0x18070
   __TEXT.__auth_stubs: 0x6e0
   __TEXT.__cstring: 0x57b7
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x598
+  __TEXT.__unwind_info: 0x7a0
   __DATA_CONST.__const: 0x14a0
   __DATA_CONST.__auth_got: 0x370
   __DATA_CONST.__got: 0x48
Functions:
~ _been_here_free : 64 -> 52
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_100002ff0 -> sub_100002f94 : 1244 -> 1224
~ _mail_version_free : 60 -> 48
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100004c84 -> sub_100004bf4 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100004e60 -> sub_100004db8 : 52 -> 40
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100005a44 -> sub_100005964 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100005ccc -> sub_100005bd4 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_1000070e8 -> sub_100006fa8 : 96 -> 84
~ sub_100007c20 -> sub_100007ad4 : 172 -> 160
~ sub_100007ffc -> sub_100007ea4 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_1000080e8 -> sub_100007f78 : 112 -> 100
~ sub_1000081e0 -> sub_100008064 : 64 -> 52
~ sub_1000082d4 -> sub_10000814c : 116 -> 104
~ sub_1000084f8 -> sub_100008364 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000094e0 -> sub_100009338 : 248 -> 236
~ sub_10000981c -> sub_100009668 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100009f24 -> sub_100009d68 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000a34c -> sub_10000a178 : 64 -> 52
~ sub_10000a434 -> sub_10000a254 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000af08 -> sub_10000ad14 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_10000dfc0 -> sub_10000dd9c : 152 -> 140
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
~ sub_100011c18 -> sub_10001192c : 984 -> 976
~ sub_1000124fc -> sub_100012208 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_1000140c8 -> sub_100013db4 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_1000150a0 -> sub_100014d7c : 60 -> 48
~ sub_1000156e4 -> sub_1000153b4 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100016520 -> sub_1000161e8 : 228 -> 216
~ sub_1000167bc -> sub_100016478 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100016e94 -> sub_100016b48 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000170a8 -> sub_100016d44 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100017c84 -> sub_1000178e4 : 100 -> 88
~ sub_100018668 -> sub_1000182bc : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

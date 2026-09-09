## postkick

> `/usr/sbin/postkick`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x18c70
+  __TEXT.__text: 0x18870
   __TEXT.__auth_stubs: 0x6e0
   __TEXT.__cstring: 0x5948
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x5a8
+  __TEXT.__unwind_info: 0x7b8
   __DATA_CONST.__const: 0x1410
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
~ sub_100002fcc -> sub_100002f70 : 1244 -> 1224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000049d8 -> sub_100004954 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100004bb4 -> sub_100004b18 : 52 -> 40
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100005798 -> sub_1000056c4 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100005a20 -> sub_100005934 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100006e3c -> sub_100006d08 : 96 -> 84
~ sub_100007974 -> sub_100007834 : 172 -> 160
~ sub_100007d50 -> sub_100007c04 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100007e3c -> sub_100007cd8 : 112 -> 100
~ sub_100007f34 -> sub_100007dc4 : 64 -> 52
~ sub_100008028 -> sub_100007eac : 116 -> 104
~ sub_10000824c -> sub_1000080c4 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_100009234 -> sub_100009098 : 248 -> 236
~ sub_100009570 -> sub_1000093c8 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100009c78 -> sub_100009ac8 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000a0a0 -> sub_100009ed8 : 64 -> 52
~ sub_10000a188 -> sub_100009fb4 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000ac5c -> sub_10000aa74 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_10000de5c -> sub_10000dc44 : 152 -> 140
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
~ sub_100010da4 -> sub_100010ae8 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_10001214c -> sub_100011e48 : 984 -> 976
~ sub_100012a30 -> sub_100012724 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_1000145fc -> sub_1000142d0 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_1000158b8 -> sub_10001557c : 60 -> 48
~ sub_100015efc -> sub_100015bb4 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100016d38 -> sub_1000169e8 : 228 -> 216
~ sub_100016fd4 -> sub_100016c78 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000176ac -> sub_100017348 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_1000178c0 -> sub_100017544 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10001849c -> sub_1000180e4 : 100 -> 88
~ sub_100018e80 -> sub_100018abc : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

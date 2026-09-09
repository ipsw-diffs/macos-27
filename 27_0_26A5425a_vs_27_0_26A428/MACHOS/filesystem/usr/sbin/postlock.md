## postlock

> `/usr/sbin/postlock`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x19804
+  __TEXT.__text: 0x193ec
   __TEXT.__auth_stubs: 0x720
   __TEXT.__cstring: 0x5969
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x5d8
+  __TEXT.__unwind_info: 0x7f0
   __DATA_CONST.__const: 0x1450
   __DATA_CONST.__auth_got: 0x390
   __DATA_CONST.__got: 0x48
Functions:
~ _been_here_free : 64 -> 52
~ _dsb_free : 108 -> 96
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ _mbox_release : 76 -> 64
~ sub_100003f38 -> sub_100003ec4 : 1244 -> 1224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100005944 -> sub_1000058a8 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100005b20 -> sub_100005a6c : 52 -> 40
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100006704 -> sub_100006618 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_10000698c -> sub_100006888 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100007da8 -> sub_100007c5c : 96 -> 84
~ sub_1000088e0 -> sub_100008788 : 172 -> 160
~ sub_100008cbc -> sub_100008b58 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100008da8 -> sub_100008c2c : 112 -> 100
~ sub_100008ea0 -> sub_100008d18 : 64 -> 52
~ sub_100008f94 -> sub_100008e00 : 116 -> 104
~ sub_1000091b8 -> sub_100009018 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10000a1a0 -> sub_100009fec : 248 -> 236
~ sub_10000a4dc -> sub_10000a31c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10000abe4 -> sub_10000aa1c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000b00c -> sub_10000ae2c : 64 -> 52
~ sub_10000b0f4 -> sub_10000af08 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000bbc8 -> sub_10000b9c8 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_10000ec80 -> sub_10000ea50 : 152 -> 140
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
~ _rand_sleep : 156 -> 144
~ _safe_getenv : 76 -> 64
~ _safe_open : 340 -> 316
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_100012de8 -> sub_100012acc : 984 -> 976
~ sub_1000136cc -> sub_1000133a8 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100015298 -> sub_100014f54 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100016438 -> sub_1000160e4 : 60 -> 48
~ sub_100016a7c -> sub_10001671c : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000178b8 -> sub_100017550 : 228 -> 216
~ sub_100017b54 -> sub_1000177e0 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10001822c -> sub_100017eb0 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100018440 -> sub_1000180ac : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10001901c -> sub_100018c4c : 100 -> 88
~ sub_100019a00 -> sub_100019624 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

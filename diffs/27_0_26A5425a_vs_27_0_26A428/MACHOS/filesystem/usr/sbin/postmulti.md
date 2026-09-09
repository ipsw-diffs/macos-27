## postmulti

> `/usr/sbin/postmulti`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x1a700
+  __TEXT.__text: 0x1a2d4
   __TEXT.__auth_stubs: 0x7a0
   __TEXT.__cstring: 0x6265
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x5f8
+  __TEXT.__unwind_info: 0x808
   __DATA_CONST.__const: 0x14e0
   __DATA_CONST.__auth_got: 0x3d0
   __DATA_CONST.__got: 0x48
Functions:
~ sub_1000015d0 : 344 -> 320
~ sub_100001728 -> sub_100001710 : 140 -> 128
~ sub_100001ad0 -> sub_100001aac : 276 -> 264
~ sub_10000210c -> sub_1000020dc : 148 -> 136
~ sub_100002290 -> sub_100002254 : 492 -> 480
~ sub_100002658 -> sub_100002610 : 136 -> 140
~ _been_here_free : 64 -> 52
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_100004b28 -> sub_100004a88 : 1244 -> 1224
~ _mail_version_free : 60 -> 48
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000067bc -> sub_1000066e8 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100006998 -> sub_1000068ac : 52 -> 40
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_10000757c -> sub_100007458 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100007804 -> sub_1000076c8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100008c20 -> sub_100008a9c : 96 -> 84
~ sub_100009758 -> sub_1000095c8 : 172 -> 160
~ sub_100009b34 -> sub_100009998 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100009c20 -> sub_100009a6c : 112 -> 100
~ sub_100009d18 -> sub_100009b58 : 64 -> 52
~ sub_100009e0c -> sub_100009c40 : 116 -> 104
~ sub_10000a030 -> sub_100009e58 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10000b018 -> sub_10000ae2c : 248 -> 236
~ sub_10000b354 -> sub_10000b15c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10000ba5c -> sub_10000b85c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000be84 -> sub_10000bc6c : 64 -> 52
~ sub_10000bf80 -> sub_10000bd5c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000ca54 -> sub_10000c81c : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_10000fbf0 -> sub_10000f988 : 152 -> 140
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
~ sub_1000139e0 -> sub_1000136b0 : 984 -> 976
~ sub_1000142c4 -> sub_100013f8c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100016370 -> sub_100016018 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100017348 -> sub_100016fe0 : 60 -> 48
~ sub_10001798c -> sub_100017618 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_1000187c8 -> sub_10001844c : 228 -> 216
~ sub_100018a64 -> sub_1000186dc : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10001913c -> sub_100018dac : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100019350 -> sub_100018fa8 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100019f2c -> sub_100019b48 : 100 -> 88
~ sub_10001a910 -> sub_10001a520 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

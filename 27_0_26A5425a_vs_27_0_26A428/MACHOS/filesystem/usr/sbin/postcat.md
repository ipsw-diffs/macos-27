## postcat

> `/usr/sbin/postcat`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x1a8c0
+  __TEXT.__text: 0x1a4a4
   __TEXT.__auth_stubs: 0x750
   __TEXT.__cstring: 0x5ffc
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x600
+  __TEXT.__unwind_info: 0x808
   __DATA_CONST.__const: 0x1448
   __DATA_CONST.__auth_got: 0x3a8
   __DATA_CONST.__got: 0x48
Functions:
~ _been_here_free : 64 -> 52
~ _get_file_id_st : 152 -> 140
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
~ sub_100004424 -> sub_1000043ac : 1244 -> 1224
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_100006cb0 -> sub_100006bec : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_100006e8c -> sub_100006db0 : 52 -> 40
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100007a70 -> sub_10000795c : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100007cf8 -> sub_100007bcc : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100009114 -> sub_100008fa0 : 96 -> 84
~ sub_100009c4c -> sub_100009acc : 172 -> 160
~ sub_10000a028 -> sub_100009e9c : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10000a114 -> sub_100009f70 : 112 -> 100
~ sub_10000a20c -> sub_10000a05c : 64 -> 52
~ sub_10000a300 -> sub_10000a144 : 116 -> 104
~ sub_10000a524 -> sub_10000a35c : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10000b50c -> sub_10000b330 : 248 -> 236
~ sub_10000b848 -> sub_10000b660 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10000bf50 -> sub_10000bd60 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000c378 -> sub_10000c170 : 64 -> 52
~ sub_10000c61c -> sub_10000c408 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000d0f0 -> sub_10000cec8 : 368 -> 364
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_100010374 -> sub_10001011c : 152 -> 140
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
~ sub_100014080 -> sub_100013d60 : 984 -> 976
~ sub_100014964 -> sub_10001463c : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100016530 -> sub_1000161e8 : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100017508 -> sub_1000171b0 : 60 -> 48
~ sub_100017b4c -> sub_1000177e8 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100018988 -> sub_10001861c : 228 -> 216
~ sub_100018c24 -> sub_1000188ac : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_1000192fc -> sub_100018f7c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100019510 -> sub_100019178 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10001a0ec -> sub_100019d18 : 100 -> 88
~ sub_10001aad0 -> sub_10001a6f0 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

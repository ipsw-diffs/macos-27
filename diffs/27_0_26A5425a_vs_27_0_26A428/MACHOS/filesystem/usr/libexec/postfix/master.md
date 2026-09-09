## master

> `/usr/libexec/postfix/master`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x1e5b4
+  __TEXT.__text: 0x1e044
   __TEXT.__auth_stubs: 0x8e0
   __TEXT.__cstring: 0x6f36
   __TEXT.__const: 0x182
-  __TEXT.__unwind_info: 0x690
+  __TEXT.__unwind_info: 0x950
   __DATA_CONST.__const: 0x1568
   __DATA_CONST.__auth_got: 0x470
   __DATA_CONST.__got: 0x48
Functions:
~ _master_config : 328 -> 316
~ _set_master_ent : 400 -> 388
~ _print_master_ent : 456 -> 444
~ _free_master_ent : 136 -> 124
~ sub_100002704 -> sub_1000026d4 : 140 -> 128
~ _master_avail_more : 176 -> 164
~ _master_avail_less : 172 -> 160
~ _master_spawn : 1048 -> 1036
~ sub_100002d68 -> sub_100002d08 : 144 -> 132
~ _master_delete_children : 168 -> 156
~ sub_1000030a4 -> sub_10000302c : 140 -> 128
~ _master_start_service : 72 -> 60
~ _master_stop_service : 72 -> 60
~ _master_restart_service : 100 -> 88
~ _master_status_init : 228 -> 216
~ _master_listen_init : 592 -> 572
~ _master_vars_init : 172 -> 160
~ _master_wakeup_init : 140 -> 128
~ sub_1000039c8 -> sub_1000038e8 : 444 -> 432
~ _master_wakeup_cleanup : 120 -> 108
~ _master_flow_init : 140 -> 128
~ _been_here_free : 64 -> 52
~ _debug_process : 120 -> 108
~ _mail_conf_read : 40 -> 28
~ _mail_conf_suck : 252 -> 240
~ _mail_conf_flush : 68 -> 56
~ _mail_conf_lookup_eval : 80 -> 68
~ _get_mail_conf_str : 136 -> 124
~ _get_mail_conf_str2 : 160 -> 148
~ _get_mail_conf_str_fn : 136 -> 124
~ _get_mail_conf_time : 232 -> 236
~ sub_100006418 -> sub_1000062ac : 1244 -> 1224
~ _mail_version_free : 60 -> 48
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_1000083b0 -> sub_100008210 : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000858c -> sub_1000083d4 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100009868 -> sub_100009658 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_100009af0 -> sub_1000098c8 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_10000af0c -> sub_10000ac9c : 96 -> 84
~ sub_10000ba44 -> sub_10000b7c8 : 172 -> 160
~ sub_10000be20 -> sub_10000bb98 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_10000bf0c -> sub_10000bc6c : 112 -> 100
~ sub_10000c004 -> sub_10000bd58 : 64 -> 52
~ sub_10000c0f8 -> sub_10000be40 : 116 -> 104
~ sub_10000c31c -> sub_10000c058 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_10000d304 -> sub_10000d02c : 248 -> 236
~ sub_10000d640 -> sub_10000d35c : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_10000dd48 -> sub_10000da5c : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_10000e170 -> sub_10000de6c : 64 -> 52
~ sub_10000e26c -> sub_10000df5c : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_10000ed40 -> sub_10000ea1c : 368 -> 364
~ _get_file_limit : 76 -> 72
~ _htable_create : 104 -> 96
~ _htable_delete : 340 -> 328
~ _htable_free : 192 -> 180
~ _inet_addr_list_append : 308 -> 312
~ sub_1000113f8 -> sub_1000110b0 : 176 -> 164
~ _lowercase : 100 -> 104
~ _mac_parse : 884 -> 888
~ _mask_addr : 132 -> 120
~ _msg_syslog_init : 204 -> 192
~ sub_1000127cc -> sub_100012468 : 152 -> 140
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
~ sub_100015e10 -> sub_100015a08 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_1000171b8 -> sub_100016d68 : 984 -> 976
~ sub_100017a9c -> sub_100017644 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100019668 -> sub_1000191f0 : 144 -> 140
~ sub_100019e78 -> sub_1000199fc : 308 -> 284
~ sub_10001a7ec -> sub_10001a358 : 248 -> 236
~ _dict_fail_open : 192 -> 180
~ sub_10001b1fc -> sub_10001ad50 : 60 -> 48
~ sub_10001b840 -> sub_10001b388 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_10001c67c -> sub_10001c1bc : 228 -> 216
~ sub_10001c918 -> sub_10001c44c : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_10001cff0 -> sub_10001cb1c : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_10001d204 -> sub_10001cd18 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_10001dde0 -> sub_10001d8b8 : 100 -> 88
~ sub_10001e7c4 -> sub_10001e290 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

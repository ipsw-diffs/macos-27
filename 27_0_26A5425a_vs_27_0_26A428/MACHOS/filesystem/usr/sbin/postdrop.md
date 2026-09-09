## postdrop

> `/usr/sbin/postdrop`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1636.0.0.0.0
-  __TEXT.__text: 0x253b8
+  __TEXT.__text: 0x24e6c
   __TEXT.__auth_stubs: 0xa50
   __TEXT.__cstring: 0x8685
   __TEXT.__const: 0x122
-  __TEXT.__unwind_info: 0x7a0
+  __TEXT.__unwind_info: 0xa18
   __DATA_CONST.__const: 0x1500
   __DATA_CONST.__auth_got: 0x528
   __DATA_CONST.__got: 0x48
Functions:
~ _been_here_free : 64 -> 52
~ sub_100001554 -> sub_100001548 : 196 -> 184
~ sub_1000017bc -> sub_1000017a4 : 152 -> 140
~ sub_100001854 -> sub_100001830 : 152 -> 140
~ sub_1000018ec -> sub_1000018bc : 128 -> 116
~ sub_100001cd4 -> sub_100001c98 : 172 -> 160
~ sub_100001d80 -> sub_100001d38 : 52 -> 40
~ _clnt_stream_free : 84 -> 72
~ sub_100001e78 -> sub_100001e18 : 52 -> 40
~ _db_common_parse_domain : 188 -> 176
~ _db_common_free_ctx : 64 -> 52
~ _db_common_sql_build_query : 344 -> 332
~ _dict_proxy_open : 1024 -> 1012
~ sub_1000039b0 -> sub_100003914 : 68 -> 56
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
~ _mail_stream_cleanup : 136 -> 124
~ sub_100006fd4 -> sub_100006eb4 : 1244 -> 1224
~ _mypwfree : 220 -> 208
~ _rec_vfprintf : 136 -> 124
~ _rec_fputs : 100 -> 88
~ _REMOVE : 272 -> 260
~ sub_100009f7c -> sub_100009e18 : 148 -> 136
~ sub_10000a010 -> sub_100009ea0 : 464 -> 468
~ _mail_version_free : 60 -> 48
~ sub_10000c0c0 -> sub_10000bf48 : 336 -> 324
~ sub_10000d37c -> sub_10000d1f8 : 164 -> 152
~ sub_10000d5b8 -> sub_10000d428 : 220 -> 224
~ _argv_alloc : 88 -> 80
~ _argv_replace_one : 128 -> 116
~ sub_10000ecdc -> sub_10000eb3c : 52 -> 40
~ _auto_clnt_free : 76 -> 64
~ sub_10000eeb8 -> sub_10000ed00 : 52 -> 40
~ _binhash_create : 100 -> 92
~ _binhash_delete : 352 -> 340
~ _binhash_free : 172 -> 160
~ _clean_env : 268 -> 256
~ _update_env : 212 -> 200
~ _ctable_create : 160 -> 152
~ _ctable_refresh : 228 -> 216
~ sub_100010640 -> sub_100010430 : 76 -> 64
~ _dict_unregister : 220 -> 208
~ sub_1000108c8 -> sub_1000106a0 : 68 -> 56
~ _dict_update : 200 -> 188
~ _dict_delete : 172 -> 160
~ _dict_sequence : 200 -> 188
~ _dict_walk : 112 -> 100
~ _dict_flags_str : 96 -> 84
~ _dict_free : 92 -> 80
~ _dict_cidr_open : 1696 -> 1708
~ sub_100011ce4 -> sub_100011a74 : 96 -> 84
~ sub_10001281c -> sub_1000125a0 : 172 -> 160
~ sub_100012bf8 -> sub_100012970 : 64 -> 52
~ _dict_env_open : 172 -> 160
~ sub_100012ce4 -> sub_100012a44 : 112 -> 100
~ sub_100012ddc -> sub_100012b30 : 64 -> 52
~ sub_100012ed0 -> sub_100012c18 : 116 -> 104
~ sub_1000130f4 -> sub_100012e30 : 88 -> 76
~ _dict_open3 : 488 -> 476
~ _dict_regexp_open : 2152 -> 2156
~ sub_1000140dc -> sub_100013e04 : 248 -> 236
~ sub_100014418 -> sub_100014134 : 372 -> 376
~ _dict_tcp_open : 220 -> 208
~ sub_100014b20 -> sub_100014834 : 100 -> 88
~ _dict_unix_open : 292 -> 280
~ sub_100014f48 -> sub_100014c44 : 64 -> 52
~ sub_100015200 -> sub_100014ef0 : 404 -> 400
~ _event_drain : 308 -> 296
~ _event_loop : 884 -> 880
~ sub_100015cd4 -> sub_1000159b0 : 368 -> 364
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
~ sub_100019e78 -> sub_100019b14 : 152 -> 140
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
~ sub_10001d00c -> sub_10001cc04 : 176 -> 164
~ _valid_hostaddr : 176 -> 152
~ _valid_ipv6_hostaddr : 588 -> 576
~ _vbuf_write : 164 -> 160
~ _vbuf_print : 2416 -> 2396
~ sub_10001e3b4 -> sub_10001df64 : 984 -> 976
~ sub_10001ec98 -> sub_10001e840 : 1116 -> 1108
~ _vstream_fflush : 96 -> 84
~ _vstream_fdclose : 100 -> 88
~ sub_100020d44 -> sub_1000208cc : 144 -> 140
~ _dict_fail_open : 192 -> 180
~ sub_100022000 -> sub_100021b78 : 60 -> 48
~ sub_100022644 -> sub_1000221b0 : 196 -> 184
~ _dict_pcre_open : 2088 -> 2092
~ sub_100023480 -> sub_100022fe4 : 228 -> 216
~ sub_10002371c -> sub_100023274 : 448 -> 452
~ _dict_pipe_open : 668 -> 656
~ sub_100023df4 -> sub_100023944 : 100 -> 88
~ _dict_random_open : 360 -> 348
~ sub_100024008 -> sub_100023b40 : 60 -> 48
~ _valid_utf8_hostname : 192 -> 180
~ _midna_domain_to_ascii : 116 -> 104
~ _midna_domain_to_utf8 : 116 -> 104
~ _dict_union_open : 668 -> 656
~ sub_100024be4 -> sub_1000246e0 : 100 -> 88
~ sub_1000255c8 -> sub_1000250b8 : 204 -> 192
~ _strcasecmp_utf8x : 244 -> 220
~ _strncasecmp_utf8x : 256 -> 232
```

## pppd

> `/usr/sbin/pppd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1031.0.0.0.4
-  __TEXT.__text: 0x2ee10
+  __TEXT.__text: 0x2e608
   __TEXT.__auth_stubs: 0x1190
   __TEXT.__const: 0x708
   __TEXT.__cstring: 0x9be1
   __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x7a0
+  __TEXT.__unwind_info: 0xa48
   __DATA_CONST.__const: 0x3b8
   __DATA_CONST.__cfstring: 0x4a0
   __DATA_CONST.__auth_got: 0x8c8
Functions:
~ _link_down : 312 -> 300
~ _link_established : 848 -> 824
~ sub_100001adc -> sub_100001ab8 : 312 -> 300
~ _start_networks : 224 -> 212
~ _continue_networks : 216 -> 204
~ _check_protocols_ready : 208 -> 196
~ _auth_peer_success : 404 -> 396
~ _auth_withpeer_success : 328 -> 316
~ _option_change_idle : 160 -> 148
~ _check_idle : 248 -> 244
~ _np_up : 264 -> 252
~ _np_down : 132 -> 120
~ _np_finished : 72 -> 60
~ _auth_hold : 80 -> 68
~ _auth_cont : 164 -> 152
~ sub_100004094 -> sub_100003fe0 : 348 -> 324
~ sub_1000041f0 -> sub_100004124 : 148 -> 136
~ sub_1000042b4 -> sub_1000041dc : 176 -> 164
~ sub_100004364 -> sub_100004280 : 88 -> 76
~ sub_10000481c -> sub_10000472c : 332 -> 320
~ sub_100004c68 -> sub_100004b6c : 844 -> 832
~ sub_100006418 -> sub_100006310 : 228 -> 216
~ _chapms_init : 68 -> 56
~ _demand_block : 112 -> 100
~ sub_1000082c0 -> sub_100008194 : 308 -> 304
~ _fsm_lowerdown : 244 -> 220
~ sub_1000084e8 -> sub_1000083a0 : 340 -> 328
~ _fsm_open : 228 -> 204
~ _fsm_sdata : 196 -> 180
~ _fsm_input : 988 -> 892
~ sub_100008cdc -> sub_100008b00 : 652 -> 640
~ sub_100008f68 -> sub_100008d80 : 436 -> 412
~ sub_10000911c -> sub_100008f1c : 228 -> 216
~ sub_100009200 -> sub_100008ff4 : 228 -> 216
~ _fsm_protreject : 316 -> 304
~ sub_10000a9b0 -> sub_10000a78c : 1348 -> 1344
~ sub_10000b754 -> sub_10000b52c : 1740 -> 1716
~ sub_10000be20 -> sub_10000bbe0 : 372 -> 360
~ sub_10000bfe0 -> sub_10000bd94 : 144 -> 132
~ sub_10000c2d4 -> sub_10000c07c : 116 -> 104
~ sub_10000c348 -> sub_10000c0e4 : 80 -> 68
~ _lcp_lowerup : 304 -> 280
~ _lcp_lowerdown : 112 -> 100
~ _lcp_close : 252 -> 240
~ sub_10000c694 -> sub_10000c3f4 : 1360 -> 1352
~ sub_10000cc88 -> sub_10000c9e0 : 120 -> 108
~ _lcp_echo_restart : 144 -> 132
~ sub_10000cf98 -> sub_10000ccd8 : 196 -> 184
~ sub_10000e338 -> sub_10000e06c : 1204 -> 1200
~ sub_10000efc0 -> sub_10000ecf0 : 376 -> 352
~ _magic_init : 64 -> 52
~ _reopen_log : 60 -> 48
~ _set_ifunit : 184 -> 172
~ sub_100011118 -> sub_100010e0c : 264 -> 252
~ _ppp_control : 768 -> 756
~ sub_100011e0c -> sub_100011ae8 : 200 -> 188
~ sub_100012bbc -> sub_10001288c : 124 -> 112
~ _parse_args : 324 -> 336
~ sub_100014ef8 -> sub_100014bc8 : 100 -> 88
~ _closeall : 120 -> 108
~ _sys_install : 116 -> 104
~ _sys_uninstall : 284 -> 272
~ _CopyServerData : 212 -> 200
~ _sys_protocolsreadynotify : 60 -> 48
~ _sys_acspdhcpreadynotify : 60 -> 48
~ sub_100016420 -> sub_10001609c : 268 -> 256
~ sub_10001652c -> sub_10001619c : 516 -> 504
~ sub_1000167f4 -> sub_100016458 : 228 -> 200
~ _cifdefaultroute : 76 -> 64
~ _sys_runloop : 128 -> 104
~ _set_network_signature : 440 -> 416
~ _sys_notify : 348 -> 324
~ _tty_disestablish_ppp : 208 -> 184
~ _output : 152 -> 140
~ _tty_set_xaccm : 132 -> 120
~ _sifdefaultroute : 84 -> 72
~ _sys_reinit : 144 -> 132
~ sub_10001c024 -> sub_10001bbd0 : 88 -> 76
~ _ppp_variable_echo_start : 220 -> 208
~ _ppp_auxiliary_probe_check : 224 -> 212
~ sub_10001c6b4 -> sub_10001c23c : 148 -> 136
~ _l2tp_set_nat_port_mapping : 224 -> 212
~ _sys_setup_security_session : 280 -> 268
~ sub_10001cdd8 -> sub_10001c93c : 76 -> 64
~ sub_10001cf10 -> sub_10001ca68 : 2968 -> 2928
~ sub_10001fa34 -> sub_10001f564 : 256 -> 244
~ _disconnect_tty : 216 -> 192
~ _tty_do_send_config : 96 -> 84
~ sub_100020f50 -> sub_100020a50 : 2712 -> 2700
~ sub_100021ba8 -> sub_10002169c : 1424 -> 1388
~ sub_100022138 -> sub_100021c08 : 140 -> 128
~ sub_1000221c4 -> sub_100021c88 : 180 -> 168
~ _upap_authwithpeer : 136 -> 124
~ sub_100022718 -> sub_1000221c4 : 144 -> 120
~ _vslprintf : 2772 -> 2744
~ _print_string : 360 -> 348
~ sub_100024b80 -> sub_1000245ec : 1652 -> 1592
~ sub_1000251f4 -> sub_100024c24 : 120 -> 108
~ sub_100025b90 -> sub_1000255b4 : 204 -> 168
~ sub_100025cb4 -> sub_1000256b4 : 668 -> 644
~ sub_100026048 -> sub_100025a30 : 932 -> 860
~ sub_1000276c8 -> sub_100027068 : 720 -> 696
~ sub_100027998 -> sub_100027320 : 212 -> 200
~ sub_100028670 -> sub_100027fec : 96 -> 84
~ sub_1000286d0 -> sub_100028040 : 76 -> 64
~ sub_100029b84 -> sub_1000294e8 : 236 -> 212
~ _acsp_data_input : 268 -> 244
~ sub_10002a650 -> sub_100029f84 : 96 -> 84
~ sub_10002a6b0 -> sub_100029fd8 : 564 -> 540
~ sub_10002ad38 -> sub_10002a648 : 1340 -> 1292
~ sub_10002b2cc -> sub_10002abac : 480 -> 476
~ sub_10002b4ac -> sub_10002ad88 : 100 -> 88
~ sub_10002ba8c -> sub_10002b35c : 376 -> 364
~ sub_10002bc78 -> sub_10002b53c : 144 -> 132
~ sub_10002bd08 -> sub_10002b5c0 : 344 -> 332
~ _chap_auth_peer : 212 -> 188
~ sub_10002bf48 -> sub_10002b7dc : 348 -> 324
~ _chap_auth_with_peer : 144 -> 132
~ sub_10002c134 -> sub_10002b9a4 : 124 -> 112
~ sub_10002c1b0 -> sub_10002ba14 : 2528 -> 2480
~ sub_10002cb90 -> sub_10002c3c4 : 216 -> 204
~ sub_10002cc68 -> sub_10002c490 : 92 -> 80
~ sub_10002cf34 -> sub_10002c750 : 224 -> 200
~ sub_10002da38 -> sub_10002d23c : 68 -> 56
```

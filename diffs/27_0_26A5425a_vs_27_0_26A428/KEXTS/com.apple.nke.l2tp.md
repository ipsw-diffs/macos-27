## com.apple.nke.l2tp

> `com.apple.nke.l2tp`

```diff

 1031.0.0.0.4
   __TEXT.__cstring: 0xacd
   __TEXT.__const: 0x58
-  __TEXT_EXEC.__text: 0x4000
+  __TEXT_EXEC.__text: 0x40c4
   __TEXT_EXEC.__auth_stubs: 0x520
   __DATA.__data: 0x1d8
   __DATA.__common: 0x150
Functions:
~ _l2tp_domain_init : 244 -> 248
~ _l2tp_domain_terminate : 244 -> 248
~ _l2tp_add : 624 -> 628
~ _l2tp_attach : 188 -> 192
~ _l2tp_control : 224 -> 228
~ _l2tp_detach : 100 -> 104
~ _l2tp_send : 104 -> 108
~ _l2tp_ctloutput : 960 -> 964
~ _l2tp_remove : 156 -> 160
~ _l2tp_input : 200 -> 204
~ _l2tp_event : 212 -> 216
~ _l2tp_timer : 176 -> 180
~ _l2tp_rfc_init : 88 -> 92
~ _l2tp_rfc_dispose : 100 -> 104
~ _l2tp_rfc_new_client : 200 -> 204
~ _l2tp_rfc_free_client : 144 -> 148
~ _l2tp_rfc_free_now : 524 -> 528
~ _l2tp_rfc_set_socket : 188 -> 192
~ _l2tp_rfc_command : 2352 -> 2368
~ _l2tp_rfc_accept : 244 -> 248
~ _l2tp_rfc_slowtimer : 460 -> 464
~ _l2tp_rfc_output_queued : 240 -> 244
~ _l2tp_rfc_output_control : 540 -> 544
~ _l2tp_rfc_output_data : 404 -> 408
~ _l2tp_handle_data : 500 -> 504
~ _l2tp_handle_control : 1352 -> 1356
~ _l2tp_rfc_handle_ack : 300 -> 304
~ _l2tp_rfc_lower_input : 464 -> 468
~ _sysctl_nb_threads : 128 -> 132
~ _l2tp_udp_init : 332 -> 336
~ _l2tp_udp_init_threads : 396 -> 404
~ _l2tp_udp_dispose : 156 -> 160
~ _l2tp_udp_dispose_threads : 448 -> 452
~ _l2tp_udp_thread_func : 204 -> 208
~ _l2tp_udp_input : 264 -> 268
~ _l2tp_udp_output : 492 -> 496
~ _l2tp_udp_attach : 492 -> 496
~ _l2tp_wan_attach : 472 -> 476
~ _l2tp_wan_ioctl : 44 -> 48
~ _l2tp_wan_output : 168 -> 172
~ _l2tp_wan_detach : 184 -> 188
~ _l2tp_wan_input : 132 -> 136
~ _l2tp_wan_xmit_full : 64 -> 68
~ _l2tp_wan_input_error : 80 -> 84
~ _l2tp_wan_xmit_ok : 92 -> 96
```

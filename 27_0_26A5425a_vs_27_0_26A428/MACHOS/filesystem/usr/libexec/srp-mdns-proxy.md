## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 3111.0.5.0.1
-  __TEXT.__text: 0x8e550
+  __TEXT.__text: 0x8e320
   __TEXT.__auth_stubs: 0x14f0
   __TEXT.__const: 0x2f5
   __TEXT.__cstring: 0x9120
   __TEXT.__oslogstring: 0x14128
-  __TEXT.__unwind_info: 0x610
+  __TEXT.__unwind_info: 0x848
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x920
   __DATA_CONST.__cfstring: 0x140
Functions:
~ _netdata_tracker_finalize : 96 -> 84
~ _netdata_tracker_set_service_tracker : 668 -> 656
~ _netdata_tracker_set_omr_watcher : 668 -> 656
~ _DNSServiceAttributeDeallocate : 96 -> 84
~ _ConnectionResponse : 448 -> 424
~ ___DNSServiceSetDispatchQueue_block_invoke : 1024 -> 1012
~ _dnssd_client_finalize : 120 -> 108
~ _dnssd_client_service_unpublish : 80 -> 68
~ _dnssd_hints_find_host_name_conflict : 516 -> 504
~ _probe_state_finalize : 148 -> 136
~ ___probe_srp_service_block_invoke : 88 -> 76
~ ___probe_srp_create_block_invoke : 88 -> 76
~ _cti_connection_finalize : 64 -> 52
~ _cti_event_handler : 2120 -> 2096
~ _cti_xpc_copy_description : 1832 -> 1820
~ _state_machine_event_deliver : 464 -> 452
~ _state_machine_event_create : 796 -> 800
~ _tls_certificate_rotate : 612 -> 600
~ _srpk_hostname_to_wire : 140 -> 128
~ _ifpermit_add_permitted_interface_to_server_ : 624 -> 612
~ _ioloop_message_create_ : 708 -> 700
~ _srp_log_ref_final : 752 -> 748
~ _adv_ctl_thread_shutdown_status_check : 92 -> 80
~ _adv_xpc_restart : 108 -> 96
~ _adv_ctl_start_thread_shutdown : 604 -> 592
~ _keychain_key_remove : 288 -> 276
~ _dns_message_free : 148 -> 136
~ _wakeup_finalize : 112 -> 100
~ _ioloop_cancel_wake_event : 116 -> 104
~ _wakeup_event : 132 -> 120
~ _listener_finalize : 160 -> 148
~ _ioloop_listener_permitted_interface_list_set : 80 -> 68
~ ___ioloop_run_async_block_invoke : 80 -> 68
~ _service_tracker_finalize : 100 -> 88
~ _service_tracker_network_data_callback : 144 -> 132
~ _dns_concatenate_name_to_wire_ : 868 -> 872
~ _dns_name_print_to_limit : 356 -> 360
~ _omr_watcher_lost_prefix_reclaim : 1260 -> 1256
~ _dp_start_dropping : 108 -> 96
~ _dnssd_proxy_set_dscp_interface : 348 -> 336
~ _dp_tracker_finalize : 100 -> 88
~ _dp_answer_free : 64 -> 52
~ _dnssd_tls_listener_restart : 392 -> 380
~ _srp_mdns_update_finished : 26672 -> 26664
~ _lease_callback : 2276 -> 2268
~ _object_allocation_stats_dump_callback : 148 -> 136
~ _service_publisher_finalize : 908 -> 896
~ _service_publisher_cancel : 932 -> 920
~ _service_publisher_listener_cancel : 788 -> 776
~ _service_publisher_deliver_event_to_all_publishers : 120 -> 108
~ _service_publisher_service_unpublish : 264 -> 252
CStrings:
+ "17:21:47"
+ "Aug  8 2026"
- "01:45:35"
- "Aug 10 2026"
```

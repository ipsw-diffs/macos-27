## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 3111.0.5.0.1
-  __TEXT.__text: 0x10742c
+  __TEXT.__text: 0x106288
   __TEXT.__auth_stubs: 0x3000
   __TEXT.__objc_stubs: 0xf00
   __TEXT.__objc_methlist: 0x2a4

   __TEXT.__objc_classname: 0x5fe
   __TEXT.__objc_methname: 0xe47
   __TEXT.__objc_methtype: 0x4ea
-  __TEXT.__unwind_info: 0x1620
+  __TEXT.__unwind_info: 0x1d10
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x62d0
   __DATA_CONST.__cfstring: 0x1260
Functions:
~ _mDNS_vsnprintf : 3492 -> 3480
~ _GetUserSpecifiedLocalHostName : 88 -> 76
~ _AppendLiteralLabelString : 164 -> 160
~ _AdvertiseInterface : 1876 -> 1880
~ _GetRDLength : 460 -> 448
~ _RDataHashValue : 444 -> 432
~ _SetDomainSecrets : 3788 -> 3776
~ _mDNSDynamicStoreSetConfig : 204 -> 192
~ _mDNSCoreInitComplete : 204 -> 192
~ _mDNS_StatusCallback : 660 -> 624
~ _mDNS_SetPrimaryInterfaceInfo : 1364 -> 1352
~ _RegisterLocalOnlyDomainEnumPTR : 388 -> 376
~ _UpdateDeviceInfoRecord : 1732 -> 1724
~ _SameRDataBody : 608 -> 596
~ _KQueueLoop : 11460 -> 11456
~ _mDNS_Execute : 25720 -> 25716
~ _mDNS_RegisterService : 2216 -> 2204
~ _ServiceCallback : 928 -> 916
~ _GetServiceTarget : 916 -> 912
~ _ActivateUnicastQuery : 440 -> 428
~ _CheckCacheExpiration : 1580 -> 1568
~ _AnswerCurrentQuestionWithResourceRecord : 2692 -> 2668
~ _mDNS_StopQuery : 104 -> 92
~ _putDomainNameAsLabels : 524 -> 528
~ _putRData : 2328 -> 2316
~ _myKQSocketCallBack : 3024 -> 3012
~ _mDNSCoreReceive : 4192 -> 4180
~ _mDNSCoreReceiveQuery : 10868 -> 10860
~ _mDNS_HostNameCallback : 352 -> 340
~ _GetZoneData_StartQuery : 520 -> 508
~ _SetRecordRetry : 536 -> 528
~ _GetZoneData_QuestionCallback : 1108 -> 1084
~ _RecordRegistrationGotZoneData : 1652 -> 1616
~ _mDNS_PurgeCacheResourceRecord : 120 -> 108
~ _AdvertiseHostname : 740 -> 728
~ _SendRecordRegistration : 1020 -> 1008
~ _tcpCallback : 3452 -> 3428
~ _DisposeTCPConn : 72 -> 60
~ _mDNSPlatformTCPCloseConnection : 300 -> 288
~ _HostnameCallback : 768 -> 732
~ _AnswerLocalQuestionWithLocalAuthRecord : 1188 -> 1176
~ _mDNS_Reconfirm_internal : 280 -> 268
~ __mdns_awdl_manager : 84 -> 72
~ __mdns_awdl_log : 84 -> 72
~ __mdns_awdl_create_service_name_string : 1160 -> 1140
~ ____mdns_awdl_log_block_invoke : 72 -> 60
~ _mdns_message_builder_write_message : 584 -> 568
~ __mdns_message_builder_write_record : 1200 -> 1156
~ _mdns_domain_name_append_to_copier : 980 -> 960
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ _mdns_system_remove_network_policy : 100 -> 88
~ _D2D_stop_advertising_record : 124 -> 112
~ _D2D_start_advertising_record : 124 -> 112
~ _xD2DReceiveResponse : 192 -> 180
~ __mdns_string_builder_grow_buffer : 180 -> 172
~ _mdns_string_builder_append_description_with_prefix : 132 -> 120
~ _mdns_string_builder_append_sockaddr : 96 -> 72
~ _mdns_string_builder_copy_string : 124 -> 112
~ __mdns_symptoms_report_dns_server_symptom : 192 -> 180
~ __http_task_create_data_task : 308 -> 296
~ ___http_task_create_dns_query_block_invoke : 404 -> 392
~ ___copy_helper_block_e8_32s40b48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ ___http_task_create_pvd_query_block_invoke_2 : 652 -> 628
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ _http_task_cancel : 76 -> 64
~ -[MDNSHTTPSessionDelegate URLSession:task:didReceiveChallenge:completionHandler:] : 240 -> 228
~ __http_task_shared_session_critical_region : 96 -> 84
~ ___http_task_prepare_for_system_sleep_block_invoke : 80 -> 68
~ ____http_task_create_data_task_block_invoke : 464 -> 452
~ ____http_task_create_shared_session_block_invoke : 92 -> 80
~ __dnssec_obj_domain_name_compare : 236 -> 224
~ _dnssec_obj_domain_name_copy_closest_common_ancestor : 380 -> 376
~ _CompleteRDataUpdate : 128 -> 116
~ _mDNSCoreRestartRegistration : 268 -> 256
~ _mDNS_DeregisterService_drt : 412 -> 400
~ _mDNSCoreReceiveForQuerier : 272 -> 260
~ _mDNSCoreReceiveResponse : 28060 -> 28052
~ _mDNSCoreReceiveUpdate : 3188 -> 3184
~ _mDNS_GetDomains_Internal : 240 -> 228
~ _mDNS_StartDomainEnumeration : 208 -> 196
~ _AdvertiseInterfaceIfNeeded : 184 -> 172
~ _mDNSCoreReceiveRawTransportPacket : 4132 -> 4120
~ _SleepProxyServerCallback : 496 -> 484
~ _SetDynDNSHostNameIfChanged : 580 -> 568
~ _mDNS_DowngradeAuthRecordAWDLInclusion_internal : 192 -> 180
~ _GenerateNegativeResponseEx : 444 -> 432
~ _SendARP : 384 -> 372
~ _SendNDP : 740 -> 728
~ _AddRecordInProbe : 216 -> 204
~ _SendWakeup : 488 -> 476
~ _SendSleepGoodbyes : 348 -> 336
~ _RecordInTheRRSet : 128 -> 116
~ _mDNSCoreReceiveNoUnicastAnswers : 18632 -> 18644
~ _ScheduleWakeup : 268 -> 256
~ _ScheduleWakeupForList : 332 -> 320
~ __DNS64RestartQuestion : 292 -> 280
~ __dns_obj_domain_name_compare : 236 -> 224
~ _dns_obj_domain_name_create_with_cstring : 452 -> 448
~ __task_log : 84 -> 72
~ ___background_task_repeating_daily_register_block_invoke : 96 -> 84
~ ____task_log_block_invoke : 72 -> 60
~ ___mdns_dispatch_data_memcpy_block_invoke : 132 -> 128
~ _dnssec_obj_rrset_get_rr_expire_time : 384 -> 372
~ ___mdns_dns_service_manager_deregister_native_service_block_invoke : 96 -> 84
~ ___mdns_dns_service_manager_deregister_discovered_push_service_block_invoke : 96 -> 84
~ ___mdns_dns_service_manager_register_custom_push_service_block_invoke : 180 -> 168
~ ___copy_helper_block_8_32b40r48r : 96 -> 84
~ ___destroy_helper_block_8_32b40r48r : 80 -> 68
~ ___mdns_dns_service_manager_deregister_custom_push_service_block_invoke : 96 -> 84
~ ___mdns_dns_service_manager_deregister_custom_service_block_invoke : 96 -> 84
~ ___mdns_dns_service_manager_register_doh_uri_block_invoke : 992 -> 980
~ __mdns_dns_service_manager_prepare_service : 3504 -> 3488
~ ___copy_helper_block_8_32b40r : 80 -> 68
~ ___destroy_helper_block_8_32b40r : 68 -> 56
~ __mdns_dns_service_add_domain : 200 -> 188
~ __domain_item_compare : 332 -> 328
~ __domain_item_free : 64 -> 52
~ ____mdns_dns_service_manager_get_interface_monitor_block_invoke_2 : 172 -> 148
~ ____mdns_dns_service_manager_enumerate_service_array_including_variants_block_invoke : 100 -> 88
~ ____mdns_dns_service_manager_register_path_resolver_internal_block_invoke : 640 -> 628
~ ____mdns_dns_service_manager_cancel_resolver_config_updates_block_invoke : 60 -> 48
~ ____mdns_dns_service_manager_terminate_block_invoke_2 : 96 -> 84
~ ___copy_helper_block_8_32b40r48r56r : 112 -> 100
~ ___destroy_helper_block_8_32b40r48r56r : 92 -> 80
~ __mdns_dns_service_forget_all_ddr_queriers : 108 -> 96
~ ____mdns_dns_service_manager_schedule_ddr_probe_block_invoke : 68 -> 56
~ ___mdns_dns_service_manager_process_ddr_response_block_invoke.304 : 424 -> 412
~ ___mdns_dns_service_manager_process_ddr_response_block_invoke.309 : 152 -> 140
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ ___mdns_dns_service_manager_probe_discovered_service_block_invoke.326 : 568 -> 556
~ __mdns_dns_service_forget_ddr_connection : 76 -> 64
~ ___copy_helper_block_8_32r40r48r56r64r72r : 144 -> 132
~ ___destroy_helper_block_8_32r40r48r56r64r72r : 116 -> 104
~ ___copy_helper_block_8_32r40r48r56r64r72r80r88r : 176 -> 164
~ ___destroy_helper_block_8_32r40r48r56r64r72r80r88r : 140 -> 128
~ ____mdns_dns_service_enumerate_array_including_variants_and_discovered_alts_block_invoke : 120 -> 108
~ ___dnssd_server_init_block_invoke : 376 -> 364
~ __dx_kqueue_locked : 156 -> 132
~ ___dnssd_server_idle_block_invoke : 136 -> 124
~ __dx_release : 108 -> 96
~ __dx_recursive_init : 92 -> 80
~ ____dx_session_activate_block_invoke : 4680 -> 4668
~ ____dx_gai_request_trust_check_block_invoke : 168 -> 156
~ ____dx_gai_request_start_client_requests_internal_block_invoke : 736 -> 724
~ __dx_gai_request_query_result_handler : 732 -> 720
~ __dx_gai_request_gai_result_handler : 736 -> 724
~ __dx_gai_request_triage_result : 224 -> 212
~ ____dx_session_reset_idle_timer_block_invoke : 636 -> 624
~ ____dx_session_send_keepalive_message_block_invoke : 132 -> 120
~ ____dx_session_send_keepalive_message_block_invoke_2 : 88 -> 76
~ _natTraversalHandlePortMapReplyWithAddress : 672 -> 668
~ _UpdateOneSRVRecord : 1164 -> 1152
~ _StartRecordNatMap : 356 -> 344
~ _uDNS_DeleteWABQueries : 716 -> 704
~ _FoundDomain : 1024 -> 1000
~ _uDNS_StartWABQueries : 244 -> 232
~ _uDNS_StopWABQueries : 244 -> 232
~ _FoundStaticHostname : 572 -> 560
~ _hostnameGetPublicAddressCallback : 420 -> 384
~ _CompleteRecordNatMap : 1196 -> 1172
~ __mdns_powerlog_set_client_stats : 188 -> 176
~ __mdns_interface_monitor_finalize : 164 -> 152
~ ___mdns_interface_monitor_invalidate_block_invoke : 80 -> 68
~ _mdns_interface_monitor_set_queue : 120 -> 108
~ __mdns_interface_monitor_check_nwi_state_for_updates : 164 -> 152
~ ____mdns_interface_monitor_terminate_block_invoke : 128 -> 116
~ _GetRRDisplayString_rdb : 2864 -> 2868
~ _SetRData : 4800 -> 4792
~ _DumpMDNSPacket : 14716 -> 14700
~ _mDNS_VerifyLockState : 1576 -> 1564
~ __mdns_ne_dns_proxy_state_watch_queue : 84 -> 72
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ __mdns_ne_dns_proxy_state_watch_log : 84 -> 72
~ ___46-[MDNSNEDNSProxyWatcher configurationChanged:]_block_invoke : 128 -> 116
~ ____mdns_ne_dns_proxy_state_watch_queue_block_invoke : 68 -> 56
~ ____mdns_ne_dns_proxy_state_watch_init_block_invoke : 136 -> 124
~ ____mdns_ne_dns_proxy_state_watch_log_block_invoke : 72 -> 60
~ _LogMcastStateInfo : 664 -> 652
~ _LogMcastClientInfo : 1176 -> 1164
~ _FreeExtraRR : 240 -> 228
~ _regservice_termination_callback : 1624 -> 1612
~ _PrintOneCacheRecordToFD : 640 -> 628
~ __return_regservice_request_error : 348 -> 336
~ _LogMcastService : 372 -> 360
~ _unlink_and_free_service_instance : 204 -> 192
~ _external_start_advertising_helper : 436 -> 412
~ _LogMcastQuestion : 328 -> 316
~ _append_reply_with_timing_defense : 272 -> 260
~ ____handle_resolve_request_with_trust_block_invoke_2 : 176 -> 164
~ ____handle_queryrecord_request_with_trust_block_invoke_2 : 176 -> 164
~ ____handle_browse_request_with_trust_block_invoke_2 : 176 -> 164
~ ____handle_regservice_request_with_trust_block_invoke_2 : 176 -> 164
~ _enum_termination_callback : 232 -> 220
~ _port_mapping_create_request_callback : 892 -> 880
~ ____handle_addrinfo_request_with_trust_block_invoke_2 : 176 -> 164
~ _append_regrecord_entry_reply : 116 -> 104
~ _resolve_result_finalize : 80 -> 68
~ _downgrade_question_awdl_inclusion : 92 -> 80
~ _Querier_GetDNSServiceManager : 988 -> 984
~ ___Querier_GetDNSServiceManager_block_invoke : 504 -> 492
~ __Querier_ExcludeEncryptedDNSServices : 92 -> 80
~ ___Querier_ProcessDNSServiceChangesAsync_block_invoke : 144 -> 132
~ _Client_SameNameCacheRecordIsAnswer : 184 -> 172
~ __Querier_DNSServiceRegistrationStopHandler : 116 -> 104
~ _DPCBrowseHandler : 428 -> 416
~ __DPCRemovePushServer : 244 -> 232
~ ____Querier_GetMyUUID_block_invoke : 92 -> 80
~ ____DPCSubscribe_block_invoke : 164 -> 152
~ _domain_name_label_canonical_compare : 164 -> 160
~ _base_x_encode : 412 -> 400
~ __dns_push_obj_context_finalize : 128 -> 116
~ _NotifyOfElusiveBug : 376 -> 364
~ ___mDNSDynamicStoreSetConfig_block_invoke : 864 -> 852
~ _mDNSPlatformSetLocalAddressCacheEntry : 612 -> 600
~ _bpf_callback : 2068 -> 2056
~ _mDNSPlatformTriggerDNSRetry : 628 -> 592
~ _AckConfigd : 120 -> 108
~ _SupportsInNICProxy : 220 -> 208
~ ___mDNSMacOSXNetworkChanged_block_invoke_2 : 1480 -> 1468
~ _mDNSPlatformSendWakeupPacket : 616 -> 604
~ _GetRandomUUIDLocalHostname : 148 -> 136
~ ___spawnSSLHandshake_block_invoke : 424 -> 412
~ _SetLocalDomains : 228 -> 204
~ _SnowLeopardPowerChanged : 536 -> 524
~ _PowerChanged : 760 -> 748
~ _DynamicStoreReconnected : 172 -> 160
~ _RegisterLocalOnlyAddressRecord : 432 -> 420
~ _UpdateEtcHosts : 100 -> 88
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke : 84 -> 72
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke_2 : 252 -> 228
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke_3 : 84 -> 72
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke_5 : 268 -> 244
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke_6 : 84 -> 72
~ ___mDNSMacOSXGetEtcHostsFD_block_invoke_7 : 108 -> 96
~ _EtcHostsParseOneName : 208 -> 204
~ _CreatePTRRecord : 460 -> 448
~ _mdns_trust_set_queue : 116 -> 104
~ ____mdns_trust_activate_internal_block_invoke_3 : 96 -> 84
~ ____mdns_trust_invalidate_internal_block_invoke : 116 -> 104
~ ___mdns_client_activate_block_invoke : 104 -> 92
~ ___mdns_client_invalidate_block_invoke : 136 -> 124
~ ___mdns_client_set_time_limit_ms_block_invoke : 88 -> 76
~ ___mdns_client_activate_time_limit_timer_block_invoke : 92 -> 80
~ __dnssec_obj_rr_compare : 292 -> 288
~ _dnssec_obj_rr_copy_rdata_rfc_description : 232 -> 220
~ __mrcs_server_activate_block_invoke.8 : 392 -> 380
~ ____mrcs_session_activate_block_invoke : 3808 -> 3796
~ ____mrcs_session_handle_dns_service_registration_start_block_invoke : 212 -> 200
~ __unicast_assist_cache_log : 84 -> 72
~ __unicast_assist_cache_free_addr : 80 -> 68
~ __unicast_assist_cache_free_interface : 92 -> 80
~ ____unicast_assist_hash_for_interface_block_invoke : 268 -> 256
~ __unicast_assist_nwi_locked : 96 -> 84
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ ____unicast_assist_internal_queue_block_invoke : 68 -> 56
~ ____unicast_assist_cache_log_block_invoke : 72 -> 60
~ ____mdns_https_resolver_update_odoh_config_async_block_invoke : 288 -> 276
~ ____mdns_resolver_invalidate_internal_block_invoke : 80 -> 68
~ ____mdns_session_invalidate_block_invoke : 88 -> 76
~ __mdns_session_invalidate_internal : 104 -> 92
~ __mdns_querier_conclude_ex : 2520 -> 2512
~ __mdns_resolver_deregister_querier : 200 -> 188
~ ____mdns_querier_conclude_ex_block_invoke : 96 -> 84
~ ___mdns_resolver_set_up_server_path_evaluator_block_invoke.51 : 60 -> 48
~ __mdns_resolver_create_oneshot_timer : 112 -> 100
~ ____mdns_querier_initiate_send_block_invoke : 308 -> 296
~ ____mdns_querier_conclude_with_response_async_block_invoke : 80 -> 68
~ ____mdns_querier_conclude_with_error_async_block_invoke : 72 -> 60
~ __pqw_qname_item_free : 64 -> 52
~ __mdns_resolver_session_receive : 432 -> 420
~ __mdns_common_session_finish : 132 -> 120
~ ____mdns_connection_session_schedule_receive_block_invoke : 252 -> 240
~ __mdns_common_session_invoke_receive : 160 -> 148
~ ____mdns_connection_session_send_block_invoke : 124 -> 112
~ __mdns_udp_socket_session_cancel_handler : 72 -> 60
~ ____mdns_url_session_schedule_interrupt_for_oldest_active_odoh_session_block_invoke : 100 -> 88
~ ____mdns_common_session_make_ready_async_block_invoke : 112 -> 100
~ __mdns_url_session_handle_connection_no_longer_pending : 132 -> 120
~ __mdns_resolver_generate_error_event : 136 -> 124
~ ____mdns_resolver_generate_event_block_invoke : 100 -> 88
~ ____mdns_common_session_terminate_async_block_invoke : 68 -> 56
~ __mdns_querier_handle_stream_termination : 180 -> 168
~ __mdns_resolver_note_responsiveness : 936 -> 932
~ __mdns_querier_handle_bad_rcode : 336 -> 312
~ __mdns_resolver_generate_connection_event : 120 -> 108
~ ____mdns_resolver_start_serverless_queries_async_block_invoke : 156 -> 144
~ ____mdns_resolver_schedule_fast_recovery_check_block_invoke : 92 -> 80
~ __mdns_resolver_start_querier : 144 -> 120
~ ____mdns_session_activate_block_invoke : 132 -> 120
~ __mdns_querier_session_receive : 952 -> 940
~ __mdns_querier_send_query_immediate : 2204 -> 2188
~ __mdns_resolver_start_probe_querier : 332 -> 320
~ __mdns_querier_finalize : 168 -> 156
~ __mdns_querier_activate : 1040 -> 1028
~ ____mdns_querier_conclude_async_block_invoke : 72 -> 60
~ _LNT_SendDiscoveryMsg : 396 -> 384
~ _handleLNTDeviceDescriptionResponse : 1116 -> 1104
~ _handleLNTPortMappingResponse : 904 -> 880
~ _AllocAndCopy : 192 -> 168
~ _UpdateDebugState : 416 -> 404
~ _HelperLog : 136 -> 124
~ ___SendDict_ToServer_block_invoke : 348 -> 336
~ _DNSMessageExtractRData : 1416 -> 1380
~ _DNSMessageCollapse : 1504 -> 1496
~ _DomainNameFromString : 300 -> 296
~ __dnssec_obj_rr_nsec3_compare : 796 -> 784
~ __mdns_dso_session_copy_description : 72 -> 60
~ ___mdns_dso_session_add_activity_block_invoke : 104 -> 92
~ ___mdns_dso_session_remove_activity_block_invoke : 144 -> 132
~ ___mdns_dso_session_send_block_invoke : 164 -> 152
~ ___mdns_dso_client_session_add_nw_endpoints_block_invoke.13 : 72 -> 60
~ __mdns_dso_client_session_connect_or_delay_reconnecting : 1464 -> 1460
~ ____mdns_dso_session_schedule_user_receive_block_invoke : 128 -> 116
~ __mdns_dso_session_close_internal : 200 -> 188
~ ____mdns_dso_session_create_tls_nw_parameters_block_invoke_2 : 96 -> 84
~ ____mdns_dso_client_session_prepare_session_block_invoke : 120 -> 108
~ __mdns_dso_client_session_accept_keepalive_message : 300 -> 292
~ ____mdns_dso_client_session_schedule_user_event_block_invoke : 100 -> 88
~ __system_util_log : 84 -> 72
~ ____system_util_log_block_invoke : 72 -> 60
~ ____mdns_create_dns_over_bytestream_framer_block_invoke_3 : 132 -> 120
~ _mdns_timing_defense_pick_delay_bucket : 192 -> 180
~ _QueryRecordClientRequestStop : 92 -> 80
~ _QueryRecordOpCallback : 4216 -> 4204
~ _QueryRecordOpRestartUnicastQuestion : 264 -> 252
~ _ProxyUDPCallback : 208 -> 196
~ _ProxyTCPCallback : 456 -> 420
~ _FreeDNSProxyClient : 88 -> 76
~ _SendError : 272 -> 256
~ _DNSProxyPrepareOmsg : 268 -> 264
~ _ProxyClientCallback : 3236 -> 3220
~ __dnssec_fetch_key_records : 2536 -> 2524
~ ____mhc_bpf_open_reply_handler_block_invoke : 88 -> 76
~ _mDNSPlatformDisposeProxyContext : 92 -> 80
~ _ProxyTCPSocketCallBack : 1116 -> 1104
~ -[OS_mrcs_object description] : 48 -> 36
~ -[OS_mrcs_object debugDescription] : 48 -> 36
~ -[OS_mrcs_object redactedDescription] : 48 -> 36
~ -[OS_mdns_object description] : 48 -> 36
~ -[OS_mdns_object debugDescription] : 48 -> 36
~ -[OS_mdns_object redactedDescription] : 48 -> 36
~ -[OS_mdns_object isEqual:] : 144 -> 132
~ ____mdns_push_server_add_subscriber_block_invoke_2 : 468 -> 444
~ __mdns_push_server_send_pending_subscribe_requests : 684 -> 672
~ ___mdns_subscriber_process_change_notifications_block_invoke.31 : 124 -> 112
~ ____mdns_subscriber_handle_timeout_block_invoke : 72 -> 60
~ ___dnssd_analytics_init_block_invoke : 68 -> 56
~ __mdns_dso_subscribe_message_builder_create_primary_tlv : 324 -> 312
~ __mdns_trust_log : 84 -> 72
~ ___destructor_8_s32_s48_s56_s64 : 76 -> 64
~ ____mdns_trust_log_block_invoke : 72 -> 60
~ __mdns_dso_server_endpoint_is_usable_now : 272 -> 268
~ _ref_count_obj_release : 104 -> 92
~ _resolved_cache_delete : 184 -> 172
```

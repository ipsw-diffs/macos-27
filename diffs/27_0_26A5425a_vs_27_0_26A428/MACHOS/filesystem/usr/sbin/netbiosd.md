## netbiosd

> `/usr/sbin/netbiosd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x277e8
+  __TEXT.__text: 0x26f50
   __TEXT.__auth_stubs: 0xfc0
   __TEXT.__init_offsets: 0x18
   __TEXT.__const: 0x758
   __TEXT.__gcc_except_tab: 0x1710
   __TEXT.__oslogstring: 0x16b2
   __TEXT.__cstring: 0xf2ca
-  __TEXT.__unwind_info: 0xfa8
+  __TEXT.__unwind_info: 0x11f8
   __DATA_CONST.__const: 0x7c90
   __DATA_CONST.__cfstring: 0x340
   __DATA_CONST.__auth_got: 0x7e8
Functions:
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZL27netbios_prefs_load_timer_fnP15nb_chore_base_t : 168 -> 144
~ __Z28cifsd_network_initializationv : 364 -> 352
~ __Z28release_cifsd_workgroup_namePFvPvES_ : 320 -> 308
~ __ZL28release_cifsd_name_fn_commonP11rel_state_t : 76 -> 64
~ __Z30netbiosd_update_active_subnetsRN4nbns11subnet_listE : 2120 -> 2060
~ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 656 -> 536
~ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 336 -> 264
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__16vectorIP11sockaddr_dlNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 196 -> 192
~ __ZN4nbns11name_recordD0Ev : 56 -> 44
~ __ZN4nbns10names_listD0Ev : 56 -> 44
~ __ZNK8platform12locked_tableIPK12netbios_nameNS_11counted_ptrIN4nbns11name_recordEEE12lt_nb_fqnameE4findERKS3_ : 196 -> 184
~ __ZN4nbns10names_list14tell_observersINS0_18name_added_messageEEEvRKT_ : 124 -> 112
~ __ZN4nbns10names_list14tell_observersINS0_20name_removed_messageEEEvRKT_ : 124 -> 112
~ __ZN8platform12locked_tableIPK12netbios_nameNS_11counted_ptrIN4nbns11name_recordEEE12lt_nb_fqnameE5clearEv : 112 -> 100
~ __ZN4nbns10names_list15attach_observerERN8platform11counted_ptrINS_19names_list_observerEEE : 100 -> 88
~ __ZNK4nbns10names_list9dump_listEv : 476 -> 464
~ __ZNSt3__110__list_impIN8platform11counted_ptrIN4nbns19names_list_observerEEENS_9allocatorIS5_EEE13__delete_nodeB9nqe220106EPNS_11__list_nodeIS5_PvEE : 108 -> 96
~ __ZNSt3__16vectorIN8platform11counted_ptrIN4nbns11name_recordEEENS_9allocatorIS5_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns10names_list18name_added_messageERN8platform11counted_ptrINS1_19names_list_observerEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 228 -> 216
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns10names_list20name_removed_messageERN8platform11counted_ptrINS1_19names_list_observerEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 228 -> 216
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns10names_list21names_cleared_messageERN8platform11counted_ptrINS1_19names_list_observerEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 228 -> 216
~ __ZNSt3__110__pop_heapB9nqe220106INS_17_ClassicAlgPolicyEN4nbns26lt_name_record_expirationsENS_11__wrap_iterIPN8platform11counted_ptrINS2_11name_recordEEEEEEEvT1_SB_RT0_NS_15iterator_traitsISB_E15difference_typeE : 424 -> 412
~ __ZNSt3__19__sift_upB9nqe220106INS_17_ClassicAlgPolicyERN4nbns26lt_name_record_expirationsENS_11__wrap_iterIPN8platform11counted_ptrINS2_11name_recordEEEEEEEvT1_SC_OT0_NS_15iterator_traitsISC_E15difference_typeE : 668 -> 656
~ __ZNSt3__16vectorIN8platform11counted_ptrIN4nbns11name_recordEEENS_9allocatorIS5_EEE24__emplace_back_slow_pathIJRKS5_EEEPS5_DpOT_ : 300 -> 296
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns10names_list16detached_messageERN8platform11counted_ptrINS1_19names_list_observerEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 228 -> 216
~ __ZN4nbns6subnetD2Ev : 336 -> 324
~ __ZN4nbns6subnetD0Ev : 56 -> 44
~ __ZNK4nbns6subnet11dump_subnetEv : 588 -> 576
~ __ZN8platform15basic_transport9keepaliveEy : 140 -> 128
~ __ZN8platform13basic_serviceIN4nbns12nb_transportEE15erase_transportERNS_11counted_ptrINS_15basic_transportEEE : 132 -> 120
~ __ZN8platform13basic_serviceIN4nbns12nb_transportEED0Ev : 56 -> 44
~ __ZN8platform13basic_serviceIN4nbns12nb_transportEE8shutdownEv : 120 -> 108
~ _GLOBAL__sub_I_nbns_subnet.cpp : 160 -> 148
~ __ZN4nbns11subnet_listD0Ev : 56 -> 44
~ __ZNK4nbns11subnet_list11find_subnetEPK7in_addrNS_13address_matchE : 376 -> 364
~ __ZNK4nbns11subnet_list11find_subnetERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 424 -> 412
~ __ZNK4nbns11subnet_list12first_subnetEv : 132 -> 120
~ __ZN4nbns11subnet_list13clear_subnetsEv : 280 -> 268
~ __ZN4nbns11subnet_list13check_subnetsEv : 144 -> 132
~ __ZN4nbns9workgroupD0Ev : 56 -> 44
~ __ZN4nbns9workgroup14remove_expiredEv : 76 -> 64
~ __ZN4nbns9workgroup6add_bbERN8platform11counted_ptrINS_11name_recordEEE : 244 -> 232
~ __ZN4nbns9workgroup12get_bb_namesEiPNS_10names_list13NB_NAMES_LISTE : 388 -> 376
~ __ZN4nbns14workgroup_list16clear_workgroupsEv : 296 -> 284
~ __ZN4nbns14workgroup_listD0Ev : 56 -> 44
~ __ZNK4nbns14workgroup_list15find_wg_with_mbEv : 320 -> 308
~ __ZN4nbns14workgroup_list17recalc_expirationEv : 384 -> 372
~ __Z20process_nbtdg_packetPK14nbtdg_packet_t : 796 -> 784
~ __ZL29nbtdg_send_deferred_finish_fnP15nb_chore_base_tPv : 84 -> 72
~ __ZL18nbtdg_ns_finish_fnP15nb_chore_base_tPv : 244 -> 232
~ __ZL16send_nbtdg_errori15nbt_node_type_t7in_addri13nbtdg_error_tS0_i : 108 -> 96
~ __Z11nbtns_queryPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 124 -> 112
~ __ZL41queue_and_send_nbtns_query_to_name_serverPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 224 -> 200
~ __Z22nbtns_query_bcast_onlyPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 132 -> 120
~ __ZL34no_ifaces_status_deferred_callbackP15nb_chore_base_tPv : 68 -> 56
~ __ZL21nbt_status_chore_dtorP15nb_chore_base_t : 64 -> 52
~ __Z14nbtns_registerPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 556 -> 532
~ __Z25nbtns_register_ucast_onlyPK12netbios_name7in_addriPFvP15nb_chore_base_tPvES5_ : 148 -> 136
~ __Z13nbtns_releasePK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 584 -> 560
~ __Z24nbtns_release_ucast_onlyPK12netbios_name7in_addriPFvP15nb_chore_base_tPvES5_ : 156 -> 144
~ __Z13nbtns_refreshPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 384 -> 372
~ __Z20process_nbtns_packetPK14nbtns_packet_t : 1776 -> 1740
~ __ZL33no_ifaces_query_deferred_callbackP15nb_chore_base_tPv : 68 -> 56
~ __ZL21nbt_query_response_fnP15nb_chore_base_tPKv : 1144 -> 1132
~ __ZL20nbt_query_chore_dtorP15nb_chore_base_t : 64 -> 52
~ __ZL20name_server_check_fnP15nb_chore_base_tPv : 236 -> 224
~ __ZL24sort_status_resrec_namesP14nbtns_resrec_t : 88 -> 84
~ __ZL36no_ifaces_register_deferred_callbackP15nb_chore_base_tPv : 104 -> 92
~ __ZL24nbt_register_response_fnP15nb_chore_base_tPKv : 440 -> 428
~ __ZL23nbt_register_timeout_fnP15nb_chore_base_t : 268 -> 256
~ __ZL44queue_and_send_nbtns_register_to_name_serverPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 236 -> 212
~ __ZL35no_ifaces_release_deferred_callbackP15nb_chore_base_tPv : 92 -> 80
~ __ZL23nbt_release_response_fnP15nb_chore_base_tPKv : 124 -> 112
~ __ZL22nbt_release_timeout_fnP15nb_chore_base_t : 268 -> 256
~ __ZL22nbt_release_chore_dtorP15nb_chore_base_t : 64 -> 52
~ __ZL43queue_and_send_nbtns_release_to_name_serverPK12netbios_nameiPFvP15nb_chore_base_tPvES4_ : 224 -> 200
~ __ZL20process_register_reqPK14nbtns_packet_t : 284 -> 272
~ __Z22nb_deferred_chore_dtorP15nb_chore_base_t : 76 -> 64
~ __ZL18enqueue_chore_nodeP15nb_chore_list_tP15nb_chore_node_t : 112 -> 100
~ __Z19nb_timer_chore_dtorP15nb_chore_base_t : 76 -> 64
~ __Z13nb_chore_dtorP15nb_chore_base_tb : 220 -> 196
~ __Z16nbtns_chore_dtorP15nb_chore_base_t : 88 -> 76
~ __Z16nbtdg_chore_dtorP15nb_chore_base_t : 76 -> 64
~ __Z25nb_chore_timer_processingd : 428 -> 416
~ __Z15dump_all_choresv : 56 -> 44
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _GLOBAL__sub_I_netbios_chore.cpp : 96 -> 84
~ __Z23add_to_local_name_tablePK12netbios_nameii : 216 -> 204
~ __Z31local_name_table_apply_functionPFvPK12netbios_nameP17local_name_node_tPvES4_ : 52 -> 40
~ __Z32add_nb_name_to_remote_name_tablePK14nbtns_resrec_t16nb_name_source_t : 708 -> 696
~ __ZL21NBNameCopyDescriptionPKv : 84 -> 72
~ __ZNSt3__15dequeIP12nbt_packet_tNS_9allocatorIS2_EEED2B9nqe220106Ev : 172 -> 160
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns11subnet_list24broadcast_packet_messageERN8platform11counted_ptrINS1_6subnetEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 164 -> 152
~ __ZNSt3__18__invokeB9nqe220106IJRN4nbns11subnet_list11dump_subnetERN8platform11counted_ptrINS1_6subnetEEEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_ : 160 -> 148
~ __ZNSt3__15dequeIP12nbt_packet_tNS_9allocatorIS2_EEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPP12nbt_packet_tNS_9allocatorIS3_EEE12emplace_backIJRS3_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPP12nbt_packet_tRNS_9allocatorIS3_EEE12emplace_backIJS3_EEEvDpOT_ : 256 -> 260
~ _GLOBAL__sub_I_netbios_network_interface.cpp : 144 -> 132
~ __Z15dump_nbt_packetiPK12nbt_packet_t : 2720 -> 2680
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __Z15nbt_packet_dtorP12nbt_packet_t : 132 -> 120
~ __ZL17dump_nbtns_resrecP10__CFStringPK14nbtns_resrec_t : 288 -> 276
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __ZL17get_nbtns_resrecsPP14nbtns_resrec_tjPKvmm : 624 -> 628
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_2 : 24 -> 12
~ __Z26nbns_schedule_renew_all_bbj : 104 -> 92
~ __Z34nbns_schedule_renew_all_wg_domainsj : 104 -> 92
~ __Z17nbns_reset_timersv : 72 -> 60
~ __Z24netbiosd_wake_from_sleepv : 100 -> 88
~ __ZL24nbns_reset_runloop_timerv : 252 -> 228
~ __Z28netbiosd_release_local_namesv : 108 -> 96
~ __ZN8platform13basic_serviceIN4nbns12nb_transportEE21disconnect_transportsEv : 520 -> 508
~ __ZNSt3__16vectorINS_4pairINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEiEENS5_IS8_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZL21nbns_list_maintenancev : 172 -> 156
~ __ZL28send_smb_server_announcementPK18server_ann_state_t : 1064 -> 1056
~ __ZL25host_announcement_dtor_fnP15nb_chore_base_t : 60 -> 48
~ __Z39smb_browse_chore_stop_host_announcementP13nbtdg_chore_t : 92 -> 80
~ __ZL39backup_browser_cache_hit_deferred_choreP15nb_chore_base_tPv : 112 -> 96
~ __ZL27backup_browser_list_time_fnP15nb_chore_base_t : 256 -> 232
~ __ZL30verify_backup_browser_query_fnP15nb_chore_base_tPv : 204 -> 192
~ __ZL31verify_backup_browser_status_fnP15nb_chore_base_tPv : 256 -> 244
~ _GLOBAL__sub_I_smb_browsing_protocol.cpp : 180 -> 168
~ __Z17make_netbios_namePKc14nb_name_type_t : 96 -> 88
~ __ZN4nbns14mdns_name_infoD0Ev : 152 -> 140
~ __ZN4nbns14mdns_name_info17update_txt_recordERNS_12mdns_sessionE : 392 -> 380
~ __ZN4nbns14mdns_name_info16stop_advertisingERNS_12mdns_sessionE : 120 -> 108
~ __ZNK4nbns14mdns_name_info9dump_infoEv : 476 -> 464
~ __ZNK4nbns19names_list_observer13dump_observerEv : 152 -> 140
~ __Z18create_name_recordRK12netbios_name16nb_name_source_t : 284 -> 272
~ __Z16create_workgroupRK12netbios_name : 264 -> 252
~ __Z21strip_trailing_spacesPc : 88 -> 92
~ __ZN4nbns26bonjour_workgroup_observerD0Ev : 56 -> 44
~ __ZN4nbns26bonjour_workgroup_observer8detachedEPK12netbios_name : 124 -> 112
~ __ZN8platform12locked_tableIPK12netbios_nameNS_11counted_ptrIN4nbns14mdns_name_infoEEE12lt_nb_fqnameE4findERKS3_ : 196 -> 184
~ __ZN8platform12locked_tableIPK12netbios_nameNS_11counted_ptrIN4nbns14mdns_name_infoEEE12lt_nb_fqnameE5clearEv : 112 -> 100
~ __ZNK4nbns26bonjour_workgroup_observer13dump_observerEv : 408 -> 396
~ __ZNK8platform12locked_tableIPK12netbios_nameNS_11counted_ptrIN4nbns14mdns_name_infoEEE12lt_nb_fqnameE8for_eachINS5_14call_mdns_dumpEEET_SC_ : 204 -> 192
~ __ZN8platform22pthread_resource_errorD0Ev : 56 -> 44
~ __ZN8platform22pthread_latch_variable9wait_secsEj : 192 -> 180
~ ____ZN4nbns12mdns_session11dns_connectEv_block_invoke_2 : 88 -> 76
~ __ZN4nbns12nb_transportD0Ev : 56 -> 44
~ __Z13renew_wg_infoN8platform11counted_ptrIN4nbns9workgroupEEE15BB_RENEW_TARGET : 1744 -> 1740
~ __ZL11wg_get_infoN8platform11counted_ptrIN4nbns9workgroupEEE15BB_RENEW_TARGET : 2396 -> 2392
~ __ZL30nbb_process_mb_status_responseP15nb_chore_base_tPv : 1228 -> 1224
~ __Z28publish_registered_workgroupPK12netbios_name : 244 -> 232
~ __Z23publish_registered_namePK12netbios_name : 244 -> 232
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZN6darwin14launch_checkinERNS_10launch_jobE : 1380 -> 1376
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ _OUTLINED_FUNCTION_2 : 32 -> 20
```

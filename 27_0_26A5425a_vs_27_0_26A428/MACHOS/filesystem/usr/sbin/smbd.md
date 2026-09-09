## smbd

> `/usr/sbin/smbd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_ntvfs`
- `__TEXT.__dof_smbd`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x7a340
+  __TEXT.__text: 0x7992c
   __TEXT.__auth_stubs: 0x1f80
   __TEXT.__init_offsets: 0x14
   __TEXT.__const: 0x1287

   __TEXT.__cstring: 0xff45
   __TEXT.__dof_ntvfs: 0x1eed
   __TEXT.__dof_smbd: 0x7aa
-  __TEXT.__unwind_info: 0x2178
+  __TEXT.__unwind_info: 0x24e8
   __DATA_CONST.__const: 0xa8c8
   __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__auth_got: 0xfc8
Functions:
~ __Z26smb2_dispatch_tree_connectR11smb_requestPhS1_ : 1132 -> 1124
~ __ZN12smbd_serviceD2Ev : 416 -> 404
~ __ZN12smbd_serviceD0Ev : 56 -> 44
~ __ZN12smbd_service16allocate_sessionEv : 76 -> 64
~ __ZN12smbd_service27disconnect_dequeue_sessionsEPKc : 376 -> 364
~ __ZN12smbd_service24lease_break_timer_rescanEv : 776 -> 772
~ __ZN8platform12locked_tableIyNS_11counted_ptrI11smb_sessionEENSt3__14lessIyEEE4findERKy : 196 -> 184
~ __ZN12smbd_service22invalidate_connectionsEP11__ODTriggerPK10__CFStringS4_S4_S4_ : 548 -> 536
~ __ZN12smbd_service25allTransportsDisconnectedEv : 92 -> 80
~ __ZNSt3__15dequeIyNS_9allocatorIyEEE19__add_back_capacityEv : 468 -> 472
~ __ZNSt3__114__split_bufferIPyNS_9allocatorIS1_EEE12emplace_backIJRS1_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPyRNS_9allocatorIS1_EEE12emplace_backIJS1_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__15dequeIyNS_9allocatorIyEEED2B9nqe220106Ev : 172 -> 160
~ __ZN5ntvfs10lease_openD0Ev : 152 -> 140
~ __ZN8platform13basic_serviceI13smb_transportED0Ev : 56 -> 44
~ __ZNSt3__116allocator_traitsINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_6vectorIhNS1_IhEEEEN8platform11counted_ptrI18client_tbl_entry_tEEEEPvEEEEE7destroyB9nqe220106INS_4pairIKS6_SA_EELi0EEEvRSE_PT_ : 128 -> 116
~ __ZN8platform13basic_serviceI13smb_transportE8shutdownEv : 120 -> 108
~ __ZNSt3__16vectorIhNS_9allocatorIhEEE18__assign_with_sizeB9nqe220106INS_17_ClassicAlgPolicyEPKhS7_EEvT0_T1_l : 308 -> 304
~ __ZNSt3__16__treeINS_12__value_typeINS_6vectorIhNS_9allocatorIhEEEEPN5ntvfs13lease_table_tEEENS_19__map_value_compareIS5_NS_4pairIKS5_S8_EENS_4lessIS5_EEEENS3_ISD_EEE12__find_equalB9nqe220106IS5_EENSB_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSO_EERKT_ : 224 -> 220
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_6vectorIhNS1_IhEEEEPN5ntvfs13lease_table_tEEEPvEEEEEclB9nqe220106EPSC_ : 100 -> 88
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_6vectorIhNS1_IhEEEEN8platform11counted_ptrIN5ntvfs11ntvfs_leaseEEEEEPvEEEEEclB9nqe220106EPSE_ : 156 -> 144
~ __ZNSt3__16vectorIhNS_9allocatorIhEEE18__assign_with_sizeB9nqe220106INS_17_ClassicAlgPolicyEPhS6_EEvT0_T1_l : 276 -> 272
~ __ZNSt3__130__default_three_way_comparatorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES6_vEclB9nqe220106ERKS6_S9_ : 112 -> 108
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEjEEPvEEEEEclB9nqe220106EPSB_ : 100 -> 88
~ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_6vectorIhNS1_IhEEEEN8platform11counted_ptrI18client_tbl_entry_tEEEEPvEEEEEclB9nqe220106EPSD_ : 100 -> 88
~ __ZN8platform15basic_transport9keepaliveEy : 140 -> 128
~ _main : 3596 -> 3592
~ __ZL19smbd_signal_handlerPv : 204 -> 192
~ __ZN8platform12config_value18invalid_conversionD0Ev : 56 -> 44
~ __ZNSt3__112__destroy_atB9nqe220106INS_4pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEN8platform12config_valueEEEEEvPT_ : 108 -> 96
~ __ZNSt3__16vectorIiNS_9allocatorIiEEE24__emplace_back_slow_pathIJiEEEPiDpOT_ : 196 -> 192
~ __ZN8platform16accept_transportINS_13basic_serviceI13smb_transportEEED0Ev : 56 -> 44
~ __ZN8platform15basic_transport9terminateEv : 80 -> 68
~ __ZN8platform13basic_serviceI13smb_transportE15erase_transportERNS_11counted_ptrINS_15basic_transportEEE : 132 -> 120
~ __ZNSt3__16vectorINS_4pairINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEiEENS5_IS8_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZN13smb_transportD2Ev : 116 -> 104
~ __ZN13smb_transportD0Ev : 56 -> 44
~ __ZN13smb_transport10disconnectEv : 476 -> 464
~ __ZN11smb_sessionD0Ev : 56 -> 44
~ __ZN11smb_session17release_resourcesEv : 472 -> 460
~ __ZN8platform12locked_tableIiNS_11counted_ptrIN5ntvfs4treeEEENSt3__14lessIiEEE5clearEv : 112 -> 100
~ __ZN8platform12locked_tableIiNS_11counted_ptrIN5ntvfs4treeEEENSt3__14lessIiEEE4findERKi : 196 -> 184
~ __ZN11smb_session22notify_server_shutdownEj : 176 -> 164
~ __ZN11smb_session29notify_server_shutdown_cancelEv : 168 -> 156
~ __ZN9sess_infoD0Ev : 128 -> 116
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ __Z23smb1_dispatch_read_andxR11smb_requestPhS1_ : 1312 -> 1300
~ __ZL16activate_signingRK11smb_requestRN8platform11counted_ptrI11smb_sessionEE : 636 -> 628
~ __ZL22smb1_dispatch_compoundP13smb_transportPhS1_ : 1224 -> 1228
~ __Z28smb1_notify_completion_replyPv : 784 -> 772
~ __ZN15smbd_statistics14smbd_analytics19enableSendAnalyticsEv : 288 -> 276
~ __ZN15smbd_statistics14smbd_analytics18sendTelemetryEventEv : 220 -> 208
~ __ZN15smbd_statistics14smbd_analytics24addSMB1SessionStatisticsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEb : 72 -> 60
~ __ZN15smbd_statistics14smbd_analytics20sendSessionAnalyticsENS_15SessionAuthEnumENS_18SessionDialectEnumEb : 236 -> 224
~ __ZN15smbd_statistics14smbd_analytics20addSessionStatisticsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEtb : 96 -> 84
~ __ZN15smbd_statistics14smbd_analytics23addOplockLevelStatisticEh : 248 -> 236
~ _GLOBAL__sub_I_smbd_analytics.cpp : 668 -> 656
~ __ZN13smbd_pwr_ctrl13terminate_pwrEv : 204 -> 192
~ __ZN13smbd_pwr_ctrl13share_connectERN8platform11counted_ptrIN5ntvfs4treeEEE : 116 -> 104
~ __ZN13smbd_pwr_ctrl16share_disconnectERN8platform11counted_ptrIN5ntvfs4treeEEE : 116 -> 104
~ __ZN13smbd_pwr_ctrl22process_ipcshare_timerEv : 108 -> 96
~ __ZN13smbd_pwr_ctrl25powerSourceChangeCallbackEv : 84 -> 72
~ __ZN8platform13basic_serviceI13smb_transportE38disconnect_transports_for_system_sleepEv : 548 -> 536
~ __Z19smb2_dispatch_ioctlR11smb_requestPhS1_ : 3512 -> 3508
~ __ZN12asn1_encoder9pop_scopeEv : 384 -> 376
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_2 : 24 -> 12
~ __ZN17ntlmssp_mechanismD2Ev : 112 -> 100
~ __ZN17ntlmssp_mechanismD0Ev : 56 -> 44
~ __ZN17ntlmssp_mechanism25receive_ntlmssp_negotiateERK17ntlmssp_negotiateRN8platform11heap_bufferE : 1248 -> 1264
~ __ZN16spnego_mechanismD2Ev : 124 -> 112
~ __ZN16spnego_mechanismD0Ev : 56 -> 44
~ __ZNKSt3__114default_deleteIN12asn1_decoder3oidEEclB9nqe220106EPS2_ : 104 -> 92
~ __ZN16gssapi_mechanismD0Ev : 56 -> 44
~ __ZNSt3__16vectorIPcNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __ZN11ipc_controlD0Ev : 152 -> 140
~ __ZN17completion_recordD0Ev : 56 -> 44
~ __ZN17completion_record15cancel_notifierEPS_ : 356 -> 344
~ __ZN17completion_record6cancelEPv : 496 -> 464
~ __ZN17notify_completionD0Ev : 152 -> 140
~ __ZN13svrmsg_recordD0Ev : 112 -> 100
~ ____ZL15set_up_notifierR11smb_requestN8platform11counted_ptrIN5ntvfs11file_handleEEENS3_15file_operations26set_notification_argumentsEm_block_invoke : 180 -> 168
~ __Z20smb2_sign_send_replyR11smb_request : 68 -> 56
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ __ZN17darwin_sharepointD0Ev : 56 -> 44
~ __Z19find_ipc_sharepointPK10__CFStringRj : 552 -> 540
~ _GLOBAL__sub_I_darwin_share.cpp : 96 -> 84
~ __ZN6darwin16cfstring_convertEPK10__CFStringj : 416 -> 404
~ __ZN8platform12config_value20placeholder_specificINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEED0Ev : 112 -> 100
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRKS6_EEEPS6_DpOT_ : 320 -> 316
~ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZN6darwin14launch_checkinERNS_10launch_jobE : 1380 -> 1376
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform11random_fillEPhS0_ : 40 -> 28
~ __ZN8ipcArrayD0Ev : 56 -> 44
~ __ZN8ipcArray3addEPvm : 80 -> 68
~ __ZN8ipcReplyD0Ev : 56 -> 44
~ __ZN10ipcRequestD0Ev : 56 -> 44
~ ___copy_helper_block_e8_32b40r : 80 -> 68
~ ___destroy_helper_block_e8_32b40r : 68 -> 56
~ __ZN10ipcRequest10send_replyEv : 80 -> 68
~ __ZN10darwin_xpc17make_xpc_listenerEPcR17ipc_callback_info : 316 -> 304
~ __ZN10darwin_xpcD0Ev : 56 -> 44
~ __Z16DsRoleFreeMemoryPv : 52 -> 40
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __Z21ConvertSidToStringSidPK4_SIDPPh : 708 -> 668
~ __Z15TokenFromHandleP8NtObject : 88 -> 68
~ __Z19GetTokenInformationP8NtObject24_TOKEN_INFORMATION_CLASSPvmPm : 596 -> 584
~ __Z17EqualAnonymousSidPK4_SID : 212 -> 200
~ __Z23ImpersonateLoggedOnUserP8NtObject : 112 -> 100
~ __Z25ImpersonateAnonymousTokenv : 176 -> 164
~ __ZN8platform14tls_exhaustionD0Ev : 56 -> 44
~ _GLOBAL__sub_I_scoped_credential.cpp : 88 -> 76
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __Z16make_rpc_bindingPKcS0_ : 1144 -> 1104
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 196 -> 192
~ __ZN6darwin12darwin_tokenD2Ev : 96 -> 84
~ __ZN6darwin12darwin_tokenD0Ev : 56 -> 44
~ __Z29NtCreateTokenFromExportedNamejPKvm : 284 -> 272
~ __Z31NtCreateTokenFromValidationInfojPK21_KERB_VALIDATION_INFO : 264 -> 252
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __Z19NtObjectDereferenceP8NtObject : 96 -> 84
~ __ZN3smb7extractERPhRKS0_RNS_27FILE_RENAME_INFORMATION_SMBES3_ : 136 -> 132
~ __ZN3smb7extractERPhRKS0_RNS_28FILE_RENAME_INFORMATION_SMB2ES3_ : 144 -> 140
~ __ZN3smb7extractERPhRKS0_RNS_26FILE_UNIX_LINK_INFORMATIONES3_ : 212 -> 192
~ __ZN3smb7extractERPhRKS0_RNS_27REPARSE_SYMLINK_DATA_BUFFERES3_ : 328 -> 308
~ __ZN3smb7extractERPhRKS0_RNS_15FSCTL_PIPE_WAITES3_ : 112 -> 108
~ __ZN4smb27extractERPhRKS0_RNS_20tree_connect_requestES3_ : 152 -> 148
~ __ZN4smb27extractERPhRKS0_RNS_14create_requestES3_ : 508 -> 504
~ __ZN4smb27extractERPhRKS0_RNS_23query_directory_requestES3_ : 252 -> 248
~ __ZN3smb7extractERPhRKS0_RNS_29session_setup_andx_request_exES3_ : 392 -> 380
~ __ZN3smb7extractERPhRKS0_RNS_25tree_connect_andx_requestES3_ : 312 -> 300
~ __ZN3smb7extractERPhRKS0_RNS_22nt_create_andx_requestES3_ : 320 -> 316
~ __ZN3smb7extractERPhRKS0_RNS_23com_transaction_requestES3_ : 584 -> 588
~ __ZN3smb7extractERPhRKS0_RNS_24com_transaction2_requestES3_ : 496 -> 500
~ __ZN3smb7extractERPhRKS0_RNS_23com_nt_transact_requestES3_ : 464 -> 468
~ __ZN3smb7extractERPhRKS0_RNS_18com_rename_requestES3_ : 276 -> 264
~ __ZN5ntvfs10waiting_opD0Ev : 100 -> 88
~ __ZN5ntvfs11RHOpContextD0Ev : 152 -> 140
~ __ZN5ntvfs10fsa_oplock29recompute_shared_oplock_stateEv : 384 -> 372
~ __ZN5ntvfsL22allocate_control_tableEv : 144 -> 136
~ __ZN6darwin20interpret_timestampsINS_22create_file_attributesEN5ntvfs15path_operations14create_resultsEEEvRT0_RKT_ : 96 -> 84
~ __ZN5ntvfs18file_control_block28release_parent_control_blockEv : 152 -> 140
~ __ZN5ntvfs18file_control_block25detach_file_handle_lockedEN8platform11counted_ptrINS_11file_handleEEE : 244 -> 232
~ __ZN5ntvfs18file_control_block31set_parent_control_block_lockedEN8platform11counted_ptrIS0_EE : 188 -> 176
~ __ZN5ntvfs18file_control_block21remove_locks_on_closeEyy : 172 -> 160
~ __ZN5ntvfs18file_control_block20send_smb_lease_breakEN8platform11counted_ptrINS_11file_handleEEEjbj : 208 -> 196
~ ___destroy_helper_block_e8_32r40c58_ZTSN8platform11counted_ptrIN5ntvfs18file_control_blockEEE : 112 -> 100
~ __ZN5ntvfs18file_control_blockD0Ev : 56 -> 44
~ __ZNSt3__110__list_impIN8platform11counted_ptrIN5ntvfs11RHOpContextEEENS_9allocatorIS5_EEE13__delete_nodeB9nqe220106EPNS_11__list_nodeIS5_PvEE : 108 -> 96
~ __ZNSt3__110__list_impIN8platform11counted_ptrIN5ntvfs11file_handleEEENS_9allocatorIS5_EEE13__delete_nodeB9nqe220106EPNS_11__list_nodeIS5_PvEE : 108 -> 96
~ __ZN5ntvfs18file_control_block15child_containerD0Ev : 152 -> 140
~ __ZN8platform13simple_waiter15wait_for_signalEv : 100 -> 88
~ __ZN8platform13simple_waiter5resetEv : 108 -> 96
~ __ZN8platform13simple_waiter13signal_waiterEv : 76 -> 64
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev : 288 -> 248
~ __ZN6darwin16darwin_directoryD2Ev : 160 -> 148
~ __ZN6darwin16darwin_directoryD0Ev : 56 -> 44
~ __ZThn8_N6darwin16darwin_directoryD0Ev : 60 -> 48
~ __ZN6darwin16darwin_directory10close_fileEv : 84 -> 72
~ __ZN6darwin20interpret_timestampsINS_17dirent_attributesEN3smb26FILE_DIRECTORY_INFORMATIONEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin20interpret_timestampsINS_17dirent_attributesEN3smb32FIND_FILE_UNIX_INFO2_INFORMATIONEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin11darwin_fileD2Ev : 168 -> 156
~ __ZN6darwin11darwin_fileD0Ev : 56 -> 44
~ __ZThn8_N6darwin11darwin_fileD0Ev : 60 -> 48
~ __ZN6darwin11darwin_file10flush_fileEv : 112 -> 100
~ __ZN6darwin11darwin_file15flush_fullfsyncEv : 132 -> 120
~ __ZN6darwinL11file_resizeEPNS_11darwin_fileEy : 388 -> 376
~ __ZN6darwin22file_update_cached_eofERN8platform11counted_ptrIN5ntvfs18file_control_blockEEEyy : 144 -> 132
~ __ZN6darwin20interpret_timestampsINS_16basic_attributesEN3smb22FILE_BASIC_INFORMATIONEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin20interpret_timestampsINS_14all_attributesEN3smb29FILE_NETWORK_OPEN_INFORMATIONEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin20interpret_timestampsINS_18smb_all_attributesEN3smb24FILE_ALL_INFORMATION_SMBEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin20interpret_timestampsINS_14all_attributesEN3smb27FILE_UNIX_INFO2_INFORMATIONEEEvRT0_RKT_ : 96 -> 84
~ __ZN6darwin11darwin_file25increment_file_open_countEv : 156 -> 144
~ __ZN6darwin11darwin_file25decrement_file_open_countEv : 192 -> 180
~ __ZN6darwin11darwin_file26increment_file_write_countEv : 156 -> 144
~ __ZN6darwin11darwin_file26decrement_file_write_countEv : 192 -> 180
~ __ZN6darwin11darwin_treeD2Ev : 152 -> 140
~ __ZN6darwin11darwin_treeD0Ev : 56 -> 44
~ __ZThn8_N6darwin11darwin_treeD0Ev : 60 -> 48
~ __ZN5ntvfs11ntvfs_leaseD0Ev : 56 -> 44
~ __ZN5ntvfs11ntvfs_lease28set_all_handles_oplock_stateENS_11file_handle11OplockStateE : 292 -> 280
~ __ZN5ntvfs17compare_directoryEPKNS_8pathnameES2_ : 128 -> 124
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ __ZN15socket_ipc_treeD1Ev : 120 -> 108
~ __ZThn8_N15socket_ipc_treeD1Ev : 116 -> 104
~ __ZN15socket_ipc_treeD0Ev : 140 -> 128
~ __ZN15socket_ipc_tree4bindEPKh : 140 -> 128
~ __ZN17socket_ipc_handleD2Ev : 160 -> 148
~ __ZN17socket_ipc_handleD0Ev : 56 -> 44
~ __ZThn8_N17socket_ipc_handleD0Ev : 60 -> 48
~ __ZN17socket_ipc_handle10write_fileERKN5ntvfs15file_operations15write_argumentsERNS1_13write_resultsE : 116 -> 104
~ __ZNSt3__16vectorI14process_holderNS_9allocatorIS1_EEE16__destroy_vectorclB9nqe220106Ev : 136 -> 124
~ __ZNSt3__19allocatorI14process_holderE7destroyB9nqe220106EPS1_ : 88 -> 76
~ __ZNSt3__16vectorI14process_holderNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 400 -> 396
~ _GLOBAL__sub_I_socket_ipc.cpp : 132 -> 120
~ __ZN6darwin11darwin_brlmD2Ev : 200 -> 188
~ __ZN6darwin11darwin_brlmD0Ev : 56 -> 44
~ __ZThn8_N6darwin11darwin_brlmD0Ev : 60 -> 48
~ __ZN6darwin11unlink_pathEjPKh : 164 -> 152
~ __ZN6darwinL12resolve_uuidERA16_KhRNS_12native_sid_tE : 84 -> 72
~ __ZN6darwin10acl_buffer6resizeEm : 84 -> 72
~ __ZN6darwinL17filesec_clear_aclERNS_14darwin_filesecE : 80 -> 68
~ __ZN6darwinL11resolve_sidERKNS_12native_sid_tERA16_h : 84 -> 72
~ __ZN6darwin12darwin_finfo9read_fileERKN5ntvfs15file_operations14read_argumentsERNS2_12read_resultsE : 460 -> 452
~ __ZN6darwin12darwin_finfo15set_informationERKN5ntvfs15file_operations25set_information_argumentsE : 324 -> 312
~ __ZN6darwin12darwin_finfoD1Ev : 184 -> 172
~ __ZN6darwin12darwin_finfoD0Ev : 204 -> 192
~ __ZThn8_N6darwin12darwin_finfoD1Ev : 184 -> 172
~ __ZThn8_N6darwin12darwin_finfoD0Ev : 204 -> 192
~ __ZN6darwinL10xattr_readEiPKcRN8platform11heap_bufferEy : 312 -> 300
~ __ZN6darwin12darwin_xattr15set_informationERKN5ntvfs15file_operations25set_information_argumentsE : 572 -> 560
~ __ZN6darwin12darwin_xattrD1Ev : 192 -> 180
~ __ZN6darwin12darwin_xattrD0Ev : 212 -> 200
~ __ZThn8_N6darwin12darwin_xattrD1Ev : 192 -> 180
~ __ZThn8_N6darwin12darwin_xattrD0Ev : 212 -> 200
~ _OUTLINED_FUNCTION_0 : 64 -> 52
~ __ZN6darwin16follow_directoryERKN5ntvfs9fsoptionsEPKhb : 376 -> 364
~ __ZN6darwin14kqueue_monitorD0Ev : 56 -> 44
~ __ZN3smb20extract_utf16_stringERPhS0_R10oem_string : 128 -> 132
~ _ZN6darwin11darwin_brlm10write_fileERKN5ntvfs15file_operations15write_argumentsERNS2_13write_resultsE.cold.1 : 80 -> 68
```

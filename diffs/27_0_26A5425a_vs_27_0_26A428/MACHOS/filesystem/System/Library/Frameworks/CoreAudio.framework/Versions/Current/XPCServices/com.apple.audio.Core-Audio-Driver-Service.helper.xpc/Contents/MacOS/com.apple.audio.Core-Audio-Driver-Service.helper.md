## com.apple.audio.Core-Audio-Driver-Service.helper

> `/System/Library/Frameworks/CoreAudio.framework/Versions/Current/XPCServices/com.apple.audio.Core-Audio-Driver-Service.helper.xpc/Contents/MacOS/com.apple.audio.Core-Audio-Driver-Service.helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 482.102.10.0.0
-  __TEXT.__text: 0x1cd60
+  __TEXT.__text: 0x1c944
   __TEXT.__realtime: 0x74
   __TEXT.__auth_stubs: 0xbd0
   __TEXT.__objc_stubs: 0xc00

   __TEXT.__objc_methname: 0x1abc
   __TEXT.__objc_classname: 0x151
   __TEXT.__objc_methtype: 0x1887
-  __TEXT.__unwind_info: 0xa98
+  __TEXT.__unwind_info: 0xaf8
   __DATA_CONST.__const: 0xfa8
   __DATA_CONST.__cfstring: 0x1c0
   __DATA_CONST.__objc_classlist: 0x28
Functions:
~ __ZNSt3__119__shared_weak_count16__release_sharedB9nqe220106Ev : 100 -> 88
~ __ZNSt3__16vectorINS_4pairIjNS_13unordered_mapIj21Custom_Property_TypesNS_4hashIjEENS_8equal_toIjEENS_9allocatorINS1_IKjS3_EEEEEEEENS8_ISD_EEE24__emplace_back_slow_pathIJSD_EEEPSD_DpOT_ : 268 -> 264
~ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIj21Custom_Property_TypesEENS_22__unordered_map_hasherIjNS_4pairIKjS2_EENS_4hashIjEENS_8equal_toIjEEEENS_21__unordered_map_equalIjS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9nqe220106IJS7_EEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlRS6_OS7_E_clEST_SU_ : 948 -> 940
~ +[Core_Audio_XPC_Raw_Transporter object:] : 112 -> 100
~ -[Core_Audio_XPC_Raw_Transporter encodeWithCoder:] : 312 -> 300
~ __ZNSt3__110unique_ptrIN5caulk10concurrent9messengerENS_14default_deleteIS3_EEE5resetB9nqe220106EPS3_ : 76 -> 64
~ __ZNSt3__120__shared_ptr_emplaceIN4AMCP3Log19AMCP_Scope_RegistryENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN4AMCP3Log5ScopeENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZN10applesauce9backtrace10snapshot_NILi64EEC1Ev : 412 -> 408
~ __ZN5boost16exception_detail10clone_implINS0_19error_info_injectorISt13runtime_errorEEED1Ev : 92 -> 80
~ __ZN5boost16exception_detail19error_info_injectorISt13runtime_errorED1Ev : 92 -> 80
~ ___destroy_helper_block_ea8_32c90_ZTSKZ77-[Core_Audio_Driver perform_device_configuration_change:action:change:reply:]E3$_9 : 60 -> 48
~ ___destroy_helper_block_ea8_32c89_ZTSKZ75-[Core_Audio_Driver abort_device_configuration_change:action:change:reply:]E4$_10 : 60 -> 48
~ -[Core_Audio_Driver create_and_start_io_receiver:client_id:nominal_sample_rate:io_buffer_frame_size:work_group_port:io_messenger:] : 7364 -> 7356
~ -[Core_Audio_Driver stop_io:client_id:reply:] : 236 -> 224
~ -[Core_Audio_Driver release_unpacked_cf_objects:qualifier_data:data_type:data:] : 352 -> 340
~ __ZL26unpack_data_from_qualifierN4AMCP3HAL22HAL_Property_Type_CodeEP6NSData : 924 -> 912
~ -[Core_Audio_Driver .cxx_destruct] : 184 -> 172
~ __ZN5boost16exception_detail10clone_implINS0_19error_info_injectorISt13runtime_errorEEED0Ev : 112 -> 100
~ __ZThn16_N5boost16exception_detail10clone_implINS0_19error_info_injectorISt13runtime_errorEEED1Ev : 84 -> 72
~ __ZTv0_n40_N5boost16exception_detail10clone_implINS0_19error_info_injectorISt13runtime_errorEEED1Ev : 112 -> 100
~ __ZN5boost16exception_detail19error_info_injectorISt13runtime_errorED0Ev : 112 -> 100
~ __ZThn16_N5boost16exception_detail19error_info_injectorISt13runtime_errorED1Ev : 84 -> 72
~ __ZN5boost16exception_detail19error_info_injectorISt13runtime_errorED2Ev : 92 -> 80
~ __ZN5boost16exception_detail12refcount_ptrINS0_20error_info_containerEE5adoptEPS2_ : 136 -> 124
~ __ZZNSt3__16vectorIN4AMCP6Portal3IPC17io_messenger_id_tENS_9allocatorIS4_EEE12emplace_backIJRKS4_EEERS4_DpOT_ENKUlvE0_clEv : 232 -> 228
~ __ZNK10applesauce3xpc4dict12object_proxycvNS0_6objectEEv : 192 -> 180
~ __ZNSt3__16vectorINS_4pairIN4AMCP6Portal3IPC20shared_buffer_info_tEN10applesauce3xpc4dictEEENS_9allocatorIS9_EEE24__emplace_back_slow_pathIJS9_EEEPS9_DpOT_ : 380 -> 376
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk4mach11unfair_lockENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceINS_3mapIyPvNS_4lessIyEENS_9allocatorINS_4pairIKyS2_EEEEEENS5_ISA_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceINS_13unordered_mapIN4AMCP6Portal3IPC17io_messenger_id_tENS_10shared_ptrINS4_11IO_ReceiverEEENS_4hashIS5_EENS_8equal_toIS5_EENS_9allocatorINS_4pairIKS5_S8_EEEEEENSD_ISI_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceINS_13unordered_mapIN4AMCP6Portal3IPC17io_messenger_id_tENS_10shared_ptrINS4_11IO_ReceiverEEENS_4hashIS5_EENS_8equal_toIS5_EENS_9allocatorINS_4pairIKS5_S8_EEEEEENSD_ISI_EEE16__on_zero_sharedEv : 124 -> 112
~ __ZNSt3__120__shared_ptr_emplaceINS_6vectorINS_4pairIN4AMCP6Portal3IPC20shared_buffer_info_tEN10applesauce3xpc4dictEEENS_9allocatorISA_EEEENSB_ISD_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceINS_6vectorINS_4pairIN4AMCP6Portal3IPC20shared_buffer_info_tEN10applesauce3xpc4dictEEENS_9allocatorISA_EEEENSB_ISD_EEE16__on_zero_sharedEv : 80 -> 68
~ __ZNSt3__120__shared_ptr_emplaceI18Property_Type_InfoNS_9allocatorIS1_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceI18Property_Type_InfoNS_9allocatorIS1_EEE16__on_zero_sharedEv : 136 -> 124
~ __ZNK5boost10error_infoIN10applesauce10exceptions13tag_backtraceENS1_9backtrace10snapshot_NILi64EEEE17name_value_stringEv : 2100 -> 2060
~ __ZN5boost10error_infoIN10applesauce10exceptions13tag_backtraceENS1_9backtrace10snapshot_NILi64EEEED0Ev : 112 -> 100
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 532 -> 492
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev : 288 -> 248
~ __ZNK5boost16exception_detail25error_info_container_impl22diagnostic_informationEPKc : 772 -> 732
~ __ZNSt3__120__shared_ptr_emplaceIN4AMCP6Portal3IPC11IO_ReceiverENS_9allocatorIS4_EEED0Ev : 84 -> 72
~ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeIN4AMCP6Portal3IPC17io_messenger_id_tENS_10shared_ptrINS6_11IO_ReceiverEEEEEPvEEEEEclB9nqe220106EPSD_ : 68 -> 56
~ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN4AMCP6Portal3IPC17io_messenger_id_tENS_10shared_ptrINS4_11IO_ReceiverEEEEENS_22__unordered_map_hasherIS5_NS_4pairIKS5_S8_EENS_4hashIS5_EENS_8equal_toIS5_EEEENS_21__unordered_map_equalIS5_SD_SH_SF_EENS_9allocatorISD_EEE14__erase_uniqueIS5_EEmRKT_ : 336 -> 324
~ __ZN10applesauce2CF7details5at_toINS0_13DictionaryRefEEET_PK9__CFArraymNS1_17applesauce_cf_tagE : 180 -> 168
~ __ZN10applesauce2CF7details5at_toINS0_9StringRefEEET_PK9__CFArraymNS1_17applesauce_cf_tagE : 180 -> 168
~ __ZN4AMCP3HAL18pack_property_dataENS0_22HAL_Property_Type_CodeEjPKv : 572 -> 560
~ __ZN4AMCP3HAL20unpack_property_dataEP6NSDataNS0_22HAL_Property_Type_CodeERjPv : 1660 -> 1640
~ -[Core_Audio_Driver_Host_Proxy .cxx_destruct] : 120 -> 108
~ __ZNSt3__120__shared_ptr_emplaceI14Host_InterfaceNS_9allocatorIS1_EEED0Ev : 84 -> 72
~ -[Core_Audio_Driver_Service set_driver_service_client_endpoint:reply:] : 156 -> 144
~ -[Core_Audio_Driver_Service set_process_name:] : 344 -> 332
~ -[Core_Audio_Driver_Service .cxx_destruct] : 160 -> 148
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE17__assign_externalEPKc : 72 -> 60
~ __ZNSt3__120__shared_ptr_emplaceIN10applesauce5iokit18io_service_factoryENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZNSt3__110__function6__funcIZ86-[Core_Audio_Driver_Service handle_deferred_driver:bundle_id:loading_conditions:info:]E3$_6FvN10applesauce5iokit16io_object_holderEEED0Ev : 152 -> 140
~ __ZNKSt3__110__function6__funcIZ86-[Core_Audio_Driver_Service handle_deferred_driver:bundle_id:loading_conditions:info:]E3$_6FvN10applesauce5iokit16io_object_holderEEE7__cloneEv : 76 -> 64
~ __ZNSt3__110__function6__funcIZ86-[Core_Audio_Driver_Service handle_deferred_driver:bundle_id:loading_conditions:info:]E3$_6FvN10applesauce5iokit16io_object_holderEEE7destroyEv : 100 -> 88
~ __ZN4AMCP6Portal3IPC11IO_ReceiverD0Ev : 56 -> 44
~ __ZN4AMCP6Portal3IPC11IO_Receiver15register_bufferEPU24objcproto13OS_xpc_object8NSObject : 2600 -> 2592
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk3ipc21synchronous_messenger18eventlink_receiverENS_9allocatorIS4_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk3ipc21synchronous_messenger18eventlink_receiverENS_9allocatorIS4_EEE16__on_zero_sharedEv : 124 -> 112
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk3ipc21synchronous_messenger18semaphore_receiverENS_9allocatorIS4_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk3ipc21synchronous_messenger18semaphore_receiverENS_9allocatorIS4_EEE16__on_zero_sharedEv : 132 -> 120
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk4mach20os_workgroup_managedENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZNSt3__120__shared_ptr_emplaceIN5caulk3ipc13mapped_memoryENS_9allocatorIS3_EEED0Ev : 84 -> 72
~ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeIN4AMCP6Portal3IPC20shared_buffer_info_tENS_10shared_ptrIN5caulk3ipc13mapped_memoryEEEEEPvEEEEEclB9nqe220106EPSF_ : 68 -> 56
~ __ZN5caulk10concurrent9messenger12enqueue_callIZZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvENK3$_0clERNS_3ipc13mapped_memoryEEUlRNSt3__15tupleIJPKciyjEEEE_JSF_EEEvOT_DpOT0_ : 172 -> 160
~ __ZN5caulk10concurrent7details15rt_message_callIZZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvENK3$_0clERNS_3ipc13mapped_memoryEEUlRNSt3__15tupleIJPKciEEEE_JSF_EED0Ev : 56 -> 44
~ __ZN5caulk10concurrent7details15rt_message_callIZZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvENK3$_0clERNS_3ipc13mapped_memoryEEUlRNSt3__15tupleIJPKciyjEEEE_JSF_EED0Ev : 56 -> 44
~ __ZN5caulk10concurrent7details15rt_message_callIZZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvENK3$_0clERNS_3ipc13mapped_memoryEEUlRNSt3__15tupleIJPKciyjEEEE_JSF_EE7performEv : 92 -> 80
~ __ZN5caulk10concurrent7details12message_callIZZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvENK3$_0clERNS_3ipc13mapped_memoryEEUlRNSt3__15tupleIJPKciyjEEEE_JSF_EED0Ev : 56 -> 44
~ __ZN5caulk12thread_proxyINSt3__15tupleIJNS_6thread10attributesEZN4AMCP6Portal3IPC11IO_Receiver20start_message_threadEvE3$_1NS2_IJEEEEEEEEPvSC_ : 3944 -> 3940
~ __ZN5caulk4mach14error_categoryD0Ev : 56 -> 44
~ __ZN5boost16exception_detail10clone_implINS0_19error_info_injectorISt12domain_errorEEED1Ev : 92 -> 80
~ __ZN5boost16exception_detail19error_info_injectorISt12domain_errorED1Ev : 92 -> 80
~ __ZN5boost16exception_detail10clone_implINS0_19error_info_injectorISt12domain_errorEEED0Ev : 112 -> 100
~ __ZThn16_N5boost16exception_detail10clone_implINS0_19error_info_injectorISt12domain_errorEEED1Ev : 84 -> 72
~ __ZTv0_n40_N5boost16exception_detail10clone_implINS0_19error_info_injectorISt12domain_errorEEED1Ev : 112 -> 100
~ __ZN5boost16exception_detail19error_info_injectorISt12domain_errorED0Ev : 112 -> 100
~ __ZThn16_N5boost16exception_detail19error_info_injectorISt12domain_errorED1Ev : 84 -> 72
~ __ZN5boost16exception_detail19error_info_injectorISt12domain_errorED2Ev : 92 -> 80
```

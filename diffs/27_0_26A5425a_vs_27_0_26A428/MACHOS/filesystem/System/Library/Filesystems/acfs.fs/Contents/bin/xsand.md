## xsand

> `/System/Library/Filesystems/acfs.fs/Contents/bin/xsand`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x7d334
+  __TEXT.__text: 0x7ceb4
   __TEXT.__auth_stubs: 0x1a20
   __TEXT.__objc_stubs: 0x1a20
   __TEXT.__objc_methlist: 0x6c8

   __TEXT.__objc_methtype: 0x1ee
   __TEXT.__gcc_except_tab: 0x1f0
   __TEXT.__objc_methname: 0x15ee
-  __TEXT.__unwind_info: 0x1270
+  __TEXT.__unwind_info: 0x1be8
   __DATA_CONST.__const: 0xa30
   __DATA_CONST.__cfstring: 0x4380
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ _xsand_setup_SCDynamicStore : 504 -> 492
~ _management_connection_close : 100 -> 88
~ _volume_disk_object_ref : 116 -> 104
~ ___40+[SANLongTaskHub noteLongTask:onVolume:]_block_invoke : 148 -> 136
~ ___copy_helper_block_e8_32o40o : 80 -> 68
~ ___destroy_helper_block_e8_32o40o : 68 -> 56
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ _command_mount : 872 -> 848
~ _command_unmount : 436 -> 412
~ _command_list : 812 -> 800
~ _command_sanConfigChanged : 156 -> 144
~ _command_ldapConfigChanged : 368 -> 356
~ _command_roleChanged : 152 -> 140
~ _command_disksChanged : 344 -> 332
~ _command_volStateChange : 2948 -> 2936
~ _command_joinSan : 584 -> 572
~ _command_wipeConfig : 160 -> 148
~ _command_readVolumeProgress : 352 -> 328
~ _command_getLongTasks : 84 -> 72
~ _build_mounted_volumes_dict : 264 -> 252
~ _do_roleChanged : 144 -> 132
~ _assessVolumeUp : 212 -> 200
~ ___command_getLongTasks_block_invoke : 80 -> 68
~ _system_power_notification_callback : 324 -> 312
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _SpotlightProxyInit : 172 -> 160
~ _command_renameVolume : 572 -> 560
~ _command_startVolume : 288 -> 264
~ _command_addVolume : 444 -> 432
~ _command_editVolume : 456 -> 444
~ _command_eraseVolume : 440 -> 428
~ _command_importVolume : 1980 -> 1968
~ _command_stopVolume : 348 -> 324
~ _command_dropVolume : 732 -> 720
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ ___buildListOfUsedLuns_block_invoke_3 : 88 -> 76
~ ___76+[XsandRequestHandler updateVolumeConfig:withRequest:existingLUNs:andError:]_block_invoke : 100 -> 88
~ ___76+[XsandRequestHandler updateVolumeConfig:withRequest:existingLUNs:andError:]_block_invoke_2 : 1152 -> 1148
~ ___copy_helper_block_e8_32o40o48o56o64r : 128 -> 116
~ ___destroy_helper_block_e8_32o40o48o56o64r : 104 -> 92
~ ___45+[XsandRequestHandler editVolumeWithRequest:]_block_invoke_2 : 144 -> 132
~ ___copy_helper_block_e8_32o40o48r : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48r : 80 -> 68
~ ___47+[XsandRequestHandler deleteVolumeWithRequest:]_block_invoke : 372 -> 360
~ ___copy_helper_block_e8_32o40o48o56r : 112 -> 100
~ ___destroy_helper_block_e8_32o40o48o56r : 92 -> 80
~ ___copy_helper_block_e8_32o40o48o56o : 112 -> 100
~ ___destroy_helper_block_e8_32o40o48o56o : 92 -> 80
~ ___49+[XsandRequestHandler getVolumeStateWithRequest:]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32o40o48o : 96 -> 84
~ ___destroy_helper_block_e8_32o40o48o : 80 -> 68
~ ___copy_helper_block_e8_32o40o48r56r : 112 -> 100
~ ___destroy_helper_block_e8_32o40o48r56r : 92 -> 80
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ _SNAdmin_FSMStopByHost : 1388 -> 1404
~ _SNAdmin_DebugAtExit : 72 -> 60
~ __HexDump : 468 -> 456
~ _scan_progress : 716 -> 704
~ _CvDumpLabel : 2596 -> 2584
~ _CvFreeLabelBuffer : 68 -> 56
~ _CvCopyLabel : 80 -> 68
~ _verify_lun_readable : 736 -> 732
~ _label_config_failed : 204 -> 192
~ _CvBuildLabelEFI : 344 -> 332
~ _CvBuildLabel : 428 -> 404
~ _CvLabelWarnings : 712 -> 700
~ _CvLabelChangeEssay : 436 -> 424
~ _PlistString : 224 -> 212
~ _CvDisplayLabel : 1816 -> 1804
~ _disk_scan_finalize : 1748 -> 1744
~ _CvPrintInfo : 664 -> 652
~ _human_capacity : 200 -> 188
~ _initLibMPIOFramework : 40 -> 28
~ _find_IORegistryBSDName : 832 -> 836
~ _find_IORegistryContent : 728 -> 704
~ _find_IORegistrySerialNumber : 2248 -> 2260
~ _print_ucs2 : 108 -> 96
~ _AppleFSEventsProxyInit : 160 -> 148
~ ___starter : 104 -> 92
~ ___SpotlightReqestDo_block_invoke : 408 -> 412
~ _XsanSpotlightRealClientFini : 104 -> 92
~ ___starter : 104 -> 92
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
~ _FsmPMFreeCoordList : 156 -> 144
~ _FsmPMFreeSvcList : 156 -> 144
~ _FsmPMFreeIdList : 84 -> 72
~ _round_to_nearest_Xbyte : 308 -> 304
~ _set_required_action : 408 -> 396
~ _set_update_in_progress : 96 -> 84
~ _add_extension_to_affinity : 340 -> 328
~ _cfg_invalid_ASR_alloc_strat_combo_transform : 76 -> 64
~ _free_disk : 428 -> 416
~ __set_sg_vacant : 160 -> 148
~ _set_sg_vacant : 72 -> 60
~ _add_vacant_disks : 424 -> 420
~ _sort_disks : 280 -> 268
~ _validate_cfg_sg_disks : 716 -> 712
~ _validate_cfg_rtios : 724 -> 720
~ _setup_directory_component : 80 -> 68
~ _config_directory_setup : 160 -> 148
~ _validate_stripegroups_transform : 704 -> 696
~ _free_config : 292 -> 280
~ _get_config_template_buffer : 280 -> 268
~ _write_config_file_to_fd : 156 -> 144
~ _autoconvert_config : 260 -> 248
~ _delete_inode_expand_values : 108 -> 96
~ _add_cfg_msg_str : 312 -> 300
~ _destroy_expandable_buffer : 72 -> 60
~ _process_global : 4132 -> 4096
~ _dump_globals : 9488 -> 9476
~ _xml_id : 180 -> 168
~ _handleFirstPass : 216 -> 204
~ _handleSecondPass : 304 -> 292
~ _free_slice_arr : 128 -> 116
~ _call_parser : 208 -> 196
~ _diskDel : 152 -> 140
~ _stripeDel : 264 -> 252
~ _disktypeDel : 152 -> 140
~ _nameAdd : 252 -> 240
~ _nameDel : 152 -> 140
~ _cfg_yyparse : 12092 -> 12936
~ _cfg_yy_delete_buffer : 112 -> 100
~ _cfg_yy_scan_string : 60 -> 48
~ _auth_sign_data : 212 -> 204
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ __SnfsCfgEntFree : 104 -> 92
~ _SnfsDirEnumEnd : 96 -> 84
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
~ _FormatSysError : 68 -> 56
~ _CloseLog : 220 -> 208
~ _GetLogFileInfo : 184 -> 172
~ _parse_option : 1440 -> 1444
~ _gvar_close : 136 -> 124
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
~ -[CachedObject objectValueForKey:] : 96 -> 84
~ -[SANComputer readMacOSVersion] : 280 -> 256
~ -[SANComputer readNameServers] : 164 -> 152
~ -[SANComputer isController] : 48 -> 36
~ -[SANComputer readUuid] : 268 -> 256
~ -[SANComputer readNeedsUpdate] : 160 -> 148
~ -[SANComputer isInNeedOfUpdate] : 40 -> 28
~ -[SANComputer readLegacyMetadataNIC] : 88 -> 76
~ -[SANComputer readLegacyMetadataIP] : 88 -> 76
~ -[SANComputer readLegacySanName] : 88 -> 76
~ _SANFilesystemDADiskAppearedCallback : 252 -> 240
~ _SANFilesystemDAIdleCallback : 40 -> 28
~ -[SANFilesystem(DAHelpers) acquireDiskDescriptionTable] : 72 -> 60
~ -[SANFilesystem areWePrimaryControllerWithDict:andHost:] : 116 -> 104
~ ___39-[SANFilesystem getListOfAllUsedDisks:]_block_invoke_3 : 88 -> 76
~ ___38-[SANFilesystem getListOfVolumeDisks:]_block_invoke_2 : 88 -> 76
~ ___37+[SANFilesystem getControllersForIP:]_block_invoke : 88 -> 76
~ ___54+[SANFilesystem getVolumesForConfig:andControllerIPs:]_block_invoke_2 : 88 -> 76
~ -[NSObject(DeepMutableCopyAdditions) deepMutableCopyWithZone:] : 488 -> 452
~ ___storagePoolsForVolume_block_invoke_2 : 92 -> 80
~ ___advancedOptionsForVolume_block_invoke : 168 -> 156
~ __advancedOptionsForVolume_block_invoke.439 : 112 -> 100
~ _launchAsyncTask : 444 -> 432
~ _state_of_volume : 1056 -> 1052
```

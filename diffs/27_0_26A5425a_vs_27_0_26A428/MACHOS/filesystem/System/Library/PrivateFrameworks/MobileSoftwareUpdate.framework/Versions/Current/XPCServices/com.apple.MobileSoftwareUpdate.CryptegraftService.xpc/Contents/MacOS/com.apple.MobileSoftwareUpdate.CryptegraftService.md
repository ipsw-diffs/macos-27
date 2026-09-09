## com.apple.MobileSoftwareUpdate.CryptegraftService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/Current/XPCServices/com.apple.MobileSoftwareUpdate.CryptegraftService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CryptegraftService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2718.0.18.0.0
-  __TEXT.__text: 0x2f82c
+  __TEXT.__text: 0x2f214
   __TEXT.__auth_stubs: 0x15b0
   __TEXT.__objc_stubs: 0x35e0
   __TEXT.__objc_methlist: 0x167c

   __TEXT.__objc_classname: 0x29a
   __TEXT.__objc_methtype: 0xa30
   __TEXT.__oslogstring: 0x158c
-  __TEXT.__unwind_info: 0x7d0
+  __TEXT.__unwind_info: 0xcd0
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x1098
   __DATA_CONST.__cfstring: 0x77a0
Functions:
~ +[MSUTargetController sharedController] : 120 -> 108
~ ___39+[MSUTargetController sharedController]_block_invoke : 76 -> 64
~ +[MSUTargetController pushController:] : 208 -> 196
~ +[MSUTargetController popController] : 236 -> 224
~ -[MSUTargetController rootSnapshotNameForTarget] : 76 -> 64
~ -[MSUTargetController targetDataVolume] : 80 -> 68
~ -[MSUTargetController sourcePrebootVolume] : 80 -> 68
~ -[MSUTargetController targetPrebootVolume] : 580 -> 568
~ -[MSUTargetController recoveryVolume] : 80 -> 68
~ -[MSUTargetController updateVolume] : 80 -> 68
~ -[MSUTargetController mountAndGetUpdateVolumeMountPoint] : 268 -> 256
~ -[MSUTargetController systemRecoveryContainer] : 436 -> 424
~ -[MSUTargetController systemRecoveryVolume] : 200 -> 188
~ -[MSUTargetController xARTVolume] : 352 -> 340
~ -[MSUTargetController targetMountPath] : 128 -> 116
~ -[MSUTargetController preparePath] : 128 -> 116
~ -[MSUTargetController patchdOptionsPath] : 88 -> 76
~ -[MSUTargetController patchdPrelightOptionsPath] : 88 -> 76
~ -[MSUTargetController patchdNVRAMShadowPath] : 88 -> 76
~ -[MSUTargetController patchdToleratedFailuresPath] : 88 -> 76
~ -[MSUTargetController lastOTALogDirectory] : 144 -> 132
~ -[MSUTargetController brainLocatorPlistPath] : 88 -> 76
~ -[MSUTargetController updateResultPlistPath] : 88 -> 76
~ -[MSUTargetController targetRestoreVersion] : 216 -> 204
~ -[MSUTargetController targetSystemVersion] : 216 -> 204
~ -[MSUTargetController bookmarkCachePath] : 172 -> 160
~ -[MSUTargetController _primaryMedia] : 340 -> 328
~ -[MSUTargetController _firmwareDiagsContainer] : 396 -> 384
~ -[MSUTargetController _mediaForUUID:timeout:] : 276 -> 264
~ -[MSUTargetController .cxx_destruct] : 104 -> 92
~ _msu_process_dictionary_values_for_xpc_serialization : 160 -> 148
~ _msu_process_cf_object_for_xpc_serialization : 396 -> 384
~ _msu_serialize_cf_object_into_xpc_dict : 240 -> 228
~ _msu_process_dictionary_values_from_xpc_deserialization : 160 -> 148
~ _msu_process_cf_object_from_xpc_deserialization : 400 -> 388
~ _handle_message : 508 -> 484
~ _msu_send_error : 240 -> 228
~ _msu_send_status_with_reply : 204 -> 192
~ ___copy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ -[CSActionInstallDownlevel cleanupAfterError:] : 84 -> 72
~ -[CSActionInstallDownlevel _buildIdentityForCurrentDeviceWithError:] : 900 -> 888
~ -[CSActionInstallDownlevel _variantFromBuildIdentity:] : 140 -> 128
~ -[CSActionInstallDownlevel _relativePathForTag:buildIdentity:] : 360 -> 348
~ ___destructor_8_s16_s24 : 60 -> 48
~ -[CSActionMountPreboot _groupUUIDForVolumeAtMountPoint:] : 300 -> 288
~ +[CSError errorWithCode:description:underlyingError:] : 296 -> 284
~ +[CSError errorWithCode:underlyingError:] : 116 -> 104
~ +[CSError errorWithCode:description:underlyingPOSIXErrorCode:] : 184 -> 172
~ +[CSError errorWithCode:underlyingPOSIXErrorCode:] : 68 -> 56
~ +[CSError errorWithCode:description:] : 116 -> 104
~ +[CSError errorWithCode:] : 64 -> 52
~ -[CSRequest splatOptions] : 332 -> 320
~ -[CSRequest .cxx_destruct] : 104 -> 92
~ +[CSEventReporter createEventDictionaryWithEventName:result:error:request:] : 380 -> 368
~ +[CSEventReporter eventResultStringFromError:] : 400 -> 388
~ -[CSTaskDownlevel actions] : 360 -> 348
~ -[CSTaskSemiSplat actions] : 436 -> 424
~ ___CryptegraftService_event_handler_block_invoke : 240 -> 228
~ _handle_CSPerformSemiSplat : 360 -> 348
~ _handle_CSPerformDownlevel : 472 -> 460
~ _supportDirectoryWithMountPoint : 600 -> 588
~ _supportDirectoryWithDataMountPoint : 168 -> 156
~ _installInfoFileWithDataMountPoint : 88 -> 76
~ +[MSUTargetController(VeryPrivate) _errorWithCode:underlyingError:] : 648 -> 636
~ ___copy_helper_block_e8_32o40b : 80 -> 68
~ ___destroy_helper_block_e8_32o40b : 68 -> 56
~ -[MSUCheckpointAsyncBlockContext runSynchronousForCheckpoint:] : 120 -> 108
~ -[MSUCheckpointAsyncBlockContext runForCheckpoint:] : 120 -> 108
~ -[MSUCheckpointAsyncBlockContext cancel] : 120 -> 108
~ _wait_for_io_service_matching_resource_with_timeout : 212 -> 200
~ _ramrod_ticket_copy_nsih : 128 -> 116
~ _ramrod_log_to_fd_set_applier : 328 -> 316
~ _checkpoint_outcome_progress : 144 -> 132
~ _checkpoint_nvram_delete_var : 260 -> 272
~ _checkpoint_access_obtain : 88 -> 76
~ _checkpoint_access_yield : 88 -> 76
~ _checkpoint_closure_context_set_encountered_async_error : 300 -> 288
~ _checkpoint_closure_context_handle_simulator_actions : 168 -> 156
~ _checkpoint_closure_context_handle_simulator_match_name : 140 -> 128
~ _checkpoint_outcome_init : 200 -> 188
~ _checkpoint_nvram_delete_var_if_matches : 104 -> 92
~ _checkpoint_reboot_retry_chassis_aware : 232 -> 220
~ _checkpoint_nvram_alloc_encode : 192 -> 180
~ _ramrod_create_error_internal_va : 288 -> 276
~ __options_get_bool : 104 -> 92
~ __get_os_preboot_path : 292 -> 280
~ __create_error_posix : 228 -> 216
~ ___copy_helper_block_e8_32o40b48r : 96 -> 84
~ ___destroy_helper_block_e8_32o40b48r : 80 -> 68
~ -[MSUBootObjectCopier _stitchedPathForTag:] : 252 -> 240
~ -[MSUBootObjectCopier _tagsToPreserve] : 148 -> 136
~ -[MSUBootObjectCopier _tagsInBuildIdentity:] : 112 -> 100
~ -[MSUCheckpointAsyncContext runForCheckpoint:] : 72 -> 60
~ -[MSUCheckpointAsyncContext runSynchronousForCheckpoint:] : 72 -> 60
~ -[MSUCheckpointAsyncContext cancel] : 72 -> 60
~ _bless2_summary_free : 68 -> 56
~ _get_media_group_uuid : 88 -> 76
~ _file_unload : 200 -> 188
~ _OUTLINED_FUNCTION_9 : 44 -> 32
~ _OUTLINED_FUNCTION_12 : 24 -> 12
~ _OUTLINED_FUNCTION_13 : 24 -> 12
~ _OUTLINED_FUNCTION_14 : 24 -> 12
~ +[MSUBootFirmwareUpdater updater] : 440 -> 416
~ +[MSUBootFirmwareUpdater updaterWithIOService:] : 348 -> 336
~ -[MSUBootFirmwareUpdater init] : 64 -> 52
~ -[MSUBootFirmwareUpdater copyFirmwareWithRestoreInfo:] : 68 -> 56
~ _OUTLINED_FUNCTION_1 : 80 -> 68
~ _OUTLINED_FUNCTION_2 : 64 -> 52
~ -[PCIeNANDBootWriter appendImages:] : 216 -> 204
~ _OUTLINED_FUNCTION_1 : 36 -> 24
~ _OUTLINED_FUNCTION_3 : 24 -> 12
~ -[IODualSPIWriter writeData:withError:] : 128 -> 104
~ -[IODualSPIWriter writeNewerGenerationFirmware:withError:] : 1212 -> 1208
~ -[IODualSPIWriter markHeaderAsInvalid:] : 96 -> 84
~ -[IODualSPIWriter commitPreparedHeaderWithError:] : 132 -> 120
~ -[IODualSPIWriter _writeFirmware:toHeader:withError:] : 1084 -> 1076
~ -[IODualSPIWriter _commitHeader:withError:] : 248 -> 236
~ -[MSUiBootHeader bumpGeneration] : 84 -> 72
~ -[MSUiBootHeaderV2 makeValid] : 92 -> 80
~ -[MSUiBootHeaderV2 computeHash] : 72 -> 60
~ -[MSUiBootHeaderV2 _hashDataWithNativeHashMethod:] : 80 -> 68
~ -[IOServiceWriter writeBytes:ofLength:withError:] : 76 -> 64
~ -[IOServiceWriter openService] : 72 -> 60
~ -[DevNodeWriter devicePath] : 84 -> 72
~ -[DevNodeWriter writeData:withError:] : 100 -> 88
~ -[PFXSoCRestoreInfoHelperOS logInternal:arguments:] : 160 -> 148
~ -[PFXRestoreInfoFirmwareCopierOS firmwareKeyFromBuildIdentityDict:deviceInfo:] : 232 -> 220
~ -[PFXSoCRestoreInfoFirmwareCopierOS readFirmwareFileDataWithError:] : 272 -> 260
~ -[PFXSoCRestoreInfoFirmwareCopierOS .cxx_destruct] : 144 -> 132
CStrings:
+ "18:32:49"
+ "Aug  8 2026"
- "02:53:04"
- "Aug 10 2026"
```

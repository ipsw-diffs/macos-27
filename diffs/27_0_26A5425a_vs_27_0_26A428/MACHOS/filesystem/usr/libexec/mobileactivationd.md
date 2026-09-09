## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1145.0.2.0.0
-  __TEXT.__text: 0x662c4
+  __TEXT.__text: 0x65574
   __TEXT.__auth_stubs: 0x1190
   __TEXT.__objc_stubs: 0x24c0
   __TEXT.__objc_methlist: 0x8ec

   __TEXT.__objc_methtype: 0x908
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0x267
-  __TEXT.__unwind_info: 0xde8
+  __TEXT.__unwind_info: 0x1390
   __DATA_CONST.__const: 0x6670
   __DATA_CONST.__cfstring: 0xa4e0
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ -[DataArk postNotification:] : 84 -> 72
~ -[DataArk .cxx_destruct] : 116 -> 104
~ ___data_ark_register_set_notification_block_invoke : 268 -> 256
~ ___copy_helper_block_e8_32s40s48s56s64r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64r : 88 -> 76
~ __create_mapkey : 216 -> 204
~ _data_ark_copy : 432 -> 420
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ ___data_ark_remove_block_invoke : 416 -> 404
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___data_ark_exists_block_invoke : 192 -> 180
~ ____copy_domain_block_invoke : 176 -> 164
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ _getRecertInfoFromData : 604 -> 592
~ _sysctlCopyDataDarwin : 240 -> 228
~ _sysctlSetGlobalInterface : 72 -> 60
~ _sysctlCopyData : 112 -> 100
~ _envCopyStringDarwin : 76 -> 64
~ _envSetGlobalInterface : 72 -> 60
~ _envCopyString : 112 -> 100
~ +[MALog getSharedInstance] : 68 -> 56
~ ___26+[MALog getSharedInstance]_block_invoke : 64 -> 52
~ -[MALog deleteExpiredLogFiles] : 76 -> 64
~ _copyLoggingHandle : 68 -> 56
~ _createAndLogError : 432 -> 420
~ _deleteExpiredPersistentLogFiles : 76 -> 64
~ ___copyLoggingHandle_block_invoke : 72 -> 60
~ _create_baa_info : 9960 -> 9948
~ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208_s216_s224_s232_s240_s248_s256_s264_s272 : 324 -> 312
~ +[DeviceType sharedInstance] : 68 -> 56
~ ___28+[DeviceType sharedInstance]_block_invoke : 64 -> 52
~ -[DeviceType .cxx_destruct] : 92 -> 80
~ _get_device_type : 96 -> 84
~ _get_device_class : 96 -> 84
~ _copy_bootsession_uuid : 88 -> 76
~ _copy_soc_generation : 96 -> 84
~ _copy_trusted_local_policy_hash : 340 -> 328
~ _copy_sfr_manifest : 412 -> 400
~ ___validACMContext_block_invoke : 148 -> 136
~ ___ucrt_oob_activity_handler_block_invoke : 140 -> 128
~ ___copy_helper_block_e8_32s40s48s56s64r72r80r88r : 144 -> 132
~ ___destroy_helper_block_e8_32s40s48s56s64r72r80r88r : 124 -> 112
~ ___copy_helper_block_e8_32s40r48r56r64r : 120 -> 108
~ ___destroy_helper_block_e8_32s40r48r56r64r : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112s120s128r136r144r152r : 208 -> 196
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104s112s120s128r136r144r152r : 188 -> 176
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r112r120r128r : 184 -> 172
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r112r120r128r : 164 -> 152
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s : 116 -> 104
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s : 116 -> 104
~ _copyUCRTDEPEnrollmentState : 728 -> 716
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _lockcrypto_query_certificate_properties : 5600 -> 5588
~ _lockcrypto_create_pem_from_key : 400 -> 388
~ _lockcrypto_create_pem : 664 -> 652
~ _lockcrypto_sign : 628 -> 616
~ _lockcrypto_digest_data : 292 -> 280
~ _lockcrypto_create_cert_request : 1104 -> 1092
~ _lockcrypto_decode_error : 708 -> 696
~ _lockcrypto_decode_pem : 664 -> 652
~ _lockcrypto_decode_pems : 840 -> 828
~ _lockcrypto_decode_pem_trailing_data : 652 -> 640
~ _lockcrypto_trailing_data_from_cert_pem_data : 304 -> 292
~ _lockcrypto_copy_certificate_validity_date : 344 -> 332
~ ___lockcrypto_query_oid_der_sequence_data_block_invoke : 84 -> 72
~ _getLAContextClass : 224 -> 212
~ _copy_keychain_data : 640 -> 628
~ _copy_keychain_data_attributes : 640 -> 628
~ _copyPersonalizedFirmwareData : 492 -> 480
~ _getMSUDataAccessorClass : 224 -> 212
~ _createMobileActivationError : 464 -> 452
~ -[MobileActivationMacOSDaemon callingProcessName] : 220 -> 208
~ -[MobileActivationMacOSDaemon valueForEntitlement:] : 180 -> 168
~ ___copy_helper_block_e8_32s40s48s56s64s72s80b88r96r104r : 160 -> 148
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r96r104r : 136 -> 124
~ ___copy_helper_block_e8_32s40s48s56s64b72r80r88r : 144 -> 132
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r88r : 120 -> 108
~ _getBYManagerClass : 260 -> 248
~ _getBYBootOptionUpdateAllCustomBootObjects : 224 -> 212
~ ___copy_helper_block_e8_32s40s48s56s64s72s80b88r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r : 112 -> 100
~ ___copy_helper_block_e8_32s40s48s56s64b72r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64s72r : 96 -> 84
~ ___copy_helper_block_e8_32s40b48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ __96-[MobileActivationMacOSDaemon _handleActivationInfo:activationData:options:withCompletionBlock:]_block_invoke.202 : 192 -> 180
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___copy_helper_block_e8_32s40s48s56s64s72s80b88r96r : 144 -> 132
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r96r : 124 -> 112
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96b104r112r : 160 -> 148
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r112r : 140 -> 128
~ ___copy_helper_block_e8_32s40s48b56r : 96 -> 84
~ ___61-[MobileActivationMacOSDaemon issueUCRT:withCompletionBlock:]_block_invoke_5 : 464 -> 452
~ __61-[MobileActivationMacOSDaemon issueUCRT:withCompletionBlock:]_block_invoke_2.456 : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64s72b80r : 120 -> 108
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80r : 104 -> 92
~ __61-[MobileActivationMacOSDaemon issueUCRT:withCompletionBlock:]_block_invoke_2.458 : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64b72r80r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r : 108 -> 96
~ -[MobileActivationMacOSDaemon .cxx_destruct] : 80 -> 68
~ ___isRunningInDiagnosticsMode_block_invoke : 108 -> 96
~ _isNSNumber : 116 -> 104
~ ___isSupportedDeviceIdentityClient_block_invoke : 80 -> 68
~ _copy_sorted_file_list : 284 -> 272
~ _isNSDictionary : 116 -> 104
~ _isNSArray : 116 -> 104
~ _isNSString : 116 -> 104
~ _isNSData : 116 -> 104
~ _isNSURL : 116 -> 104
~ _isNSDate : 116 -> 104
~ _dictionary_to_xml : 136 -> 124
~ _load_dict : 64 -> 52
~ _copy_process_name : 364 -> 352
~ _formatURLRequest : 612 -> 600
~ _formatURLResponse : 540 -> 528
~ _writeUserDefaults : 176 -> 164
~ _readUserDefaults : 172 -> 160
~ _libaks_ref_key_get_public : 312 -> 300
~ _libaks_system_key_get_public : 364 -> 352
~ _libaks_system_key_collection : 864 -> 852
~ _libaks_system_key_attest : 468 -> 456
~ _libavp_copy_strong_identity_data : 1632 -> 1620
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ _security_create_system_key_attestation : 576 -> 564
~ _security_create_attestation : 280 -> 268
~ _security_create_external_representation : 332 -> 320
~ _copySplunkDeviceIdentifiers : 3444 -> 3432
~ _copySplunkDailyStatistics : 3676 -> 3664
~ _copySortedSplunkFileList : 492 -> 480
~ _copySplunkQueue : 68 -> 56
~ ___splunk_activity_handler_block_invoke : 140 -> 128
~ ___copy_helper_block_e8_32s40s48s56s64r72r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48s56s64r72r : 100 -> 88
~ ___copy_helper_block_e8_32s40s48s56s64s72r : 104 -> 92
~ _copySplunkUUIDQueue : 68 -> 56
~ ___rollSplunkLogUUID_block_invoke : 148 -> 136
~ ___copySplunkLogUUID_block_invoke : 224 -> 212
~ ___copySplunkQueue_block_invoke : 108 -> 96
~ ___copySplunkUUIDQueue_block_invoke : 108 -> 96
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ _deactivationRequiredForSalavagedDevice : 76 -> 64
~ _copyRTCResetSerialQueue : 68 -> 56
~ ___copyRTCResetSerialQueue_block_invoke : 108 -> 96
~ _copyMobileActivationSerialQueue : 68 -> 56
~ ___copyMobileActivationSerialQueue_block_invoke : 108 -> 96
~ ___scheduleXPCActivity_block_invoke : 116 -> 104
~ ___scheduleXPCActivity_block_invoke_3 : 100 -> 88
~ _copyDCRT : 2120 -> 2108
~ _copy_device_id_info : 260 -> 248
~ _copy_device_info : 260 -> 248
~ _copyUCRTVersionInformation : 760 -> 748
~ _baa_rkproperties_create_data : 1492 -> 1480
~ _mobileGestaltSetGlobalInterface : 72 -> 60
~ _copyMobileGestaltAnswer : 112 -> 100
~ _copyMobileGestaltAnswerDarwin : 44 -> 32
~ +[NetworkProvider sharedInstance] : 136 -> 124
~ _copy_ucrt_path : 68 -> 56
~ ___copy_ucrt_path_block_invoke : 80 -> 68
~ _copy_dcrt_path : 68 -> 56
~ ___copy_dcrt_path_block_invoke : 80 -> 68
~ _copy_data_ark_directory_path : 68 -> 56
~ ___copy_data_ark_directory_path_block_invoke : 80 -> 68
~ _copy_log_directory_path : 68 -> 56
~ ___copy_log_directory_path_block_invoke : 80 -> 68
~ _copy_splunk_directory_path : 68 -> 56
~ ___copy_splunk_directory_path_block_invoke : 80 -> 68
~ _copyRootCertificate : 884 -> 872
~ _parseDERCertificatesFromChain : 488 -> 476
~ -[NSDateFormatter(MobileActivation) dateFromServerString:withError:] : 464 -> 452
~ _copyBridgeKey : 536 -> 524
~ _bridge_call_and_response : 176 -> 164
~ _copyRemoteServiceConnection : 816 -> 804
~ _copy_required_dcrt_oids : 172 -> 160
~ _copy_critical_dcrt_oids : 144 -> 132
~ _copy_supported_baa_oids : 356 -> 344
~ _FindMyCopyMaskedActivationLockUserName : 728 -> 716
~ ____FindMyRemoveActivationLockMacOS_block_invoke : 184 -> 172
~ ____FindMyCopyMaskedActivationLockUserNameMacOS_block_invoke : 240 -> 228
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ ____FindMyDeviceIsActivationLockedMacOS_block_invoke : 148 -> 136
~ _baa_request_body_create_dictionary : 312 -> 300
~ _udid_from_rkproperties_data : 196 -> 184
~ _baa_request_create_with_body : 700 -> 688
~ _talkToServerWithError : 2884 -> 2872
~ ___talkToServerWithError_block_invoke : 680 -> 668
~ ___copy_helper_block_e8_32s40s48s56s64s72r80r88r96r104r112r : 184 -> 172
~ ___destroy_helper_block_e8_32s40s48s56s64s72r80r88r96r104r112r : 156 -> 144
~ _getAKAccountManagerClass : 260 -> 248
~ _copyTokenForActivationLock : 2752 -> 2740
~ _getAKAppleIDAuthenticationControllerClass : 260 -> 248
~ _getAKAppleIDAuthenticationContextClass : 260 -> 248
~ ___copyTokenForActivationLock_block_invoke : 164 -> 152
~ ___copy_helper_block_e8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_e8_32r40r48r : 80 -> 68
~ _getAKAuthenticationPasswordKey : 260 -> 248
~ _getAKAuthenticationUsernameKey : 260 -> 248
~ +[GestaltHlpr getSharedInstance] : 68 -> 56
~ ___32+[GestaltHlpr getSharedInstance]_block_invoke : 64 -> 52
~ -[GestaltHlpr addAGestaltKey:toDictionary:required:errors:] : 284 -> 272
~ -[GestaltHlpr updateRecertInfo:errors:] : 428 -> 416
~ -[NSData(MobileActivation) hexString] : 268 -> 256
~ +[NSString(MobileActivation) stringWithUTF8StringData:] : 172 -> 160
~ _copyEndpointsFromTrial : 1224 -> 1212
~ _copyActiveEnrollments : 216 -> 204
~ ___initializeTrialClient_block_invoke : 88 -> 76
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ _createBAAClientName : 148 -> 136
~ _createUserAgentValue : 120 -> 108
~ _copySignpostLoggingHandle : 68 -> 56
~ ___copySignpostLoggingHandle_block_invoke : 72 -> 60
~ _DERDecodeItemPartialBufferGetLength : 488 -> 480
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _OUTLINED_FUNCTION_8 : 32 -> 20
~ _OUTLINED_FUNCTION_9 : 32 -> 20
~ _OUTLINED_FUNCTION_10 : 28 -> 16
~ _OUTLINED_FUNCTION_14 : 28 -> 16
~ _OUTLINED_FUNCTION_15 : 32 -> 20
~ _OUTLINED_FUNCTION_16 : 28 -> 16
~ _OUTLINED_FUNCTION_17 : 28 -> 16
~ _OUTLINED_FUNCTION_20 : 28 -> 16
~ _OUTLINED_FUNCTION_22 : 28 -> 16
~ _OUTLINED_FUNCTION_24 : 28 -> 16
~ _OUTLINED_FUNCTION_32 : 24 -> 12
~ _OUTLINED_FUNCTION_36 : 28 -> 16
~ _OUTLINED_FUNCTION_37 : 28 -> 16
~ _OUTLINED_FUNCTION_38 : 24 -> 12
~ _OUTLINED_FUNCTION_42 : 28 -> 16
~ _OUTLINED_FUNCTION_45 : 24 -> 12
~ _OUTLINED_FUNCTION_71 : 24 -> 12
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _OUTLINED_FUNCTION_6 : 32 -> 20
~ _OUTLINED_FUNCTION_8 : 32 -> 20
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_13 : 40 -> 28
~ _OUTLINED_FUNCTION_18 : 32 -> 20
~ _OUTLINED_FUNCTION_21 : 36 -> 24
~ _OUTLINED_FUNCTION_22 : 28 -> 16
~ _OUTLINED_FUNCTION_39 : 24 -> 12
~ _OUTLINED_FUNCTION_47 : 32 -> 20
~ _OUTLINED_FUNCTION_48 : 24 -> 12
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_0 : 36 -> 24
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_3 : 44 -> 32
~ _OUTLINED_FUNCTION_6 : 36 -> 24
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ _OUTLINED_FUNCTION_14 : 40 -> 28
~ _OUTLINED_FUNCTION_19 : 28 -> 16
~ _OUTLINED_FUNCTION_20 : 12 -> 20
~ _OUTLINED_FUNCTION_21 : 20 -> 12
~ _OUTLINED_FUNCTION_2 : 40 -> 28
~ _OUTLINED_FUNCTION_3 : 24 -> 16
~ _OUTLINED_FUNCTION_4 : 16 -> 24
~ _OUTLINED_FUNCTION_5 : 40 -> 28
~ _OUTLINED_FUNCTION_7 : 28 -> 16
~ _OUTLINED_FUNCTION_9 : 32 -> 20
~ _OUTLINED_FUNCTION_14 : 36 -> 24
~ _OUTLINED_FUNCTION_20 : 24 -> 12
~ _OUTLINED_FUNCTION_21 : 24 -> 12
~ _OUTLINED_FUNCTION_22 : 24 -> 12
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ _Util_hexDumpToStrHelper : 124 -> 120
~ _Util_SafeDeallocParameters : 256 -> 244
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _OUTLINED_FUNCTION_17 : 32 -> 20
~ _OUTLINED_FUNCTION_2 : 40 -> 28
~ _OUTLINED_FUNCTION_70 : 32 -> 20
~ _validateSignatureRSA : 632 -> 636
~ _X509ExtensionParseAppleExtension : 3172 -> 3076
~ _X509CertificateIsValid : 64 -> 52
~ __qsort_compare : 296 -> 292
~ _DeallocCredentialList : 156 -> 144
CStrings:
+ "Absinthe/2.0 macOS Device Activator (MobileActivation-1145.0.2 built on Aug  8 2026 at 15:54:48)"
- "Absinthe/2.0 macOS Device Activator (MobileActivation-1145.0.2 built on Aug 10 2026 at 01:08:15)"
```

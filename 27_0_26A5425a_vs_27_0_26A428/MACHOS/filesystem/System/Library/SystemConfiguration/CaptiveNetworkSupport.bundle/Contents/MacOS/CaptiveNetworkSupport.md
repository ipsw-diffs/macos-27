## CaptiveNetworkSupport

> `/System/Library/SystemConfiguration/CaptiveNetworkSupport.bundle/Contents/MacOS/CaptiveNetworkSupport`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 542.0.0.0.1
-  __TEXT.__text: 0x25a18
+  __TEXT.__text: 0x254d4
   __TEXT.__auth_stubs: 0x11a0
   __TEXT.__objc_stubs: 0x120
   __TEXT.__const: 0x1d0
   __TEXT.__oslogstring: 0x47fc
   __TEXT.__cstring: 0x18fd
   __TEXT.__objc_methname: 0x9a
-  __TEXT.__unwind_info: 0x718
+  __TEXT.__unwind_info: 0x970
   __DATA_CONST.__const: 0xe88
   __DATA_CONST.__cfstring: 0x1a20
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _BBMonitorCancelEvents : 80 -> 68
~ _BBMonitor_Probing : 272 -> 236
~ _BBMonitor_Broken : 1012 -> 1000
~ _BBMonitorSetTimer : 112 -> 100
~ _add_post_variable : 308 -> 296
~ _cleanup_context : 80 -> 68
~ ___schedule_probe_response_handler_block_invoke : 96 -> 84
~ ___schedule_query_api_response_handler_block_invoke : 96 -> 84
~ ___schedule_login_response_handler_block_invoke : 92 -> 80
~ ___schedule_logout_response_handler_block_invoke : 80 -> 68
~ ___send_message_block_invoke : 756 -> 708
~ ___schedule_token_auth_response_handler_block_invoke : 96 -> 84
~ _CaptiveUpdateAPIState : 116 -> 104
~ _CaptiveHandleCredentials : 492 -> 480
~ _stop : 116 -> 104
~ _CaptiveCopyAuthenticationResult : 392 -> 380
~ _CaptiveCarPlayAndInternetMode : 144 -> 132
~ _CNSStartServer : 124 -> 112
~ _CaptiveSymptomEnablePassiveDetection : 308 -> 296
~ _CaptiveSymptomReportCaptiveState : 176 -> 164
~ _CaptiveSymptomReportInconclusiveCaptiveEvaluation : 116 -> 104
~ _CaptiveSymptomReportBackhaulState : 172 -> 160
~ _MachServerCallback : 248 -> 236
~ _WebSheetStateIssueCommand : 124 -> 112
~ _ProberContextGet : 68 -> 56
~ _WebSheetRemove : 380 -> 368
~ _CaptiveCopyValueAfterEqual : 272 -> 260
~ _my_CFDictionaryGetBooleanValue : 116 -> 104
~ _my_CFArrayFindValue : 84 -> 72
~ _handleNotification : 188 -> 176
~ _PassiveDetectNewNetwork : 72 -> 60
~ _PassiveDetectSetRedirectURLHostname : 84 -> 72
~ _CNSPreferencesGet : 56 -> 44
~ _CNSPreferencesSet : 68 -> 56
~ _NotificationDispose : 136 -> 124
~ _CNPluginMonitorHandlerPluginListChanged : 96 -> 84
~ _CNPluginMonitorSetCommandList : 112 -> 88
~ _CNAccountsLookupPasswordType : 92 -> 80
~ _CNAccountsCredentialsValidate : 320 -> 308
~ _CNAccountCopyCurrentAccountRecord : 284 -> 272
~ _CNAccountsKeychainQueryAbort : 128 -> 116
~ _CNAccountsATTQueryAbort : 144 -> 132
~ _SFRQueryAbort : 132 -> 120
~ _CaptivePrefsInit : 168 -> 156
~ _CaptivePrefsGetBoolean : 164 -> 152
~ _CaptivePrefsSetBoolean : 144 -> 132
~ _CaptivePrefsUnset : 104 -> 92
~ _CaptivePrefsGetNumber : 172 -> 160
~ _CNInfoAuthenticating : 1272 -> 1248
~ _CNInfoMaintaining : 1372 -> 1348
~ _CNInfoPresentingUI : 736 -> 724
~ _my_CFDictionaryContainsKeyAndValue : 88 -> 76
~ _CNInfoFlushAuthCommand : 80 -> 68
~ _CNInfoGetCacheEntry : 100 -> 88
~ _CNInfoFailure : 284 -> 260
~ _SendCleanupCommandToBuiltinPluginIfNecessary : 152 -> 140
~ _CNInfoInactive : 524 -> 512
~ _filterDictCompare : 176 -> 164
~ _CNScanListFilterAppendCommandApplier : 404 -> 392
~ __BrokenBackhaulMonitorComplete : 296 -> 284
~ _CNInfoAddExcludedDisplayID : 148 -> 136
~ _CNPluginRemove : 56 -> 44
~ _CNPluginProcessResponse : 80 -> 68
~ _CNPluginProcessAck : 80 -> 68
~ _CNInfoFlushFilterCommand : 80 -> 68
~ _power_changed : 224 -> 200
~ _CNPluginStateListInitialize : 148 -> 136
~ _CNPluginStateBuiltinProvideResponse : 180 -> 168
~ _CNPluginStateBuiltinAckEvaluateCommand : 180 -> 168
~ _CNPluginStateCopyCommandList : 212 -> 200
~ _CNPluginStateIssueCommand : 296 -> 284
~ _CNPluginStateIssueForegroundCommand : 140 -> 116
~ _CNPluginStateSetFilterResults : 188 -> 164
~ _CNPluginStateRemoveCommandApplier : 196 -> 172
~ _CNPluginStateRemoveApplier : 144 -> 132
~ _prefs_set_entry : 200 -> 188
~ ___CommandHandlerDeallocate : 120 -> 108
~ _ThirdPartyAppRegisterSSIDs : 124 -> 112
~ _BuildSSIDLookup : 184 -> 172
~ _AppIDAddSSIDList : 92 -> 80
~ _SSIDAddAppID : 148 -> 136
~ _checkForNewInterfaces : 248 -> 236
~ _NetIFCopyCurrentWiFiNetwork : 196 -> 184
~ _NetIFWiFiNetworkWasAutoJoined : 116 -> 104
~ _NetIFIsQuickProbeRequired : 72 -> 60
~ _NetIFReportQuickProbeResult : 80 -> 68
~ _NetIFWiFiNetworkIsCaptive : 152 -> 140
~ _NetIFGetWiFiNetworkWasCaptive : 196 -> 184
~ _NetIFWiFiNetworkSetCaptivePortalAPIURL : 128 -> 116
~ _NetIFWiFiNetworkSetCaptivePortalUserPortalURL : 128 -> 116
~ _NetIFWiFiNetworkSetCaptivePortalVenueInfoURL : 128 -> 116
~ _NetIFWiFiNetworkSetCaptivePortalCanExtendSession : 128 -> 116
~ _NetIFWiFiNetworkSetCaptivePortalSessionExpiration : 128 -> 116
~ _NetIFWiFiNetworkSetCaptivePortalClientAuthURL : 128 -> 116
~ _NetIFWiFiNetworkGetBoolean : 104 -> 92
~ _NetIFUpdateWiFiNetwork : 72 -> 60
~ _append_signature : 156 -> 144
~ _NetCacheEntryDestroy : 160 -> 148
~ __XParsePost : 596 -> 592
~ __XAddAccount : 588 -> 584
~ __XAuthenticateUsing : 424 -> 420
~ __XAuthenticateUsingToken : 396 -> 392
```

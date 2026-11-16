## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/Support/assistantd`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-3610.11.2.4.1
-  __TEXT.__text: 0x561618
-  __TEXT.__auth_stubs: 0x3480
-  __TEXT.__objc_stubs: 0x46520
-  __TEXT.__objc_methlist: 0x23194
-  __TEXT.__cstring: 0x4fc4e
+3610.19.2.4.1
+  __TEXT.__text: 0x5665e4
+  __TEXT.__auth_stubs: 0x34e0
+  __TEXT.__objc_stubs: 0x46c60
+  __TEXT.__objc_methlist: 0x23444
+  __TEXT.__cstring: 0x503ec
   __TEXT.__const: 0xa2f78
   __TEXT.__dlopen_cstrs: 0x4e2
-  __TEXT.__gcc_except_tab: 0x487c
-  __TEXT.__oslogstring: 0x48a2c
-  __TEXT.__objc_classname: 0x4e9c
-  __TEXT.__objc_methname: 0x61809
-  __TEXT.__objc_methtype: 0xf263
-  __TEXT.__ustring: 0x98
-  __TEXT.__unwind_info: 0xcf10
+  __TEXT.__gcc_except_tab: 0x494c
+  __TEXT.__oslogstring: 0x4970b
+  __TEXT.__objc_classname: 0x4ec1
+  __TEXT.__objc_methname: 0x624ed
+  __TEXT.__objc_methtype: 0xf300
+  __TEXT.__ustring: 0xb6
+  __TEXT.__unwind_info: 0xcff0
   __TEXT.__eh_frame: 0x140
-  __DATA_CONST.__const: 0x24600
-  __DATA_CONST.__cfstring: 0x124e0
-  __DATA_CONST.__objc_classlist: 0xce8
+  __DATA_CONST.__const: 0x246d0
+  __DATA_CONST.__cfstring: 0x126e0
+  __DATA_CONST.__objc_classlist: 0xcf0
   __DATA_CONST.__objc_catlist: 0x638
   __DATA_CONST.__objc_protolist: 0x6a8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xb0
-  __DATA_CONST.__objc_superrefs: 0xab8
+  __DATA_CONST.__objc_superrefs: 0xac0
   __DATA_CONST.__objc_arraydata: 0x4c0
   __DATA_CONST.__objc_arrayobj: 0x1b0
-  __DATA_CONST.__objc_intobj: 0x780
+  __DATA_CONST.__objc_intobj: 0x798
   __DATA_CONST.__objc_dictobj: 0x2f8
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x30
-  __DATA_CONST.__auth_got: 0x1a50
-  __DATA_CONST.__got: 0x3b10
+  __DATA_CONST.__auth_got: 0x1a80
+  __DATA_CONST.__got: 0x3b20
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA.__objc_const: 0x339e8
-  __DATA.__objc_selrefs: 0x14f08
-  __DATA.__objc_ivar: 0x26c8
-  __DATA.__objc_data: 0x8110
+  __DATA.__objc_const: 0x33db0
+  __DATA.__objc_selrefs: 0x150f0
+  __DATA.__objc_ivar: 0x271c
+  __DATA.__objc_data: 0x8160
   __DATA.__data: 0x5b50
-  __DATA.__bss: 0xab8
+  __DATA.__bss: 0xac8
   __DATA.__common: 0x1428
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14693
-  Symbols:   2838
-  CStrings:  27370
+  Functions: 14764
+  Symbols:   2846
+  CStrings:  27546
 
Symbols:
+ _AFIsLinwoodCandidateHomePodWithoutLinwood
+ _AFPreferencesSetRecognizedSpeakerTwentyFourHourTimeDisplay
+ _AFRecognizedSpeakerHasNoTwentyFourHourTimeChoice
+ _AFUsesRecognizedSpeakerTwentyFourHourTime
+ _OBJC_CLASS_$_AFDisambiguationOutcomeDescriptor
+ _SecCodeCheckValidity
+ _SecCodeCopyGuestWithAttributes
+ _SecRequirementCreateWithString
+ _kSecGuestAttributeAudit
- _OBJC_CLASS_$_FTSnippetServiceManager
CStrings:
+ "%s #SiriAvailability Application installation changed, updating the Campo installation cache"
+ "%s #SiriAvailability Campo installation cache updated: installed=%{bool}d"
+ "%s #SiriAvailability candidate HomePod cannot run Linwood: skipping GMS and AuthKit checks, siriLinwoodCapabilities=%{public}@"
+ "%s #SiriAvailability recomputing: Campo installation changed to installed=%{bool}d"
+ "%s #rdar191712659 [%{public}s] Siri classic does not support this HomePod locale and Linwood is not supported: dismissing Siri with reason AFDismissalAssetsNotReady"
+ "%s %@ Could not get the code of the connecting process: %d"
+ "%s %@ Siri Capabilities Service Connection admitted as UserAccountUpdater by its code signature."
+ "%s Activating a peer's selection on request %@"
+ "%s Called off ADCommandCenterQueue, ending there. context = %@"
+ "%s Cancelling the stall retry of zone %@ for a new fetch"
+ "%s Cloud sync is off; skipping mirror sync for (%@)"
+ "%s Companion Siri availability record saved %{public}@, before the companion's last upload at %{public}@: left by an earlier companion, read as absent"
+ "%s Could not archive the selection: %@"
+ "%s Could not create the UserAccountUpdater code requirement: %d"
+ "%s Deferred releasing audio session until recording stops (speechState = %@)."
+ "%s Deferred service reset still waiting for %lu newer remote execution context(s)"
+ "%s Deferring service reset until %lu remote execution context(s) end"
+ "%s Fetch for zone %@ abandoned; retrying in %.0f seconds"
+ "%s FlowToolsSnippetService is not installed, not starting the snippet service manager"
+ "%s Ignoring a selection for request %@ from %{private}@, which it was not relayed to"
+ "%s Ignoring a selection for request %@, which this device is not relaying"
+ "%s Ignoring a selection for request %@, which was cancelled"
+ "%s Last remote execution context ended, running the deferred service reset if idle"
+ "%s Malformed selection from a peer"
+ "%s Not noting relayed views for request %@: no IDS id for the target"
+ "%s Not noting relayed views: peer id %d, request id %d"
+ "%s Not retrying zone %@ after %lu retries"
+ "%s Not retrying zone %@: another account's fetch kept it busy"
+ "%s Not retrying zone %@: its account is no longer tracked"
+ "%s Not sending %@ with refId=%@: this command is not associated with the current SASMUXStartAsrOnServerRequest"
+ "%s Peer did not take the selection: %@"
+ "%s Peer's selection for request %@ activated: %d, error: %@"
+ "%s Recognized speaker twentyFourHourTimeDisplay changed to %@"
+ "%s Refusing a remote peer's request with text (%d) or an unshowable name (name length %lu)"
+ "%s Relayed views expired; starting the selection here"
+ "%s Relaying views for request %@ to %{private}@"
+ "%s Remote execution context still active %.0fs after a service reset was deferred behind it; ending it. executionID=%{public}@"
+ "%s Remote peer is not owned by the current user; asking the user before starting its request (it asked itself: %d)"
+ "%s Request %@ cancelled (%ld); holding the selection for %@ until another request takes over"
+ "%s Request %@ ended; no longer taking a selection for %@"
+ "%s Request %@ took over from cancelled request %@"
+ "%s Scheduling mirrored zone setup for (%@)"
+ "%s Sending ASR request to server with requestId = %@, inputOrigin = %{public}@"
+ "%s Sending the selection back to the peer for request %@"
+ "%s Showing views relayed by %@ for request %@"
+ "%s remote request %@: sender owned by the current user %d, named by Rapport %d"
+ "+[ADAccount _accountForIdentifier:infoDictionary:instanceContext:isReadOnly:isCoupledToHost:keychainIsReadable:]"
+ "-[ADCampoInstallationCache scheduleUpdate]_block_invoke"
+ "-[ADCloudKitManager _scheduleMirroredZoneSetupIfNeededForZoneInfo:]"
+ "-[ADCloudKitManager _scheduleStalledFetchCheckForZoneInfo:account:generation:delay:retryFetch:completion:]_block_invoke"
+ "-[ADCloudKitManager _scheduleStalledFetchRetryForZoneInfo:account:afterGeneration:delay:waitsLeft:retryFetch:]_block_invoke"
+ "-[ADCommandCenter _commandShouldNotBeSentForHomePodServerAsrRequest:]"
+ "-[ADCommandCenter _handleExternalActivationRequest:fromRemotePeer:ownedByCurrentUser:solicitedReply:completion:]"
+ "-[ADCommandCenter _performDeferredServicesResetBackstopForGeneration:executionIDs:]"
+ "-[ADCommandCenter _publishSelectedSpeakerTwentyFourHourTimeDisplay]"
+ "-[ADCommandCenter _resetServicesIfIdle]"
+ "-[ADCommandCenter sendMuxAsrRequestToServer:inputOrigin:]_block_invoke"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_currentRequestDidChangeFrom:to:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_forwardRequestIfNeeded:delegate:completion:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_noteOutgoingRemoteRequest:executionContext:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_noteRemoteCommand:fromPeer:remoteExecutionInfo:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_requestWasCancelledWithRequestID:reason:successorInfo:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_startSelection:forRequestID:fromPeerWithIDSIdentifier:]"
+ "-[ADCommandCenter(RelayedPick) _relayedPick_startSelection:forRequestID:fromPeerWithIDSIdentifier:]_block_invoke"
+ "-[ADCommandCenter(RelayedPick) handleMessage:messageType:fromDeviceWithIdentifier:completion:]"
+ "-[ADDaemon _setupFlowToolsSnippetService]"
+ "-[ADSiriCapabilitiesStore handleCampoInstallationCacheDidUpdate:]_block_invoke"
+ "-[ADSpeechManager _handleCoordinatorReleaseRequestFromCoordinator:]"
+ "-[ADSpeechManager _releaseSessionIfDeferredUntilRecordingStopped]"
+ "@\"ADCampoInstallationCache\""
+ "ADCampoInstallationCache"
+ "ADCampoInstallationCacheDidUpdateNotification"
+ "ADCampoInstallationCacheIsInstalledKey"
+ "ADMultiUserTwentyFourHourTimeDisplayDidChangeNotification"
+ "AddViews"
+ "FTSnippetServiceManager"
+ "Hk"
+ "MobileAssistantDaemons-3610.19.2.4.1"
+ "RelayedPick"
+ "Remote request is not allowed."
+ "T@\"NSDictionary\",C,V_twentyFourHourTimeDisplayBySharedUserID"
+ "T@\"NSMutableDictionary\",&,N,V_fetchGenerationByAccount"
+ "T@\"NSMutableDictionary\",&,N,V_stalledFetchRetryCountByAccount"
+ "T@\"NSString\",C,N,V_stalledFetchRetryAccount"
+ "T@?,C,N,V_stalledFetchRetryFetch"
+ "TB,GisInstalled,V_installed"
+ "TB,V_siriClassicUnsupportedInLocale"
+ "TQ,N,V_stalledFetchRetryGeneration"
+ "This device does not take its Siri AI access from a companion"
+ "_ADConnectionIsUserAccountUpdater"
+ "_ADRelayedPickSendMessage_block_invoke"
+ "_accountForIdentifier:infoDictionary:instanceContext:isReadOnly:isCoupledToHost:"
+ "_accountForIdentifier:infoDictionary:instanceContext:isReadOnly:isCoupledToHost:keychainIsReadable:"
+ "_accountOfFetchContainer:"
+ "_campoInstallationCache"
+ "_commandShouldNotBeSentForHomePodServerAsrRequest:"
+ "_deferredServicesResetGeneration"
+ "_fetchGenerationByAccount"
+ "_handleCoordinatorReleaseRequestFromCoordinator:"
+ "_handleExternalActivationRequest:fromRemotePeer:ownedByCurrentUser:solicitedReply:completion:"
+ "_hasActiveRemoteExecutionContext"
+ "_heldEndpointFeaturesDelivery"
+ "_installed"
+ "_isContainerTracked:"
+ "_isHomePodLocaleWithoutSiriClassicForRequest"
+ "_needsServicesResetAfterRemoteExecution"
+ "_performDeferredServicesResetBackstopForGeneration:executionIDs:"
+ "_publishSelectedSpeakerTwentyFourHourTimeDisplay"
+ "_publishTwentyFourHourTimeDisplayBySharedUserID"
+ "_publishedSpeakerTwentyFourHourTimeDisplay"
+ "_relayedPickNotedTime"
+ "_relayedPickOutgoingCancelled"
+ "_relayedPickOutgoingPeerIDSIdentifier"
+ "_relayedPickOutgoingRequestID"
+ "_relayedPickOutgoingTime"
+ "_relayedPickPeerIDSIdentifier"
+ "_relayedPickPeerRequestID"
+ "_relayedPick_clear"
+ "_relayedPick_clearOutgoing"
+ "_relayedPick_currentRequestDidChangeFrom:to:"
+ "_relayedPick_forwardRequestIfNeeded:delegate:completion:"
+ "_relayedPick_noteOutgoingRemoteRequest:executionContext:"
+ "_relayedPick_noteRemoteCommand:fromPeer:remoteExecutionInfo:"
+ "_relayedPick_requestWasCancelledWithRequestID:reason:successorInfo:"
+ "_relayedPick_startListening"
+ "_relayedPick_startSelection:forRequestID:fromPeerWithIDSIdentifier:"
+ "_releaseSessionIfDeferredUntilRecordingStopped"
+ "_resetServicesIfIdle"
+ "_scheduleDeferredServicesResetBackstop"
+ "_scheduleMirroredZoneSetupIfNeededForZoneInfo:"
+ "_scheduleStalledFetchCheckForZoneInfo:account:generation:delay:retryFetch:completion:"
+ "_scheduleStalledFetchRetryForZoneInfo:account:afterGeneration:delay:waitsLeft:retryFetch:"
+ "_serverHeardNothingWithEndpointFeatures:"
+ "_siriClassicUnsupportedInLocale"
+ "_speakerTwentyFourHourTimeDisplayForSharedUserID:bySharedUserID:"
+ "_stalledFetchRetryAccount"
+ "_stalledFetchRetryCountByAccount"
+ "_stalledFetchRetryFetch"
+ "_stalledFetchRetryGeneration"
+ "_stalledFetchRetryLimit"
+ "_twentyFourHourTimeDisplayBySharedUserID"
+ "_twentyFourHourTimeDisplayBySharedUserIDForUsers:"
+ "_twentyFourHourTimeDisplayDidChange:"
+ "_twentyFourHourTimeDisplayForRegion:"
+ "_twentyFourHourTimeDisplayForSettings:"
+ "addCharactersInRange:"
+ "addCharactersInString:"
+ "characterSetWithCharactersInString:"
+ "com.apple.assistantd/voiceid.mirror.cache"
+ "controlCharacterSet"
+ "dateFormatFromTemplate:options:locale:"
+ "descriptor"
+ "fetchAvailabilityEnsuringCompanionAvailability:completion:"
+ "fetchCompanionSiriAvailabilityForSetup:completion:"
+ "fetchGenerationByAccount"
+ "formUnionWithCharacterSet:"
+ "handleCampoInstallationCacheDidUpdate:"
+ "identifier \"com.apple.UserAccountUpdater\" and anchor apple"
+ "installed"
+ "invertedSet"
+ "isHomePodLocaleWithoutSiriClassic:"
+ "isLinwoodCandidateHomePodWithoutLinwood"
+ "j"
+ "newlineCharacterSet"
+ "rangeOfCharacterFromSet:"
+ "relayedpick"
+ "removeCharactersInString:"
+ "scheduleUpdate"
+ "sendMuxAsrRequestToServer:inputOrigin:"
+ "setFetchGenerationByAccount:"
+ "setInstalled:"
+ "setSiriClassicUnsupportedInLocale:"
+ "setStalledFetchRetryAccount:"
+ "setStalledFetchRetryCountByAccount:"
+ "setStalledFetchRetryFetch:"
+ "setStalledFetchRetryGeneration:"
+ "setTwentyFourHourTimeDisplayBySharedUserID:"
+ "siriClassicUnsupportedInLocale"
+ "stalledFetchRetryAccount"
+ "stalledFetchRetryCountByAccount"
+ "stalledFetchRetryFetch"
+ "stalledFetchRetryGeneration"
+ "twentyFourHourTimeDisplayBySharedUserID"
+ "v16@?0@\"AFSiriAvailability\"8"
+ "v32@0:8@\"AFSiriAvailability\"16@?<v@?@\"AFSiriAvailability\"@\"NSError\">24"
+ "v44@0:8@16B24B28B32@?36"
+ "v64@0:8@16@24Q32d40@?48@?56"
+ "v64@0:8@16@24Q32d40Q48@?56"
+ "whitespaceAndNewlineCharacterSet"
+ "͏ᅟᅠ឴឵⠀ㅤﾠ"
+ "\u200c\u200d\u200e\u200f\u061c"
- "%s #SiriAvailability Application installation changed, re-evaluating capabilities"
- "+[ADAccount _accountForIdentifier:infoDictionary:intanceContext:isReadOnly:isCoupledToHost:keychainIsReadable:]"
- "-[ADCloudKitManager _scheduleStalledFetchCheckForZoneInfo:generation:delay:completion:]_block_invoke"
- "-[ADCloudKitManager _setUpMirroredZoneWithZoneInfo:]_block_invoke_2"
- "-[ADCommandCenter _handleExternalActivationRequest:fromRemotePeer:ownedByCurrentUser:completion:]"
- "-[ADCommandCenter sendMuxAsrRequestToServer:]_block_invoke"
- "-[ADSpeechManager audioSessionCoordinator:releaseAudioSessionWithContext:]_block_invoke"
- "MobileAssistantDaemons-3610.11.2.4.1"
- "_accountForIdentifier:infoDictionary:intanceContext:isReadOnly:isCoupledToHost:"
- "_accountForIdentifier:infoDictionary:intanceContext:isReadOnly:isCoupledToHost:keychainIsReadable:"
- "_handleExternalActivationRequest:fromRemotePeer:ownedByCurrentUser:completion:"
- "_scheduleStalledFetchCheckForZoneInfo:generation:delay:completion:"
- "sendMuxAsrRequestToServer:"
- "siriAvailabilityOverXPCEnabled"
- "v48@0:8@16Q24d32@?40"
```

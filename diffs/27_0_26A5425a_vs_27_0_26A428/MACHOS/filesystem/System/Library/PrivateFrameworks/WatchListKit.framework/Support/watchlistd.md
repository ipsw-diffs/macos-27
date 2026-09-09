## watchlistd

> `/System/Library/PrivateFrameworks/WatchListKit.framework/Support/watchlistd`

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

 952.0.1.0.0
-  __TEXT.__text: 0x29adc
+  __TEXT.__text: 0x28e58
   __TEXT.__auth_stubs: 0x7a0
   __TEXT.__objc_stubs: 0x4ec0
   __TEXT.__objc_methlist: 0x255c

   __TEXT.__objc_methname: 0x5c74
   __TEXT.__const: 0x118
   __TEXT.__gcc_except_tab: 0xc60
-  __TEXT.__unwind_info: 0xb18
+  __TEXT.__unwind_info: 0xcf8
   __DATA_CONST.__const: 0x1440
   __DATA_CONST.__cfstring: 0x38e0
   __DATA_CONST.__objc_classlist: 0x110
Functions:
~ +[AMSBag(WLKAdditions) wlk_defaultBag] : 272 -> 260
~ -[UWLPlayEvent mediaTypeAsString:] : 108 -> 84
~ -[UWLPlayEvent contractOrTimedAsString:] : 108 -> 84
~ -[UWLPlayEvent description] : 172 -> 160
~ -[UWLPlayEvent dictionaryRepresentation] : 1464 -> 1452
~ -[UWLPlayEvent writeTo:] : 888 -> 876
~ -[UWLPlayEvent copyTo:] : 912 -> 900
~ -[UWLPlayEvent mergeFrom:] : 948 -> 936
~ -[UWLPlayEvent .cxx_destruct] : 284 -> 272
~ ___59-[WLDClientConnection initWithConnection:clientIdentifier:]_block_invoke_2 : 72 -> 60
~ ___50-[WLDClientConnection requestNowPlayingSummaries:]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32b40r : 80 -> 68
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___59-[WLDClientConnection requestDecoratedNowPlayingSummaries:]_block_invoke : 84 -> 72
~ -[WLDClientConnection reportPlayback:sessionID:completion:] : 420 -> 408
~ -[WLDClientConnection endPlaybackSession:] : 100 -> 88
~ -[WLDClientConnection checkPendingPlaybackReports] : 72 -> 60
~ ___72-[WLDClientConnection requestConsentForBundleID:forceAuth:replyHandler:]_block_invoke : 160 -> 148
~ ___41-[WLDClientConnection readSettingsStore:]_block_invoke : 84 -> 72
~ ___55-[WLDClientConnection writeSettingsStore:replyHandler:]_block_invoke : 84 -> 72
~ ___49-[WLDClientConnection postSettings:replyHandler:]_block_invoke : 136 -> 124
~ ___37-[WLDClientConnection fetchSettings:]_block_invoke : 164 -> 152
~ ___56-[WLDClientConnection fetchLocationAuthorizationStatus:]_block_invoke : 84 -> 72
~ -[WLDClientConnection prewarm] : 92 -> 80
~ ___51-[WLDClientConnection saveOffer:completionHandler:]_block_invoke : 132 -> 120
~ ___62-[WLDClientConnection removeOfferByBadgeId:completionHandler:]_block_invoke : 132 -> 120
~ ___46-[WLDClientConnection fetchOffers:completion:]_block_invoke : 172 -> 160
~ ___35-[WLDClientConnection clearOffers:]_block_invoke : 132 -> 120
~ -[WLDClientConnection reportFederatedPunchout:] : 100 -> 88
~ -[WLDClientConnection vppaConsentedBundleIDsWithCompletion:] : 100 -> 88
~ ___91-[WLDClientConnection performSportsFavoritesAction:favoritesSyncEnabled:caller:completion:]_block_invoke : 80 -> 68
~ -[WLDClientConnection _didInvalidate] : 180 -> 168
~ -[WLDClientConnection delegate] : 44 -> 32
~ -[WLDClientConnection .cxx_destruct] : 88 -> 76
~ +[WLDServer server] : 68 -> 56
~ ___19+[WLDServer server]_block_invoke : 68 -> 56
~ -[WLDServer addClient:] : 172 -> 160
~ -[WLDServer clientConnectionDidInvalidate:] : 144 -> 132
~ -[WLDServer handleSubscriptionRegistration] : 64 -> 52
~ -[WLDServer handleAMSDeviceOffer] : 80 -> 68
~ -[WLDServer handleVideosUIInvalidationNotification:] : 76 -> 64
~ -[WLDServer _handleRestrictionsChangedNotification:] : 76 -> 64
~ -[WLDServer .cxx_destruct] : 92 -> 80
~ -[UWLLiveActivityEvent causeAsString:] : 112 -> 88
~ -[UWLLiveActivityEvent contractOrTimedAsString:] : 108 -> 84
~ -[UWLLiveActivityEvent description] : 172 -> 160
~ -[UWLLiveActivityEvent dictionaryRepresentation] : 780 -> 768
~ -[UWLLiveActivityEvent writeTo:] : 440 -> 428
~ -[UWLLiveActivityEvent copyTo:] : 460 -> 448
~ -[UWLLiveActivityEvent mergeFrom:] : 508 -> 496
~ -[UWLLiveActivityEvent .cxx_destruct] : 144 -> 132
~ -[WLDMercuryPushHandler handleNotification:shouldBadge:] : 544 -> 532
~ +[WLDMercuryPushHandler _getBadgeID:] : 108 -> 96
~ +[WLDMercuryPushHandler _addMercurySilentNotifOfferSource:badgeId:] : 216 -> 204
~ -[WLKFederatedPunchout(WLKFederatedPunchoutReporterAdditions) setTtl:] : 108 -> 96
~ -[WLKFederatedPunchout(WLKFederatedPunchoutReporterAdditions) setFailureReason:] : 108 -> 96
~ -[WLKFederatedPunchout(WLKFederatedPunchoutReporterAdditions) expiry] : 132 -> 120
~ +[WLDFederatedPunchoutReporter sharedFederatedPunchoutReporter] : 68 -> 56
~ ___63+[WLDFederatedPunchoutReporter sharedFederatedPunchoutReporter]_block_invoke : 64 -> 52
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[WLDFederatedPunchoutReporter _reportPunchoutEvent:withPlaybackSummary:] : 168 -> 156
~ -[WLDFederatedPunchoutReporter _metadataForEventWithPunchout:playbackSummary:] : 604 -> 592
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[WLDFederatedPunchoutReporter .cxx_destruct] : 80 -> 68
~ -[MapEntry description] : 172 -> 160
~ -[MapEntry dictionaryRepresentation] : 144 -> 132
~ -[MapEntry writeTo:] : 128 -> 116
~ -[MapEntry copyTo:] : 120 -> 108
~ -[MapEntry mergeFrom:] : 120 -> 108
~ -[MapEntry .cxx_destruct] : 84 -> 72
~ ___53-[WLDLivePlaybackReporter reportPlayback:completion:]_block_invoke_3 : 312 -> 300
~ ___53-[WLDLivePlaybackReporter reportPlayback:completion:]_block_invoke_4 : 116 -> 104
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ -[WLDLivePlaybackReporter getCachedCanonicalIDForSummary:completionHandler:] : 236 -> 224
~ -[WLDLivePlaybackReporter schedule] : 88 -> 76
~ -[WLDLivePlaybackReporter setSchedule:] : 160 -> 148
~ ___52-[WLDLivePlaybackReporter _processInput:completion:]_block_invoke : 392 -> 380
~ ___copy_helper_block_e8_32s40b48w : 84 -> 72
~ ___destroy_helper_block_e8_32s40s48w : 68 -> 56
~ ___76-[WLDLivePlaybackReporter _handlePlayerStateDidBecomePlayingWithCompletion:]_block_invoke : 236 -> 224
~ ___57-[WLDLivePlaybackReporter _handleTimerFiredAtEventStart:]_block_invoke_2 : 124 -> 112
~ ___63-[WLDLivePlaybackReporter _handleTimerFiredAtScheduleBoundary:]_block_invoke : 236 -> 224
~ ___67-[WLDLivePlaybackReporter _getScheduleWithPlaybackDate:completion:]_block_invoke : 244 -> 232
~ ___59+[WLDLivePlaybackReporter _decorateLiveSummary:completion:]_block_invoke_2 : 184 -> 172
~ ___copy_helper_block_e8_32b40w : 76 -> 64
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ ___58+[WLDLivePlaybackReporter _decorateEBSSummary:completion:]_block_invoke_2 : 184 -> 172
~ ___91-[WLDLivePlaybackReporter _evaluateEventsForReportingWithPlaybackDate:schedule:completion:]_block_invoke : 124 -> 112
~ ___64-[WLDLivePlaybackReporter _reportPlayEvents:account:completion:]_block_invoke : 240 -> 228
~ +[WLDLivePlaybackReporter _contentEventFromSummary:schedule:event:] : 348 -> 336
~ -[WLDLivePlaybackReporter _evaluateScheduleWithPlaybackDate:] : 416 -> 404
~ -[WLDLivePlaybackReporter _invalidateTimer] : 148 -> 136
~ -[WLDLivePlaybackReporter .cxx_destruct] : 116 -> 104
~ -[UWLOptOutEvent description] : 172 -> 160
~ -[UWLOptOutEvent dictionaryRepresentation] : 108 -> 96
~ -[UWLOptInEvent description] : 172 -> 160
~ -[UWLOptInEvent dictionaryRepresentation] : 108 -> 96
~ -[WLDPlayActivityReportOperation nextExpectedReportMillis] : 116 -> 104
~ -[WLDPlayActivityReportOperation _protoForURLRequest:] : 1136 -> 1124
~ -[WLDPlayActivityReportOperation _userAgentHeaderForRequest:] : 184 -> 172
~ -[WLDPlayActivityReportOperation .cxx_destruct] : 104 -> 92
~ _WLDOperationQueue : 68 -> 56
~ ___WLDOperationQueue_block_invoke : 120 -> 108
~ _WLDDispatchQueue : 68 -> 56
~ ___WLDDispatchQueue_block_invoke : 68 -> 56
~ -[UWLErrorResponse description] : 172 -> 160
~ -[UWLErrorResponse dictionaryRepresentation] : 136 -> 124
~ -[UWLLiveActivityEventChannel description] : 172 -> 160
~ -[UWLLiveActivityEventChannel dictionaryRepresentation] : 216 -> 204
~ -[UWLLiveActivityEventChannel writeTo:] : 192 -> 180
~ -[UWLLiveActivityEventChannel copyTo:] : 176 -> 164
~ -[UWLLiveActivityEventChannel mergeFrom:] : 176 -> 164
~ -[UWLLiveActivityEventChannel .cxx_destruct] : 124 -> 112
~ -[WLDUTSPushHandler _handlePayloadExpiredForNotificationType:] : 256 -> 232
~ ___62-[WLDUTSPushHandler _handlePayloadExpiredForNotificationType:]_block_invoke : 60 -> 48
~ -[WLDUTSPushHandler _handlePayloadInvalidatedForNotificationType:] : 256 -> 232
~ ___66-[WLDUTSPushHandler _handlePayloadInvalidatedForNotificationType:]_block_invoke : 60 -> 48
~ -[UWLMessageWireEnvelope addPlayEvents:] : 132 -> 120
~ -[UWLMessageWireEnvelope addOptInEvents:] : 132 -> 120
~ -[UWLMessageWireEnvelope addOptOutEvents:] : 132 -> 120
~ -[UWLMessageWireEnvelope addLiveActivityEvents:] : 132 -> 120
~ -[UWLMessageWireEnvelope description] : 172 -> 160
~ -[UWLMessageWireEnvelope dictionaryRepresentation] : 1324 -> 1312
~ -[UWLMessageWireEnvelope copyTo:] : 492 -> 480
~ -[UWLMessageWireEnvelope .cxx_destruct] : 144 -> 132
~ +[WLDPlaybackReporter _cachedMetadataByIdentifier] : 68 -> 56
~ ___50+[WLDPlaybackReporter _cachedMetadataByIdentifier]_block_invoke : 84 -> 72
~ +[WLDPlaybackReporter _cachedNotFoundIdentifiers] : 68 -> 56
~ ___49+[WLDPlaybackReporter _cachedNotFoundIdentifiers]_block_invoke : 64 -> 52
~ ___59-[WLDPlaybackReporter _reportPlayEvent:summary:completion:]_block_invoke : 200 -> 188
~ ___copy_helper_block_e8_32s40s48b56w : 92 -> 80
~ ___destroy_helper_block_e8_32s40s48s56w : 76 -> 64
~ ___copy_helper_block_e8_32s40s48w : 76 -> 64
~ -[WLDPlaybackReporter .cxx_destruct] : 92 -> 80
~ +[WLDPlaybackManager sharedManager] : 68 -> 56
~ ___35+[WLDPlaybackManager sharedManager]_block_invoke : 64 -> 52
~ ___26-[WLDPlaybackManager init]_block_invoke : 396 -> 384
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ -[WLDPlaybackManager handlePlaybackSummary:sessionID:] : 564 -> 552
~ ___47-[WLDPlaybackManager fetchNowPlayingSummaries:]_block_invoke : 120 -> 108
~ ___56-[WLDPlaybackManager fetchDecoratedNowPlayingSummaries:]_block_invoke : 136 -> 124
~ ___56-[WLDPlaybackManager fetchDecoratedNowPlayingSummaries:]_block_invoke_2 : 276 -> 264
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ __56-[WLDPlaybackManager fetchDecoratedNowPlayingSummaries:]_block_invoke.82 : 164 -> 152
~ __56-[WLDPlaybackManager fetchDecoratedNowPlayingSummaries:]_block_invoke_2.83 : 112 -> 100
~ ___52-[WLDPlaybackManager handleSubscriptionRegistration]_block_invoke : 348 -> 336
~ -[WLDPlaybackManager checkPendingReports] : 64 -> 52
~ -[WLDPlaybackManager queue] : 172 -> 160
~ -[WLDPlaybackManager reporter] : 76 -> 64
~ -[WLDPlaybackManager _getLastSummaryBySessionID:] : 164 -> 152
~ -[WLDPlaybackManager _removeLastSummaryBySessionID:] : 148 -> 136
~ -[WLDPlaybackManager _setSessionReporter:sessionID:] : 180 -> 168
~ -[WLDPlaybackManager _setLastSummaryBySessionID:sessionID:] : 176 -> 164
~ -[WLDPlaybackManager _getSessionReporterBySessionID:] : 164 -> 152
~ -[WLDPlaybackManager _removeReporterBySessionID:] : 208 -> 196
~ ___34-[WLDPlaybackManager _endSession:]_block_invoke : 88 -> 76
~ ___58-[WLDPlaybackManager _handleDirectPlaybackAppTermination:]_block_invoke : 240 -> 228
~ ___66-[WLDPlaybackManager _enqueuePlaybackSummary:sessionID:serialize:]_block_invoke_3 : 128 -> 104
~ ___copy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56s64w : 92 -> 80
~ ___destroy_helper_block_e8_32s40s48s56s64w : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56w : 84 -> 72
~ ___73-[WLDPlaybackManager _handleReporting:summary:sessionIDKey:isFirstParty:]_block_invoke : 252 -> 240
~ -[WLDPlaybackManager _handleReportingError:forSummary:] : 376 -> 364
~ ___51-[WLDPlaybackManager _onlineValidation:completion:]_block_invoke_3 : 572 -> 560
~ -[WLDPlaybackManager _promptForBundleID:completionHandler:] : 128 -> 116
~ -[WLDPlaybackManager _scanForPendingReports] : 2276 -> 2264
~ ___44-[WLDPlaybackManager _scanForPendingReports]_block_invoke_2 : 144 -> 132
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ -[WLDPlaybackManager _networkReachabilityChanged:] : 144 -> 132
~ -[WLDPlaybackManager _cleanupSummary:] : 100 -> 88
~ -[WLDPlaybackManager _queueDir] : 304 -> 292
~ -[WLDPlaybackManager _queuePathForSummary:] : 460 -> 448
~ -[WLDPlaybackManager .cxx_destruct] : 140 -> 128
~ ___main_block_invoke_2 : 360 -> 348
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ +[WLDChannelManager defaultChannelManager] : 68 -> 56
~ ___42+[WLDChannelManager defaultChannelManager]_block_invoke : 64 -> 52
~ +[WLDAppVisibilityManager sharedManager] : 68 -> 56
~ ___40+[WLDAppVisibilityManager sharedManager]_block_invoke : 64 -> 52
~ -[WLDAppVisibilityManager _networkReachabilityDidChangeNotification:] : 140 -> 128
~ -[WLDAppVisibilityManager _accountDidChangeNotification:] : 116 -> 104
~ +[WLDFullTVAppMonitor sharedInstance] : 68 -> 56
~ ___37+[WLDFullTVAppMonitor sharedInstance]_block_invoke : 64 -> 52
~ -[WLDFullTVAppMonitor _activeAccountChangedNotification:] : 72 -> 60
~ -[WLDPushNotificationController handleAction:] : 232 -> 220
~ -[WLDPushNotificationController _augmentCustomEventInfo:] : 732 -> 720
~ ___62-[WLDPushNotificationController _postNotificationWithPayload:]_block_invoke_2 : 88 -> 76
~ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96r : 128 -> 116
~ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96r : 120 -> 108
~ ___66-[WLDPushNotificationController _loadURLBagWithCompletionHandler:]_block_invoke : 208 -> 196
~ ___copy_helper_block_e8_32s40s48b56r : 96 -> 84
~ -[WLDPushNotificationController .cxx_destruct] : 152 -> 140
~ -[UWLLiveActivityEventContent description] : 172 -> 160
~ -[UWLLiveActivityEventContent dictionaryRepresentation] : 384 -> 372
~ -[UWLLiveActivityEventContent writeTo:] : 284 -> 272
~ -[UWLLiveActivityEventContent copyTo:] : 276 -> 264
~ -[UWLLiveActivityEventContent mergeFrom:] : 276 -> 264
~ -[UWLLiveActivityEventContent .cxx_destruct] : 124 -> 112
~ ___37-[WLDRateLimiter initWithRate:burst:]_block_invoke : 72 -> 60
~ -[WLDRateLimiter .cxx_destruct] : 68 -> 56
~ ___48-[WLDPlaybackDirectPlayObserver _startObserving]_block_invoke_2 : 148 -> 136
~ -[WLDPlaybackDirectPlayObserver _stopObserving] : 96 -> 84
~ -[WLDPlaybackDirectPlayObserver setAppIsRunning:] : 232 -> 220
~ -[WLDPlaybackDirectPlayObserver _identifier] : 152 -> 140
~ -[WLDPlaybackDirectPlayObserver .cxx_destruct] : 92 -> 80
~ +[WLDDeviceOfferManager amsDeviceOffertoDictionary:] : 580 -> 568
~ -[UWLMessageHeaders addCookies:] : 132 -> 120
~ -[UWLMessageHeaders description] : 172 -> 160
~ -[UWLMessageHeaders dictionaryRepresentation] : 756 -> 744
~ -[UWLMessageHeaders copyTo:] : 408 -> 396
~ -[UWLMessageHeaders .cxx_destruct] : 204 -> 192
~ +[WLDSubscriptionStore sharedInstance] : 68 -> 56
~ ___38+[WLDSubscriptionStore sharedInstance]_block_invoke : 64 -> 52
~ -[WLDSubscriptionStore _inflightCoalescingID] : 80 -> 68
~ -[WLDSubscriptionStore _setInflightCoalescingID:] : 112 -> 100
~ -[WLDSubscriptionStore _coalescedCompletion] : 100 -> 88
~ -[WLDSubscriptionStore _setCoalescedCompletion:] : 112 -> 100
~ ___74-[WLDSubscriptionStore _fetchDataFromCommerceWithCoalescingID:completion:]_block_invoke_2 : 148 -> 136
~ ___copy_helper_block_e8_32b40b : 80 -> 68
~ ___copy_helper_block_e8_32s40b48w56w : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48w56w : 76 -> 64
~ -[WLDSubscriptionStore _readFromDisk] : 240 -> 228
~ -[WLDSubscriptionStore _supportPath] : 112 -> 100
~ -[WLDSubscriptionStore _stubbedDataPath] : 112 -> 100
~ ___58-[WLDSubscriptionStore _activeAccountChangedNotification:]_block_invoke : 220 -> 208
~ __58-[WLDSubscriptionStore _activeAccountChangedNotification:]_block_invoke.49 : 232 -> 220
~ -[WLDSubscriptionStore _getSubscriptionDataMaxAge] : 136 -> 124
~ -[WLDSubscriptionStore .cxx_destruct] : 128 -> 116
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ -[WLDPlaybackNowPlayingObserver nowPlayingSummaries] : 724 -> 712
~ ___52-[WLDPlaybackNowPlayingObserver nowPlayingSummaries]_block_invoke : 264 -> 252
~ -[WLDPlaybackNowPlayingObserver _isPlayingDidChangeNotification:] : 204 -> 192
~ -[WLDPlaybackNowPlayingObserver _nowPlayingInfoDidChangeNotification:] : 136 -> 124
~ -[WLDPlaybackNowPlayingObserver _getActivePlayerPaths] : 108 -> 96
~ -[WLDPlaybackNowPlayingObserver _setActivePlayerPaths:] : 100 -> 88
~ -[WLDPlaybackNowPlayingObserver _fetchActivePlayerPaths] : 656 -> 644
~ ___56-[WLDPlaybackNowPlayingObserver _fetchActivePlayerPaths]_block_invoke : 84 -> 72
~ __56-[WLDPlaybackNowPlayingObserver _fetchActivePlayerPaths]_block_invoke.34 : 160 -> 148
~ -[WLDPlaybackNowPlayingObserver _nowPlayingInfoForPlayerPath:] : 512 -> 500
~ -[WLDPlaybackNowPlayingObserver _unsupportedMediaTypes] : 68 -> 56
~ -[WLDPlaybackNowPlayingObserver .cxx_destruct] : 116 -> 104
~ +[WLDAMSBagObserver sharedObserver] : 68 -> 56
~ ___35+[WLDAMSBagObserver sharedObserver]_block_invoke : 64 -> 52
~ __BagObserverLog : 68 -> 56
~ ____BagObserverLog_block_invoke : 72 -> 60
~ -[WLDSportsLiveActivityPushHandler handleSentimentNotification:completion:] : 160 -> 148
~ -[WLDSportsLiveActivityPushHandler connection] : 352 -> 340
~ -[UWLSectionInfo description] : 172 -> 160
~ -[UWLSectionInfo dictionaryRepresentation] : 356 -> 344
~ -[UWLSectionInfo writeTo:] : 236 -> 224
~ -[UWLSectionInfo copyTo:] : 248 -> 236
~ -[UWLSectionInfo mergeFrom:] : 248 -> 236
```

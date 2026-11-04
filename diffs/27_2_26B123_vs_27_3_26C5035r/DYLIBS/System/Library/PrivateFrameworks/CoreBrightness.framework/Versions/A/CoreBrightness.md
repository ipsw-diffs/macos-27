## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness`

```diff

-2300.41.8.0.0
-  __TEXT.__text: 0x167f10
-  __TEXT.__objc_methlist: 0xd888
-  __TEXT.__cstring: 0xd12a
-  __TEXT.__const: 0x129e8
-  __TEXT.__gcc_except_tab: 0x210c
-  __TEXT.__oslogstring: 0x18ffd
+2300.60.30.501.1
+  __TEXT.__text: 0x1773c0
+  __TEXT.__objc_methlist: 0xe1b0
+  __TEXT.__cstring: 0xd92a
+  __TEXT.__const: 0x130c8
+  __TEXT.__gcc_except_tab: 0x21b8
+  __TEXT.__oslogstring: 0x1ab5d
   __TEXT.__dlopen_cstrs: 0x10d
   __TEXT.__swift5_typeref: 0xf36
   __TEXT.__constg_swiftt: 0xd80

   __TEXT.__swift5_proto: 0x308
   __TEXT.__swift5_types: 0x144
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x7738
+  __TEXT.__unwind_info: 0x7bc0
   __TEXT.__eh_frame: 0xbd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1210
-  __DATA_CONST.__objc_classlist: 0x720
+  __DATA_CONST.__const: 0x1368
+  __DATA_CONST.__objc_classlist: 0x770
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x350
+  __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x5938
+  __DATA_CONST.__objc_selrefs: 0x5c78
   __DATA_CONST.__objc_protorefs: 0x138
-  __DATA_CONST.__objc_superrefs: 0x5c8
-  __DATA_CONST.__objc_arraydata: 0xc40
-  __DATA_CONST.__got: 0x7b8
-  __AUTH_CONST.__const: 0x5f88
-  __AUTH_CONST.__cfstring: 0xe8e0
-  __AUTH_CONST.__objc_const: 0x36758
+  __DATA_CONST.__objc_superrefs: 0x610
+  __DATA_CONST.__objc_arraydata: 0xf10
+  __DATA_CONST.__got: 0x7c0
+  __AUTH_CONST.__const: 0x6068
+  __AUTH_CONST.__cfstring: 0xf320
+  __AUTH_CONST.__objc_const: 0x3a1a0
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0xd08
-  __AUTH_CONST.__objc_floatobj: 0x180
-  __AUTH_CONST.__objc_arrayobj: 0x2d0
+  __AUTH_CONST.__objc_floatobj: 0x390
+  __AUTH_CONST.__objc_arrayobj: 0x618
   __AUTH_CONST.__objc_dictobj: 0x690
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x1300
-  __AUTH.__objc_data: 0x2940
-  __AUTH.__data: 0x6c0
-  __DATA.__objc_ivar: 0x17ec
-  __DATA.__data: 0x670c8
+  __AUTH_CONST.__auth_got: 0x1330
+  __AUTH.__objc_data: 0x2cb0
+  __AUTH.__data: 0x6b0
+  __DATA.__objc_ivar: 0x19d0
+  __DATA.__data: 0x671f8
   __DATA.__bss: 0x6440
   __DATA.__common: 0x10
-  __DATA_DIRTY.__objc_data: 0x21e8
+  __DATA_DIRTY.__objc_data: 0x2198
   __DATA_DIRTY.__data: 0x510
-  __DATA_DIRTY.__bss: 0x160
+  __DATA_DIRTY.__bss: 0x168
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreDisplay.framework/Versions/A/CoreDisplay
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8417
-  Symbols:   12866
-  CStrings:  4738
+  Functions: 8722
+  Symbols:   13462
+  CStrings:  4993
 
Symbols:
+ +[CBLEBacklightModeStore coerceMode:]
+ +[CBLEPWMContainer copyBacklightMatchingDictionary]
+ +[CBLEPWMContainer isPWMBacklightService:]
+ +[CBLEPWMContainer isValidBacklightService:]
+ -[BLControl setupLEManager]
+ -[CBDisplayContainerSKL setupBrightnessModulesExtGeneric:]
+ -[CBDisplayContainerSKL updateExtGenericOwnership]
+ -[CBDisplayModuleExtGeneric commitBrightness:]
+ -[CBDisplayModuleExtGeneric copyPropertyForKey:]
+ -[CBDisplayModuleExtGeneric dealloc]
+ -[CBDisplayModuleExtGeneric displayMode]
+ -[CBDisplayModuleExtGeneric handleDisplayModeUpdate:withDuration:callback:]
+ -[CBDisplayModuleExtGeneric handleNotificationForKey:withProperty:]
+ -[CBDisplayModuleExtGeneric initWithService:andQueue:andDisplayId:]
+ -[CBDisplayModuleExtGeneric newStatusInfo]
+ -[CBDisplayModuleExtGeneric probeBrightnessAttempt:]
+ -[CBDisplayModuleExtGeneric readControl:currentValue:maxValue:]
+ -[CBDisplayModuleExtGeneric setDisplayMode:]
+ -[CBDisplayModuleExtGeneric setProperty:forKey:]
+ -[CBDisplayModuleExtGeneric start]
+ -[CBDisplayModuleExtGeneric stop]
+ -[CBDisplayModuleExtGeneric writeControl:value:]
+ -[CBDisplayModuleSKL initialiseBrightDotMitigation]
+ -[CBDisplayModuleSKL initialiseFrameStats]
+ -[CBDisplayModuleSKL newAmmolite]
+ -[CBDisplayModuleSKL newTwilight]
+ -[CBDisplayModuleSKL rampBDMNitsCap:length:]
+ -[CBDisplayModuleSKL rampRTPLCCap:to:withSpeed:]
+ -[CBDisplayModuleSKL startRTPLCRampFrom:to:withSpeed:]
+ -[CBDisplayModuleSKL updateBDMWithLux:]
+ -[CBIOAVServiceLookup dealloc]
+ -[CBIOAVServiceLookup edidBytesMatchDisplay:]
+ -[CBIOAVServiceLookup handleServiceArrival:]
+ -[CBIOAVServiceLookup initWithVendorId:productId:serialNumber:queue:]
+ -[CBIOAVServiceLookup registerNotificationBlock:]
+ -[CBIOAVServiceLookup start]
+ -[CBIOAVServiceLookup stop]
+ -[CBIOAVServiceLookup unregisterNotificationBlock]
+ -[CBLEBacklightModeStore _handleObservedChange]
+ -[CBLEBacklightModeStore _readStore]
+ -[CBLEBacklightModeStore dealloc]
+ -[CBLEBacklightModeStore initWithQueue:suiteName:nodeName:nvram:externalChange:]
+ -[CBLEBacklightModeStore invalidate]
+ -[CBLEBacklightModeStore mode]
+ -[CBLEBacklightModeStore observeValueForKeyPath:ofObject:change:context:]
+ -[CBLEBacklightModeStore setMode:]
+ -[CBLENVRAM boolForKey:outValue:]
+ -[CBLEPWMAutoBrightnessModule _alsNodeForService:]
+ -[CBLEPWMAutoBrightnessModule _defaultMappingTable]
+ -[CBLEPWMAutoBrightnessModule _defaultluxToMaxNitsRestrictionTable]
+ -[CBLEPWMAutoBrightnessModule _defaultluxToMinNitsRestrictionTable]
+ -[CBLEPWMAutoBrightnessModule _loadRestrictionRampDurationForKey:default:]
+ -[CBLEPWMAutoBrightnessModule _loadStartupRampDurationFromDefaults]
+ -[CBLEPWMAutoBrightnessModule _mapDisplayNitsToPWMNits:]
+ -[CBLEPWMAutoBrightnessModule _mapLuxToMaxNits:]
+ -[CBLEPWMAutoBrightnessModule _mapLuxToMinNits:]
+ -[CBLEPWMAutoBrightnessModule _pendingRestriction:current:]
+ -[CBLEPWMAutoBrightnessModule _restrictionRampDurationForPerceptualDelta:]
+ -[CBLEPWMAutoBrightnessModule _setNits:withFadeSpeed:]
+ -[CBLEPWMAutoBrightnessModule addHIDServiceClient:]
+ -[CBLEPWMAutoBrightnessModule copyIdentifiers]
+ -[CBLEPWMAutoBrightnessModule copyPropertyForKey:]
+ -[CBLEPWMAutoBrightnessModule copyPropertyForKey:withParameter:]
+ -[CBLEPWMAutoBrightnessModule copyPropertyInternalForKey:]
+ -[CBLEPWMAutoBrightnessModule dealloc]
+ -[CBLEPWMAutoBrightnessModule handleALSEvent:]
+ -[CBLEPWMAutoBrightnessModule handleDisplayBrightnessUpdate:]
+ -[CBLEPWMAutoBrightnessModule handleEvent:]
+ -[CBLEPWMAutoBrightnessModule handleNotificationForKey:withProperty:]
+ -[CBLEPWMAutoBrightnessModule initWithControlModule:configProvider:queue:]
+ -[CBLEPWMAutoBrightnessModule removeHIDServiceClient:]
+ -[CBLEPWMAutoBrightnessModule setProperty:forKey:]
+ -[CBLEPWMAutoBrightnessModule start]
+ -[CBLEPWMAutoBrightnessModule stop]
+ -[CBLEPWMContainer _copyContainerStatusInfo]
+ -[CBLEPWMContainer _initializeInternalModules]
+ -[CBLEPWMContainer _teardownInternalModules]
+ -[CBLEPWMContainer addHIDServiceClient:]
+ -[CBLEPWMContainer copyIdentifiers]
+ -[CBLEPWMContainer copyPropertyForKey:]
+ -[CBLEPWMContainer copyPropertyInternalForKey:]
+ -[CBLEPWMContainer dealloc]
+ -[CBLEPWMContainer getBacklightServiceID]
+ -[CBLEPWMContainer handleEvent:]
+ -[CBLEPWMContainer handleNotificationForKey:withProperty:]
+ -[CBLEPWMContainer initWithBacklightService:systemContext:]
+ -[CBLEPWMContainer registerNotificationBlock:]
+ -[CBLEPWMContainer removeHIDServiceClient:]
+ -[CBLEPWMContainer sendNotificationForKey:andValue:]
+ -[CBLEPWMContainer setProperty:forKey:]
+ -[CBLEPWMContainer start]
+ -[CBLEPWMContainer stop]
+ -[CBLEPWMContainer unregisterNotificationBlock]
+ -[CBLEPWMControlModule _applyFactorToHardware]
+ -[CBLEPWMControlModule _copyModuleStatusInfo]
+ -[CBLEPWMControlModule _currentState]
+ -[CBLEPWMControlModule _didWriteEffectiveNits:]
+ -[CBLEPWMControlModule _displayReadyForFactorOnRamp:]
+ -[CBLEPWMControlModule _effectiveNitsForBase:]
+ -[CBLEPWMControlModule _evaluateAndApplyFactor]
+ -[CBLEPWMControlModule _factorRampDurationForBaseNits:turningOn:]
+ -[CBLEPWMControlModule _handleModeChange]
+ -[CBLEPWMControlModule _resolveTargetFactor]
+ -[CBLEPWMControlModule _setNits:]
+ -[CBLEPWMControlModule _setNits:withFadeSpeed:]
+ -[CBLEPWMControlModule _startFactorRampToTarget:baseNits:]
+ -[CBLEPWMControlModule _stringForDisplayLogicalState:]
+ -[CBLEPWMControlModule _stringForDisplayPowerStateEvent:]
+ -[CBLEPWMControlModule appliedNits]
+ -[CBLEPWMControlModule copyIdentifiers]
+ -[CBLEPWMControlModule copyPropertyForKey:]
+ -[CBLEPWMControlModule copyPropertyForKey:withParameter:]
+ -[CBLEPWMControlModule copyPropertyInternalForKey:]
+ -[CBLEPWMControlModule dealloc]
+ -[CBLEPWMControlModule factorRampInProgress]
+ -[CBLEPWMControlModule handleNotificationForKey:withProperty:]
+ -[CBLEPWMControlModule initWithBacklightService:queue:]
+ -[CBLEPWMControlModule rampFactorToTarget:withLength:useSpringProfile:]
+ -[CBLEPWMControlModule setBootNits:]
+ -[CBLEPWMControlModule setDisplayBrightnessZero:]
+ -[CBLEPWMControlModule setNits:withFadeSpeed:state:]
+ -[CBLEPWMControlModule setProperty:forKey:]
+ -[CBLEPWMControlModule start]
+ -[CBLEPWMControlModule stop]
+ -[CBLEPWMDisplayReadyGate _enterProviderStage]
+ -[CBLEPWMDisplayReadyGate _enterSwapStage]
+ -[CBLEPWMDisplayReadyGate _frameShowsLitDisplay:]
+ -[CBLEPWMDisplayReadyGate _handleFrameInfo:generation:]
+ -[CBLEPWMDisplayReadyGate _open:]
+ -[CBLEPWMDisplayReadyGate _setTimeoutSeconds:]
+ -[CBLEPWMDisplayReadyGate _updateStage]
+ -[CBLEPWMDisplayReadyGate arm]
+ -[CBLEPWMDisplayReadyGate armed]
+ -[CBLEPWMDisplayReadyGate dealloc]
+ -[CBLEPWMDisplayReadyGate disarm]
+ -[CBLEPWMDisplayReadyGate frameInfoProviderAttached]
+ -[CBLEPWMDisplayReadyGate initWithQueue:logHandle:onReady:]
+ -[CBLEPWMDisplayReadyGate setFrameInfoProvider:]
+ -[CBLEPWMDisplayReadyGate shouldGate]
+ -[CBLEPWMDisplayReadyGate waitingForProvider]
+ -[CBLEPWMNitsMultiplier _evaluate]
+ -[CBLEPWMNitsMultiplier _forwardLastNits]
+ -[CBLEPWMNitsMultiplier _forwardNits:withFadeSpeed:]
+ -[CBLEPWMNitsMultiplier _loadConfigFromProvider:]
+ -[CBLEPWMNitsMultiplier _loadScalar:fromProvider:default:]
+ -[CBLEPWMNitsMultiplier _resolvedChargerMultiplier]
+ -[CBLEPWMNitsMultiplier _scaledNits:]
+ -[CBLEPWMNitsMultiplier dealloc]
+ -[CBLEPWMNitsMultiplier factorRampInProgress]
+ -[CBLEPWMNitsMultiplier initWithNitsControl:configProvider:queue:]
+ -[CBLEPWMNitsMultiplier initWithNitsControl:configProvider:queue:enclosureColorProvider:clockSource:]
+ -[CBLEPWMNitsMultiplier multiplier]
+ -[CBLEPWMNitsMultiplier setChargerState:]
+ -[CBLEPWMNitsMultiplier setNits:withFadeSpeed:state:]
+ -[CBLEPWMNitsMultiplier start]
+ -[CBLEPWMNitsMultiplier stop]
+ -[CBLEPWMNitsMultiplier targetMultiplier]
+ -[CBLEPWMNitsMultiplier updateLux:]
+ -[CBLEPWMNitsRateLimiter _clockFollowRamp:]
+ -[CBLEPWMNitsRateLimiter _defaultFallRateTable]
+ -[CBLEPWMNitsRateLimiter _defaultRiseRateTable]
+ -[CBLEPWMNitsRateLimiter _insertFollowRamp]
+ -[CBLEPWMNitsRateLimiter _loadRateTableForKey:default:]
+ -[CBLEPWMNitsRateLimiter _loadTauFromDefaults]
+ -[CBLEPWMNitsRateLimiter _now]
+ -[CBLEPWMNitsRateLimiter _pushOutputNits:withFadeSpeed:atTime:]
+ -[CBLEPWMNitsRateLimiter _rateForOutputNits:rising:]
+ -[CBLEPWMNitsRateLimiter _rateForRemaining:atTimestamp:]
+ -[CBLEPWMNitsRateLimiter _snapToTarget:]
+ -[CBLEPWMNitsRateLimiter appliedNits]
+ -[CBLEPWMNitsRateLimiter armStartupRampFromNits:duration:]
+ -[CBLEPWMNitsRateLimiter cancel]
+ -[CBLEPWMNitsRateLimiter dealloc]
+ -[CBLEPWMNitsRateLimiter initWithNitsControl:queue:]
+ -[CBLEPWMNitsRateLimiter initWithNitsControl:queue:clockSource:]
+ -[CBLEPWMNitsRateLimiter setNits:withFadeSpeed:state:]
+ -[CBLEPWMNitsRateLimiter start]
+ -[CBLEPWMNitsRateLimiter stop]
+ -[CBSliderMappingGenericMac configureSegmentCoefficients]
+ -[CBSliderMappingGenericMac copyStatusInfo]
+ -[CBSliderMappingGenericMac initWithPanelParameters:]
+ -[CBSliderMappingGenericMac nitsForSlider:]
+ -[CBSliderMappingGenericMac sliderForNits:]
+ -[CBSliderMappingGenericMac validateParameters]
+ GCC_except_table203
+ GCC_except_table240
+ GCC_except_table255
+ GCC_except_table70
+ GCC_except_table89
+ _CBU_isExtGenericDisplayEnabled
+ _CBU_isExtGenericDisplayEnabled.once
+ _CBU_isExtGenericDisplayEnabled.result
+ _IOAVServiceCopyEDID
+ _IOAVServiceCreateWithService
+ _IOAVServiceGetLocation
+ _IOAVServiceReadI2C
+ _IOAVServiceWriteI2C
+ _OBJC_CLASS_$_CBDisplayModuleExtGeneric
+ _OBJC_CLASS_$_CBIOAVServiceLookup
+ _OBJC_CLASS_$_CBLEBacklightModeStore
+ _OBJC_CLASS_$_CBLENVRAM
+ _OBJC_CLASS_$_CBLEPWMAutoBrightnessModule
+ _OBJC_CLASS_$_CBLEPWMContainer
+ _OBJC_CLASS_$_CBLEPWMControlModule
+ _OBJC_CLASS_$_CBLEPWMDisplayReadyGate
+ _OBJC_CLASS_$_CBLEPWMNitsMultiplier
+ _OBJC_CLASS_$_CBLEPWMNitsRateLimiter
+ _OBJC_CLASS_$_CBSliderMappingGenericMac
+ _OBJC_IVAR_$_BLControl._leManager
+ _OBJC_IVAR_$_CBDisplayContainerSKL._extGenericModuleActive
+ _OBJC_IVAR_$_CBDisplayContainerSKL._extGenericService
+ _OBJC_IVAR_$_CBDisplayContainerSKL._extGenericServiceLookup
+ _OBJC_IVAR_$_CBDisplayContainerSKL._maybeExtGeneric
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._avService
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._displayId
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._displayMode
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._logHandle
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._maxLevel
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._slider
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._userBrightness
+ _OBJC_IVAR_$_CBDisplayModuleSKL._ammolite
+ _OBJC_IVAR_$_CBDisplayModuleSKL._bdm
+ _OBJC_IVAR_$_CBDisplayModuleSKL._bdmCurrentCap
+ _OBJC_IVAR_$_CBDisplayModuleSKL._rtplc
+ _OBJC_IVAR_$_CBDisplayModuleSKL._sbim
+ _OBJC_IVAR_$_CBDisplayModuleSKL._twilight
+ _OBJC_IVAR_$_CBIOAVServiceLookup._foundBlock
+ _OBJC_IVAR_$_CBIOAVServiceLookup._logHandle
+ _OBJC_IVAR_$_CBIOAVServiceLookup._notificationPort
+ _OBJC_IVAR_$_CBIOAVServiceLookup._productId
+ _OBJC_IVAR_$_CBIOAVServiceLookup._queue
+ _OBJC_IVAR_$_CBIOAVServiceLookup._serialNumber
+ _OBJC_IVAR_$_CBIOAVServiceLookup._serviceIterator
+ _OBJC_IVAR_$_CBIOAVServiceLookup._vendorId
+ _OBJC_IVAR_$_CBLEBacklightModeStore._defaults
+ _OBJC_IVAR_$_CBLEBacklightModeStore._enabledKey
+ _OBJC_IVAR_$_CBLEBacklightModeStore._handler
+ _OBJC_IVAR_$_CBLEBacklightModeStore._invalidated
+ _OBJC_IVAR_$_CBLEBacklightModeStore._logHandle
+ _OBJC_IVAR_$_CBLEBacklightModeStore._mode
+ _OBJC_IVAR_$_CBLEBacklightModeStore._nvram
+ _OBJC_IVAR_$_CBLEBacklightModeStore._queue
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._alsNodes
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._builtInDisplayID
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._controlModule
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._lastDisplayNits
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._lastLux
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._lastRequestedNits
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._luxToMaxNitsRestrictionTable
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._luxToMinNitsRestrictionTable
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._mappingTable
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._maxNitsRestriction
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._minNitsRestriction
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._nitsMultiplier
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._rampManager
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._rateLimiter
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._restrictionFallDuration
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._restrictionRiseDuration
+ _OBJC_IVAR_$_CBLEPWMAutoBrightnessModule._startupRampDuration
+ _OBJC_IVAR_$_CBLEPWMContainer._autoBrightnessModule
+ _OBJC_IVAR_$_CBLEPWMContainer._backlightService
+ _OBJC_IVAR_$_CBLEPWMContainer._controlModule
+ _OBJC_IVAR_$_CBLEPWMContainer._modules
+ _OBJC_IVAR_$_CBLEPWMContainer._nodeName
+ _OBJC_IVAR_$_CBLEPWMContainer._registryID
+ _OBJC_IVAR_$_CBLEPWMContainer._running
+ _OBJC_IVAR_$_CBLEPWMControlModule._bootNits
+ _OBJC_IVAR_$_CBLEPWMControlModule._clamshellClosed
+ _OBJC_IVAR_$_CBLEPWMControlModule._clamshellDrivenTransition
+ _OBJC_IVAR_$_CBLEPWMControlModule._displayBrightnessZero
+ _OBJC_IVAR_$_CBLEPWMControlModule._displayLogicalState
+ _OBJC_IVAR_$_CBLEPWMControlModule._displayPowerState
+ _OBJC_IVAR_$_CBLEPWMControlModule._displayReadyGate
+ _OBJC_IVAR_$_CBLEPWMControlModule._driver
+ _OBJC_IVAR_$_CBLEPWMControlModule._factor
+ _OBJC_IVAR_$_CBLEPWMControlModule._factorFadeDurationOverride
+ _OBJC_IVAR_$_CBLEPWMControlModule._factorRampInProgress
+ _OBJC_IVAR_$_CBLEPWMControlModule._frozenNits
+ _OBJC_IVAR_$_CBLEPWMControlModule._lastEffectiveNits
+ _OBJC_IVAR_$_CBLEPWMControlModule._lastNits
+ _OBJC_IVAR_$_CBLEPWMControlModule._modeStore
+ _OBJC_IVAR_$_CBLEPWMControlModule._nodeName
+ _OBJC_IVAR_$_CBLEPWMControlModule._pendingNits
+ _OBJC_IVAR_$_CBLEPWMControlModule._pendingState
+ _OBJC_IVAR_$_CBLEPWMControlModule._rampManager
+ _OBJC_IVAR_$_CBLEPWMControlModule._shutdownInProgress
+ _OBJC_IVAR_$_CBLEPWMControlModule._springProfile
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._armMillis
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._armed
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._deadlineMillis
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._frameInfoProvider
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._logHandle
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._observerGeneration
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._observerRegistered
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._onReady
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._providerEverAttached
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._queue
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._stageFireMillis
+ _OBJC_IVAR_$_CBLEPWMDisplayReadyGate._timeout
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._chargerColors
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._chargerConnected
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._chargerMultiplier
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._chargerMultipliers
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._enclosureColorProvider
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._fullScaleLux
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._lastLux
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._lastNits
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._lastState
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._logHandle
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._multiplier
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._nitsControl
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._queue
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._rampDuration
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._rampManager
+ _OBJC_IVAR_$_CBLEPWMNitsMultiplier._running
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._appliedNits
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._clockSource
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._fallRateTable
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._lastOutputTime
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._logHandle
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._nitsControl
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._queue
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._rampManager
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._riseRateTable
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._startupRampDeadline
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._startupRampDuration
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._startupRampPending
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._state
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._targetNits
+ _OBJC_IVAR_$_CBLEPWMNitsRateLimiter._tau
+ _OBJC_IVAR_$_CBSliderMappingGenericMac._b1
+ _OBJC_IVAR_$_CBSliderMappingGenericMac._b2
+ _OBJC_IVAR_$_CBSliderMappingGenericMac._m1
+ _OBJC_IVAR_$_CBSliderMappingGenericMac._m2
+ _OBJC_IVAR_$_CBSliderMappingGenericMac._panelParameters
+ _OBJC_IVAR_$_VMDisplayModule._requestDelegate
+ _OBJC_METACLASS_$_CBDisplayModuleExtGeneric
+ _OBJC_METACLASS_$_CBIOAVServiceLookup
+ _OBJC_METACLASS_$_CBLEBacklightModeStore
+ _OBJC_METACLASS_$_CBLENVRAM
+ _OBJC_METACLASS_$_CBLEPWMAutoBrightnessModule
+ _OBJC_METACLASS_$_CBLEPWMContainer
+ _OBJC_METACLASS_$_CBLEPWMControlModule
+ _OBJC_METACLASS_$_CBLEPWMDisplayReadyGate
+ _OBJC_METACLASS_$_CBLEPWMNitsMultiplier
+ _OBJC_METACLASS_$_CBLEPWMNitsRateLimiter
+ _OBJC_METACLASS_$_CBSliderMappingGenericMac
+ _RTPLC_RAMP
+ __OBJC_$_CLASS_METHODS_CBLEBacklightModeStore
+ __OBJC_$_CLASS_METHODS_CBLEPWMContainer
+ __OBJC_$_INSTANCE_METHODS_CBDisplayModuleExtGeneric
+ __OBJC_$_INSTANCE_METHODS_CBIOAVServiceLookup
+ __OBJC_$_INSTANCE_METHODS_CBLEBacklightModeStore
+ __OBJC_$_INSTANCE_METHODS_CBLENVRAM
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMAutoBrightnessModule
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMContainer
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMControlModule
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMDisplayReadyGate
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMNitsMultiplier
+ __OBJC_$_INSTANCE_METHODS_CBLEPWMNitsRateLimiter
+ __OBJC_$_INSTANCE_METHODS_CBSliderMappingGenericMac
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayModuleExtGeneric
+ __OBJC_$_INSTANCE_VARIABLES_CBIOAVServiceLookup
+ __OBJC_$_INSTANCE_VARIABLES_CBLEBacklightModeStore
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMAutoBrightnessModule
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMContainer
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMControlModule
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMDisplayReadyGate
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMNitsMultiplier
+ __OBJC_$_INSTANCE_VARIABLES_CBLEPWMNitsRateLimiter
+ __OBJC_$_INSTANCE_VARIABLES_CBSliderMappingGenericMac
+ __OBJC_$_PROP_LIST_CBDisplayModuleExtGeneric
+ __OBJC_$_PROP_LIST_CBIOAVServiceLookup
+ __OBJC_$_PROP_LIST_CBLEBacklightModeStore
+ __OBJC_$_PROP_LIST_CBLENVRAM
+ __OBJC_$_PROP_LIST_CBLEPWMAutoBrightnessModule
+ __OBJC_$_PROP_LIST_CBLEPWMContainer
+ __OBJC_$_PROP_LIST_CBLEPWMControlModule
+ __OBJC_$_PROP_LIST_CBLEPWMDisplayReadyGate
+ __OBJC_$_PROP_LIST_CBLEPWMNitsControlProtocol
+ __OBJC_$_PROP_LIST_CBLEPWMNitsMultiplier
+ __OBJC_$_PROP_LIST_CBLEPWMNitsRateLimiter
+ __OBJC_$_PROP_LIST_CBSliderMappingGenericMac
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBLENVRAMStore
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBLEPWMNitsControlProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBServiceLookupProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_VMRequestDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBLENVRAMStore
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBLEPWMNitsControlProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBServiceLookupProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_VMRequestDelegate
+ __OBJC_$_PROTOCOL_REFS_CBLENVRAMStore
+ __OBJC_$_PROTOCOL_REFS_CBLEPWMNitsControlProtocol
+ __OBJC_$_PROTOCOL_REFS_CBServiceLookupProtocol
+ __OBJC_$_PROTOCOL_REFS_VMRequestDelegate
+ __OBJC_CLASS_PROTOCOLS_$_CBDisplayModuleExtGeneric
+ __OBJC_CLASS_PROTOCOLS_$_CBIOAVServiceLookup
+ __OBJC_CLASS_PROTOCOLS_$_CBLENVRAM
+ __OBJC_CLASS_PROTOCOLS_$_CBLEPWMAutoBrightnessModule
+ __OBJC_CLASS_PROTOCOLS_$_CBLEPWMContainer
+ __OBJC_CLASS_PROTOCOLS_$_CBLEPWMControlModule
+ __OBJC_CLASS_PROTOCOLS_$_CBLEPWMNitsMultiplier
+ __OBJC_CLASS_PROTOCOLS_$_CBSliderMappingGenericMac
+ __OBJC_CLASS_RO_$_CBDisplayModuleExtGeneric
+ __OBJC_CLASS_RO_$_CBIOAVServiceLookup
+ __OBJC_CLASS_RO_$_CBLEBacklightModeStore
+ __OBJC_CLASS_RO_$_CBLENVRAM
+ __OBJC_CLASS_RO_$_CBLEPWMAutoBrightnessModule
+ __OBJC_CLASS_RO_$_CBLEPWMContainer
+ __OBJC_CLASS_RO_$_CBLEPWMControlModule
+ __OBJC_CLASS_RO_$_CBLEPWMDisplayReadyGate
+ __OBJC_CLASS_RO_$_CBLEPWMNitsMultiplier
+ __OBJC_CLASS_RO_$_CBLEPWMNitsRateLimiter
+ __OBJC_CLASS_RO_$_CBSliderMappingGenericMac
+ __OBJC_LABEL_PROTOCOL_$_CBLENVRAMStore
+ __OBJC_LABEL_PROTOCOL_$_CBLEPWMNitsControlProtocol
+ __OBJC_LABEL_PROTOCOL_$_CBServiceLookupProtocol
+ __OBJC_LABEL_PROTOCOL_$_VMRequestDelegate
+ __OBJC_METACLASS_RO_$_CBDisplayModuleExtGeneric
+ __OBJC_METACLASS_RO_$_CBIOAVServiceLookup
+ __OBJC_METACLASS_RO_$_CBLEBacklightModeStore
+ __OBJC_METACLASS_RO_$_CBLENVRAM
+ __OBJC_METACLASS_RO_$_CBLEPWMAutoBrightnessModule
+ __OBJC_METACLASS_RO_$_CBLEPWMContainer
+ __OBJC_METACLASS_RO_$_CBLEPWMControlModule
+ __OBJC_METACLASS_RO_$_CBLEPWMDisplayReadyGate
+ __OBJC_METACLASS_RO_$_CBLEPWMNitsMultiplier
+ __OBJC_METACLASS_RO_$_CBLEPWMNitsRateLimiter
+ __OBJC_METACLASS_RO_$_CBSliderMappingGenericMac
+ __OBJC_PROTOCOL_$_CBLENVRAMStore
+ __OBJC_PROTOCOL_$_CBLEPWMNitsControlProtocol
+ __OBJC_PROTOCOL_$_CBServiceLookupProtocol
+ __OBJC_PROTOCOL_$_VMRequestDelegate
+ __ZN14CoreBrightnessL14sbimLimitsK11pE
+ ___101-[CBLEPWMNitsMultiplier initWithNitsControl:configProvider:queue:enclosureColorProvider:clockSource:]_block_invoke
+ ___24-[CBLEPWMContainer stop]_block_invoke
+ ___25-[CBLEPWMContainer start]_block_invoke
+ ___27-[BLControl setupLEManager]_block_invoke
+ ___30-[CBLEPWMDisplayReadyGate arm]_block_invoke
+ ___32-[CBLEPWMContainer handleEvent:]_block_invoke
+ ___32-[CBLEPWMContainer handleEvent:]_block_invoke_2
+ ___33-[CBDisplayModuleSKL newAmmolite]_block_invoke
+ ___33-[CBDisplayModuleSKL newTwilight]_block_invoke
+ ___39-[CBLEPWMContainer copyPropertyForKey:]_block_invoke
+ ___39-[CBLEPWMContainer copyPropertyForKey:]_block_invoke_2
+ ___39-[CBLEPWMContainer setProperty:forKey:]_block_invoke
+ ___39-[CBLEPWMContainer setProperty:forKey:]_block_invoke_2
+ ___40-[CBLEPWMContainer addHIDServiceClient:]_block_invoke
+ ___40-[CBLEPWMContainer addHIDServiceClient:]_block_invoke_2
+ ___41-[CBLEPWMControlModule _handleModeChange]_block_invoke
+ ___42-[CBDisplayModuleExtGeneric newStatusInfo]_block_invoke
+ ___42-[CBLEPWMDisplayReadyGate _enterSwapStage]_block_invoke
+ ___42-[CBLEPWMDisplayReadyGate _enterSwapStage]_block_invoke_2
+ ___43-[CBLEPWMContainer removeHIDServiceClient:]_block_invoke
+ ___43-[CBLEPWMContainer removeHIDServiceClient:]_block_invoke_2
+ ___43-[CBLEPWMNitsRateLimiter _insertFollowRamp]_block_invoke
+ ___44-[CBDisplayModuleSKL rampBDMNitsCap:length:]_block_invoke
+ ___46-[CBLEPWMAutoBrightnessModule handleALSEvent:]_block_invoke
+ ___46-[CBLEPWMContainer _initializeInternalModules]_block_invoke
+ ___46-[CBLEPWMContainer _initializeInternalModules]_block_invoke_2
+ ___48-[CBDisplayModuleSKL rampRTPLCCap:to:withSpeed:]_block_invoke
+ ___48-[CBLEPWMDisplayReadyGate setFrameInfoProvider:]_block_invoke
+ ___52-[CBDisplayModuleExtGeneric probeBrightnessAttempt:]_block_invoke
+ ___52-[CBLEPWMContainer sendNotificationForKey:andValue:]_block_invoke
+ ___52-[CBLEPWMContainer sendNotificationForKey:andValue:]_block_invoke_2
+ ___55-[CBLEPWMControlModule initWithBacklightService:queue:]_block_invoke
+ ___55-[CBLEPWMControlModule initWithBacklightService:queue:]_block_invoke_2
+ ___58-[CBDisplayContainerSKL setupBrightnessModulesExtGeneric:]_block_invoke
+ ___58-[CBLEPWMContainer handleNotificationForKey:withProperty:]_block_invoke
+ ___58-[CBLEPWMControlModule _startFactorRampToTarget:baseNits:]_block_invoke
+ ___73-[CBLEBacklightModeStore observeValueForKeyPath:ofObject:change:context:]_block_invoke
+ ___CBU_isExtGenericDisplayEnabled_block_invoke
+ ___IOAVClassMatching
+ ___block_descriptor_40_e16_v16?0"CBRamp"8ls32l8
+ ___block_descriptor_40_e19_f20?0f8"CBRamp"12ls32l8
+ ___block_descriptor_40_e23_v16?0"CBRampManager"8ls32l8
+ ___block_descriptor_40_e5_v8?0ls32l8
+ ___block_descriptor_40_e8_32w_e8_v16?08l
+ ___block_descriptor_40_e8_v16?0q8ls32l8
+ ___block_descriptor_40_e9_v16?0r*8ls32l8
+ ___block_descriptor_48_e8_32o40w_e11_v24?0816l
+ ___block_descriptor_48_e8_32o_e19_v40?0{?=QIBBffff}8l
+ ___block_descriptor_56_e8_32o40o48r_e44_v32?0"<CBContainerModuleProtocol>"8Q16^B24l
+ ___copy_helper_block_e8_32o40w
+ ___destroy_helper_block_e8_32o40w
+ _kLEPWMChargerEnclosureColorsDefault
+ _kLEPWMChargerMultipliersDefault
+ _objc_loadWeak
+ _objc_msgSend$_alsNodeForService:
+ _objc_msgSend$_applyFactorToHardware
+ _objc_msgSend$_clockFollowRamp:
+ _objc_msgSend$_copyContainerStatusInfo
+ _objc_msgSend$_copyModuleStatusInfo
+ _objc_msgSend$_currentState
+ _objc_msgSend$_defaultFallRateTable
+ _objc_msgSend$_defaultMappingTable
+ _objc_msgSend$_defaultRiseRateTable
+ _objc_msgSend$_defaultluxToMaxNitsRestrictionTable
+ _objc_msgSend$_defaultluxToMinNitsRestrictionTable
+ _objc_msgSend$_didWriteEffectiveNits:
+ _objc_msgSend$_displayReadyForFactorOnRamp:
+ _objc_msgSend$_effectiveNitsForBase:
+ _objc_msgSend$_enterProviderStage
+ _objc_msgSend$_enterSwapStage
+ _objc_msgSend$_evaluate
+ _objc_msgSend$_evaluateAndApplyFactor
+ _objc_msgSend$_factorRampDurationForBaseNits:turningOn:
+ _objc_msgSend$_forwardLastNits
+ _objc_msgSend$_forwardNits:withFadeSpeed:
+ _objc_msgSend$_frameShowsLitDisplay:
+ _objc_msgSend$_handleFrameInfo:generation:
+ _objc_msgSend$_handleModeChange
+ _objc_msgSend$_handleObservedChange
+ _objc_msgSend$_insertFollowRamp
+ _objc_msgSend$_loadConfigFromProvider:
+ _objc_msgSend$_loadRateTableForKey:default:
+ _objc_msgSend$_loadRestrictionRampDurationForKey:default:
+ _objc_msgSend$_loadScalar:fromProvider:default:
+ _objc_msgSend$_loadStartupRampDurationFromDefaults
+ _objc_msgSend$_loadTauFromDefaults
+ _objc_msgSend$_mapDisplayNitsToPWMNits:
+ _objc_msgSend$_mapLuxToMaxNits:
+ _objc_msgSend$_mapLuxToMinNits:
+ _objc_msgSend$_now
+ _objc_msgSend$_open:
+ _objc_msgSend$_pendingRestriction:current:
+ _objc_msgSend$_pushOutputNits:withFadeSpeed:atTime:
+ _objc_msgSend$_rateForOutputNits:rising:
+ _objc_msgSend$_rateForRemaining:atTimestamp:
+ _objc_msgSend$_readStore
+ _objc_msgSend$_resolveTargetFactor
+ _objc_msgSend$_resolvedChargerMultiplier
+ _objc_msgSend$_restrictionRampDurationForPerceptualDelta:
+ _objc_msgSend$_scaledNits:
+ _objc_msgSend$_setNits:
+ _objc_msgSend$_setNits:withFadeSpeed:
+ _objc_msgSend$_setTimeoutSeconds:
+ _objc_msgSend$_snapToTarget:
+ _objc_msgSend$_startFactorRampToTarget:baseNits:
+ _objc_msgSend$_stringForDisplayLogicalState:
+ _objc_msgSend$_stringForDisplayPowerStateEvent:
+ _objc_msgSend$_updateStage
+ _objc_msgSend$addEntriesFromDictionary:
+ _objc_msgSend$appliedNits
+ _objc_msgSend$arm
+ _objc_msgSend$armStartupRampFromNits:duration:
+ _objc_msgSend$armed
+ _objc_msgSend$boolForKey:outValue:
+ _objc_msgSend$calculateNitsCapForLux:
+ _objc_msgSend$cap
+ _objc_msgSend$coerceMode:
+ _objc_msgSend$copyPropertyForKey:andClient:
+ _objc_msgSend$currentCap
+ _objc_msgSend$damping
+ _objc_msgSend$disarm
+ _objc_msgSend$edidBytesMatchDisplay:
+ _objc_msgSend$factorRampInProgress
+ _objc_msgSend$frameInfoProvider
+ _objc_msgSend$frameInfoProviderAttached
+ _objc_msgSend$getProductId
+ _objc_msgSend$getSerialNumber
+ _objc_msgSend$getVendorId
+ _objc_msgSend$handleBrightnessUpdateWithSDRNits:andAppliedHeadroom:
+ _objc_msgSend$handleDisplayBrightnessUpdate:
+ _objc_msgSend$handleServiceArrival:
+ _objc_msgSend$hasPrefix:
+ _objc_msgSend$initWithBacklightService:configuration:
+ _objc_msgSend$initWithBacklightService:queue:
+ _objc_msgSend$initWithBacklightService:systemContext:
+ _objc_msgSend$initWithContext:andDisplayModule:andEDRModule:andEDRThreshold:
+ _objc_msgSend$initWithControlModule:configProvider:queue:
+ _objc_msgSend$initWithNitsControl:configProvider:queue:
+ _objc_msgSend$initWithNitsControl:configProvider:queue:enclosureColorProvider:clockSource:
+ _objc_msgSend$initWithNitsControl:queue:
+ _objc_msgSend$initWithNitsControl:queue:clockSource:
+ _objc_msgSend$initWithProvider:withName:andPrefix:
+ _objc_msgSend$initWithQueue:andSystemContext:
+ _objc_msgSend$initWithQueue:frameInfoProvider:rtplcCapabilities:movingAverageDuration:
+ _objc_msgSend$initWithQueue:logHandle:onReady:
+ _objc_msgSend$initWithQueue:suiteName:nodeName:nvram:externalChange:
+ _objc_msgSend$initWithService:andQueue:andDisplayId:
+ _objc_msgSend$initWithVendorId:productId:serialNumber:queue:
+ _objc_msgSend$initialVelocity
+ _objc_msgSend$initialiseBrightDotMitigation
+ _objc_msgSend$initialiseFrameStats
+ _objc_msgSend$insertNewRampOrigin:target:length:frequency:identifier:profile:
+ _objc_msgSend$isPWMBacklightService:
+ _objc_msgSend$mass
+ _objc_msgSend$newAmmolite
+ _objc_msgSend$newKeyForName:
+ _objc_msgSend$newTwilight
+ _objc_msgSend$numberWithUnsignedShort:
+ _objc_msgSend$probeBrightnessAttempt:
+ _objc_msgSend$rampBDMNitsCap:length:
+ _objc_msgSend$rampFactorToTarget:withLength:useSpringProfile:
+ _objc_msgSend$rampRTPLCCap:to:withSpeed:
+ _objc_msgSend$readControl:currentValue:maxValue:
+ _objc_msgSend$readerWithService:
+ _objc_msgSend$sendBrightnessTransactionRequestForDisplayUUID:builtIn:
+ _objc_msgSend$setBool:forKey:
+ _objc_msgSend$setBootNits:
+ _objc_msgSend$setCalibrationKey:
+ _objc_msgSend$setChargerState:
+ _objc_msgSend$setCurrentHeadroom:
+ _objc_msgSend$setCurrentHeadroomRequest:
+ _objc_msgSend$setDamping:
+ _objc_msgSend$setDisplayBrightnessZero:
+ _objc_msgSend$setInitialVelocity:
+ _objc_msgSend$setMass:
+ _objc_msgSend$setMaxNits:
+ _objc_msgSend$setMaxPercentage:
+ _objc_msgSend$setMinNits:
+ _objc_msgSend$setMinPercentage:
+ _objc_msgSend$setNits:withFadeSpeed:minPWMPercentage:
+ _objc_msgSend$setNits:withFadeSpeed:state:
+ _objc_msgSend$setProperty:forKey:andClient:
+ _objc_msgSend$setReferenceModeState:
+ _objc_msgSend$setStiffness:
+ _objc_msgSend$setUseDynamicFrequency:
+ _objc_msgSend$setupBrightnessModulesExtGeneric:
+ _objc_msgSend$setupLEManager
+ _objc_msgSend$shouldGate
+ _objc_msgSend$stiffness
+ _objc_msgSend$systemContext
+ _objc_msgSend$targetMultiplier
+ _objc_msgSend$transitionLengthFrom:to:
+ _objc_msgSend$updateBDMWithLux:
+ _objc_msgSend$updateExtGenericOwnership
+ _objc_msgSend$updateLux:
+ _objc_msgSend$waitingForProvider
+ _objc_msgSend$writeControl:value:
- -[CBSliderMappingGeneric configureSegmentCoefficients]
- -[CBSliderMappingGeneric copyStatusInfo]
- -[CBSliderMappingGeneric initWithPanelParameters:]
- -[CBSliderMappingGeneric nitsForSlider:]
- -[CBSliderMappingGeneric sliderForNits:]
- -[CBSliderMappingGeneric validateParameters]
- GCC_except_table198
- GCC_except_table235
- GCC_except_table250
- _MAX_SLIDER
- _MIN_SLIDER
- _NON_ZERO_MIN
- _OBJC_CLASS_$_CBSliderMappingGeneric
- _OBJC_IVAR_$_CBSliderMappingGeneric._b1
- _OBJC_IVAR_$_CBSliderMappingGeneric._b2
- _OBJC_IVAR_$_CBSliderMappingGeneric._m1
- _OBJC_IVAR_$_CBSliderMappingGeneric._m2
- _OBJC_IVAR_$_CBSliderMappingGeneric._panelParameters
- _OBJC_IVAR_$_VMDisplayModule._headroomRequestDelegate
- _OBJC_IVAR_$_VMDisplayModule._lastBrightnessTransaction
- _OBJC_METACLASS_$_CBSliderMappingGeneric
- _ZERO_NITS
- _ZERO_SLIDER
- __OBJC_$_INSTANCE_METHODS_CBSliderMappingGeneric
- __OBJC_$_INSTANCE_VARIABLES_CBSliderMappingGeneric
- __OBJC_$_PROP_LIST_CBSliderMappingGeneric
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_VMHeadroomRequestDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_VMHeadroomRequestDelegate
- __OBJC_$_PROTOCOL_REFS_VMHeadroomRequestDelegate
- __OBJC_CLASS_PROTOCOLS_$_CBSliderMappingGeneric
- __OBJC_CLASS_RO_$_CBSliderMappingGeneric
- __OBJC_LABEL_PROTOCOL_$_VMHeadroomRequestDelegate
- __OBJC_METACLASS_RO_$_CBSliderMappingGeneric
- __OBJC_PROTOCOL_$_VMHeadroomRequestDelegate
- _xpc_retain
CStrings:
+ " (clamped)"
+ " (not in table)"
+ "%@ updated (%lu points)"
+ "%@-enabled"
+ "%{public}@ must be finite and > 0 s; using %.4f"
+ "%{public}@ rate must be > 0 nits/s; using the default table"
+ "%{public}s capped at %.4f s (was %.4f)"
+ "%{public}s must be >= 0 s; using %.4f"
+ "ALS event ignored (lux=%.2f): factor ramp in progress"
+ "ALS event ignored (lux=%.2f): not from a built-in ALS"
+ "AMMOLITE_RAMP"
+ "AVService"
+ "Added ALS node %@ (count=%lu)"
+ "AppleARMPWMDevice"
+ "AppliedNits"
+ "BDM"
+ "BDMNits cap transition %f -> %f"
+ "BDM_NITS_CAP_RAMP"
+ "BacklightMode"
+ "Blank"
+ "BrightnessTransaction ignored: display=%@ is not built-in"
+ "CBAmmolite"
+ "CBLEPWMAutoBrightnessModule initialized (mapping table: %lu points, startup ramp %.4fs)"
+ "CBLEPWMContainer started for node '%s'"
+ "CBLEPWMControlModule initialized for node '%s'"
+ "CBTwilight"
+ "ClamshellClosed"
+ "CurrentLevel"
+ "Default minNitsRestriction = %f maxNitsRestriction = %f (ramp rise %.4fs, fall %.4fs)"
+ "DeviceEnclosureColor %d -> charger nits multiplier %.4f%s"
+ "DeviceEnclosureColor unavailable; no charger nits boost for now"
+ "DidDim"
+ "DidSleep"
+ "DidWake"
+ "Dim"
+ "Display brightness update: display=%.2f nits → pwm=%.2f nits"
+ "DisplayBrightnessZero"
+ "DisplayNits"
+ "EDID candidate: ven=0x%04x prod=0x%04x ser=0x%08x | expected: ven=0x%04llx prod=0x%04llx ser=0x%08llx"
+ "EDID does not match this display, skipping"
+ "EDID too short (%ld bytes), skipping"
+ "EDR headroom is being capped by SBIM: request=%f cap=%f"
+ "EDT"
+ "EDT %{public}@ must be finite and > 0; using %.4f"
+ "EDT charger multiplier table invalid (%lu colors, %lu values); using defaults"
+ "ExtGeneric"
+ "ExtGeneric module failed to start, tearing down"
+ "ExtGeneric service lookup failed to start"
+ "FactorOnRampArmed"
+ "FactorOnRampWaitingForProvider"
+ "Fade"
+ "Failed to start LEManager %@"
+ "FinalNits"
+ "Found main display ID = %d"
+ "FrameInfoProviderAttached"
+ "FrozenNits"
+ "Got shutdown notification -> ramping LE PWM factor to 0 (spring)"
+ "IOAVClassMatching returned NULL"
+ "IOAVService"
+ "IOAVServiceCopyEDID failed (0x%x), skipping"
+ "IOAVServiceCreateWithService returned NULL, skipping"
+ "LE PWM state: ALS %.1f lux | display %.1f -> LE %.1f nits, restrictions [%.1f .. %.1f] | limited %.1f x boost %.3f (charger %d) x fade %.3f -> driver %.1f nits"
+ "LEBacklightMode"
+ "LEPWMBrightnessNitsMapping"
+ "LEPWMFactorFadeDuration"
+ "LEPWMFollowFallRateTable"
+ "LEPWMFollowRiseRateTable"
+ "LEPWMFollowTau"
+ "LEPWMFrameInfoProvider"
+ "LEPWMLuxToMaxNitsRestrictionMapping"
+ "LEPWMLuxToMinNitsRestrictionMapping"
+ "LEPWMRestrictionFallDuration"
+ "LEPWMRestrictionRiseDuration"
+ "LEPWMStartupRampDuration"
+ "LEPWMState"
+ "LE_MULTIPLIER_RAMP"
+ "LE_NITS_FOLLOW_RAMP"
+ "Last requested Nits < 0, not initialized, wait for first display update"
+ "LastNits"
+ "Lux=%.2f → maxNitsRestriction ramp %.2f → %.2f nits (ΔP %+.4f) over %.4fs"
+ "Lux=%.2f → minNitsRestriction ramp %.2f → %.2f nits (ΔP %+.4f) over %.4fs"
+ "MAX_NITS_RESTRICTION_RAMP"
+ "MIN_NITS_RESTRICTION_RAMP"
+ "MaxLevel"
+ "MaxNitsRestriction"
+ "MinNitsRestriction"
+ "Multitouch event - X: %{private}f, Y: %{private}f, range: %{private}f, minor r: %{private}f, major r: %{private}f, touch: %{private}d, ALS[%d] obstruction %sdetected"
+ "NVRAM nits commit: display=%.2f nits → light emitter=%.2f nits"
+ "NitsMultiplier"
+ "No %{public}@ SMC key; duty reporting is off"
+ "NodeName"
+ "None"
+ "Notification block key=%@, value=%@"
+ "OPBR"
+ "Offline"
+ "Online (%p)"
+ "PWM"
+ "PWMNitsPreRestriction"
+ "PendingNits"
+ "RTPLC"
+ "RTPLC cap ramp clocked: %f -> %f - %f%%"
+ "RTPLC cap transition %f -> %f (speed=%f)"
+ "RTPLC tables not found"
+ "RTPLC_RAMP"
+ "RampSpringProfileDamping"
+ "RampSpringProfileMass"
+ "RampSpringProfileStiffness"
+ "RampSpringProfileVelocity"
+ "Received ALS event from node %@ (lux=%.2f)"
+ "RegistryID"
+ "Reporting duty cycle to SMC key %{public}@"
+ "SBIMEnabled"
+ "Starting BDM cap ramp to %f over %f seconds cause lux is %f"
+ "TWILIGHT_RAMP"
+ "Unblank"
+ "Undim"
+ "Unexpected brightnessRatio %f, targetPerceptual = %f, currentPerceptual = %f, currentBrightness = %f, targetBrightness = %f"
+ "Unfade"
+ "Unknown(%lld)"
+ "Unknown(%lu)"
+ "Unpowered"
+ "WillDim"
+ "WillSleep"
+ "WillWake"
+ "_applyFactorToHardware factor = %f effective = %f"
+ "_setNits: %.1f deferred (mode 0 disabled)"
+ "_setNits: %.1f frozen (HW write skipped; factor ramp uses %.1f)"
+ "aml"
+ "ammolite"
+ "applying persisted boot nits: %.2f"
+ "attached"
+ "backlight confirmed off (mode 0)"
+ "bklb-backlight"
+ "brightness control read failed for display %u"
+ "brightness update: SDR=%f | EDR.applied=%f | EDR.nits=%f | EDR.req=%f | EDR.curr=%f | EDR.ref=%f | EDR.available=%f | EDR.max=%f | lux=%f | limit=%f | gcp=%f | pcc=%f | Twilight.Strength=%f | Ammolite.Strength=%f | Indicator.brightness=%f | Indicator.limit=%f"
+ "charger %s (state %lu)"
+ "charger nits multiplier: colors=%{public}@ values=%{public}@ (%s), ramp %.4fs, full scale %.2f lux"
+ "charger-nits-multiplier-enclosure-color"
+ "charger-nits-multiplier-full-scale-lux"
+ "charger-nits-multiplier-ramp-duration"
+ "charger-nits-multiplier-value"
+ "clamshell"
+ "clamshell %s"
+ "com.apple.CoreBrightness.CBDisplayModuleExtGeneric"
+ "com.apple.CoreBrightness.CBIOAVServiceLookup"
+ "com.apple.CoreBrightness.CBLEBacklightModeStore"
+ "com.apple.CoreBrightness.CBLEPWMAutoBrightnessModule"
+ "com.apple.CoreBrightness.CBLEPWMContainer"
+ "com.apple.CoreBrightness.CBLEPWMControlModule"
+ "com.apple.CoreBrightness.CBLEPWMNitsMultiplier"
+ "com.apple.CoreBrightness.CBLEPWMNitsRateLimiter"
+ "commitBrightness: rejecting non-finite value"
+ "commitBrightness: slider=%.3f -> level %u/%u"
+ "connected"
+ "constant, everywhere"
+ "copyPropertyForKey: \"%@\""
+ "copyPropertyForKey: unknown key, returning nil"
+ "dealloc: displayId=%u avService=%p"
+ "disconnected"
+ "display %u online — brightness %u/%u (%.2f)"
+ "display brightness %s"
+ "display logical state: %{public}@ -> %{public}@"
+ "display power state: %{public}@ -> %{public}@"
+ "display ready gate armed: holding the factor ON ramp for up to %.0f ms total"
+ "display ready gate opened (%s) %.1f ms after arming"
+ "ext_generic_display_brightness"
+ "factor ON ramp (%s) abandoned: target=%.2f baseNits=%.2f"
+ "factor ON ramp already armed; still waiting for %s"
+ "factor ON ramp wait cancelled (target -> 0)"
+ "factor fade duration override = %.4f s (%s)"
+ "factor ramp %.2f -> %.2f over %.3fs (%s %s, baseNits=%.2f, clamshell=%d, power=%{public}@, logical=%{public}@)"
+ "failed to create BacklightDriverPWM for node '%s'"
+ "failed to create CBLEPWMAutoBrightnessModule for node '%s'"
+ "failed to create CBLEPWMControlModule for node '%s'"
+ "failed to create CBLEPWMNitsMultiplier"
+ "failed to create CBLEPWMNitsRateLimiter"
+ "failed to create ExtGeneric display module"
+ "failed to create notification port"
+ "failed to create the display ready fallback timer; not gating the ON ramp"
+ "failed to create the display ready gate; ON ramps will not wait for the panel"
+ "failed to register IOService notification: 0x%x"
+ "first lit swap"
+ "follow ramp abandoned at %.2f nits (target was %.2f)"
+ "follow ramp engaged: output=%.2f -> target=%.2f (delta=%.2f > %.2f allowed in %.4fs)"
+ "follow ramp yielding to factor ramp; snapping to %.2f"
+ "follow tick: dt=%.5f rate=%.2f remaining=%.3f step=%.3f"
+ "handleServiceArrival: service=%u"
+ "holding the factor ON ramp for the panel (baseNits=%.2f, power=%{public}@, logical=%{public}@)"
+ "init: avService=%p queue=%p"
+ "init: ven=0x%04llx prod=0x%04llx ser=0x%08llx"
+ "initial backlight mode = %ld"
+ "late probe gave up after %d attempts"
+ "late probe: attempt %d cur=%u -> %.3f"
+ "matched IOAVService for display ven=0x%04llx prod=0x%04llx"
+ "max Nits restriction = %f"
+ "min Nits restriction = %f"
+ "mode %ld; from NVRAM"
+ "mode %ld; from defaults"
+ "mode %ld; nothing stored"
+ "newStatusInfo: %@"
+ "nits frozen @ %.2f (WillSleep)"
+ "nits frozen @ %.2f (clamshell closed)"
+ "nits frozen @ %.2f (display brightness zero)"
+ "nits multiplier %.4f -> %.4f (not running, applied at once)"
+ "nits multiplier ramp %.4f -> %.4f over %.4fs (charger=%d lux=%.2f)"
+ "nits unfrozen (factor reached 0); applying pendingNits=%.2f"
+ "nits unfrozen (ramping up to %.2f); applying pendingNits=%.2f"
+ "open"
+ "per-sequence curves"
+ "persistent mode but no boot nits in NVRAM"
+ "provider timeout"
+ "pwm-backlight"
+ "pwm-backlight-control"
+ "rate limiter initialized (rise: %lu points, fall: %lu points, tau: %.4f s)"
+ "read control reply failed: 0x%x"
+ "read control request failed: 0x%x"
+ "read control: bad reply — opcode=0x%02x (expected 0x%02x) result=0x%02x (expected 0x%02x) control=0x%02x (expected 0x%02x)"
+ "readControl: opcode=0x%02x (avService=%p)"
+ "requestDelegate is nil, cannot request brightness transaction"
+ "requestDelegate is nil, ignoring headroom request"
+ "restored"
+ "setNits: requested=%.2f minRestriction=%.2f maxRestriction=%.2f → target=%.2f%s fadeSpeed=%u"
+ "setProperty: %@ expects a CBFrameInfoProvider, got %{public}@"
+ "setProperty: %@ table invalid"
+ "setProperty: key=\"%@\" value=%@ class=%@"
+ "setup ExtGeneric brightness modules"
+ "skipping embedded display"
+ "sleep/wake"
+ "spring profile damping = %.4f"
+ "spring profile initialVelocity = %.4f"
+ "spring profile mass = %.4f"
+ "spring profile stiffness = %.4f"
+ "start: displayId=%u"
+ "start: probe OK — cur=%u max=%u userBrightness=%.4f"
+ "startup ramp armed from %.2f nits over %.4f s"
+ "startup ramp deadline reached; resuming slew-rate limiting"
+ "startup ramp disabled (duration %.4f s)"
+ "startup ramp engaged: %.2f -> %.2f over %.4f s"
+ "startup ramp not needed (target %.2f, output %.2f, bypass %d)"
+ "startup ramp skipped: emitter is dark (applied nits %.2f)"
+ "stop: displayId=%u avService=%p"
+ "swap %u reports the display lit (nominal=%.2f scale=%.3f)"
+ "swap %u: display still dark (nominal=%.2f scale=%.3f)"
+ "swap timeout"
+ "the first lit swap"
+ "the frame info provider"
+ "tw"
+ "twilight"
+ "unable to create light emitter manager"
+ "unable to retrieve node name, using default"
+ "v16@?0@8"
+ "v16@?0q8"
+ "v16@?0r*8"
+ "wait deadline"
+ "waiting up to %.0f ms for the first lit swap (%.1f ms into the wait)"
+ "waiting up to %.0f ms for the frame info provider (%.1f ms into the wait)"
+ "wake event; clearing _shutdownInProgress latch"
+ "write control 0x%02x failed: 0x%x"
+ "writeControl: opcode=0x%02x value=%u (avService=%p)"
- "Multitouch event - X: %f, Y: %f, range: %f, minor r: %f, major r: %f, touch: %d, ALS[%d] obstruction %sdetected"
- "Unexpected brightnessRatio %f, targetPerceptual = %f, currentPerceptual = %f, currentLinearBrightness = %f, targetLinearBrightness = %f"
- "brightness update: SDR=%f | EDR.applied=%f | EDR.nits=%f | EDR.req=%f | EDR.curr=%f | EDR.ref=%f | EDR.available=%f | EDR.max=%f | lux=%f | limit=%f | gcp=%f | pcc=%f | Indicator.brightness=%f | Indicator.limit=%f"
- "headroomRequestDelegate is nil, ignoring headroom request"
```
